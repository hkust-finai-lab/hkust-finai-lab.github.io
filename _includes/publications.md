<h1 id="publications"></h1>

<h2 style="margin: 30px 0px -15px;">Publications 
    <temp style="font-size:15px;">[</temp>
    <a href="https://scholar.google.com/citations?user=lxrXMY0AAAAJ&hl=en&oi=ao" target="_blank" style="font-size:15px;">Google Scholar</a>
    <temp style="font-size:15px;">]</temp>
    <temp style="font-size:15px;">[</temp>
    <a href="https://www.researchgate.net/profile/Zixuan-Yuan" target="_blank" style="font-size:15px;">ResearchGate</a>
    <temp style="font-size:15px;">]</temp>
</h2>
<br>

* means equal contribution.<br>
† means corresponding authors.

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="publication-entry" style="margin-bottom: 30px; display: flex; flex-direction: column; align-items: center;">
  <div class="col-sm-12 abbr" style="position: relative; text-align: center; padding: 15px; max-width: 800px;">
      <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width: auto; height: auto; max-width: 100%; object-fit: contain; margin-bottom: 20px;">
      <abbr class="badge" style="position: absolute; top: 10px; left: 10px; background: #002D72; color: white; padding: 5px;">{{ link.conference_short }}</abbr>
  </div>
  <div class="col-sm-12" style="padding: 15px; text-align: center; margin-top: 15px; max-width: 800px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em></div>
      <div class="links">
        {% if link.pdf %} 
        <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
        {% endif %}
        {% if link.code %} 
        <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
        {% endif %}
        {% if link.page %} 
        <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
        {% endif %}
        {% if link.bibtex %} 
        <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
        {% endif %}
        {% if link.web %} 
        <a href="{{ link.web }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Website</a>
        {% endif %}
        {% if link.notes %} 
        <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
        {% endif %}
        {% if link.others %} 
        {{ link.others }}
        {% endif %}
      </div>
  </div>
</div>
</li>

{% endfor %}
</ol>
</div>
