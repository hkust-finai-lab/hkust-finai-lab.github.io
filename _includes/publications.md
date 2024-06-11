<h1 id="publications"></h1>

<h2 style="margin: 30px 0px -15px;">Publications <temp style="font-size:15px;">[</temp><a href="https://scholar.google.com/citations?user=lxrXMY0AAAAJ&hl=en&oi=ao" target="_blank" style="font-size:15px;">Google Scholar</a><temp style="font-size:15px;">]</temp><temp style="font-size:15px;">[</temp><a href="https://www.researchgate.net/profile/Zixuan-Yuan" target="_blank" style="font-size:15px;">ResearchGate</a><temp style="font-size:15px;">]</temp></h2><br>

 \* means equal contribution.<br>
 † means corresponding authors.

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}
{% if forloop.counter == 3 %}
        {% break %}
    {% endif %}
<li>
<div class="publication-entry" style="margin-bottom: 30px;">
  <div class="col-sm-12 abbr" style="position: relative; text-align: center; padding: 15px;">
      <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width: auto; height: auto; object-fit: contain; margin-bottom: 20px;">
      <abbr class="badge" style="position: absolute; top: 10px; left: 10px; background: #002D72; color: white; padding: 5px;">{{ link.conference_short }}</abbr>
  </div>
  <div class="col-sm-12" style="padding: 15px; text-align: center; margin-top: 15px;">
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

<li>
    <div class="publication-entry" style="margin-bottom: 30px;">
      <div class="col-sm-12 abbr" style="position: relative; text-align: center; padding: 15px;height: 350px;">
          <img src="{{ site.data.publications.main.image1 }}" class="teaser img-fluid z-depth-1" style="width: auto; height: auto; object-fit: contain; margin-bottom: 20px;">
          <abbr class="badge" style="position: absolute; top: 10px; left: 10px; background: #002D72; color: white; padding: 5px;">{{ site.data.publications.main.conference_short1 }}</abbr>
      </div>
      <div class="col-sm-12" style="padding: 15px; text-align: center; margin-top: 15px;">
          <div class="title"><a href="{{ site.data.publications.main.pdf1 }}">{{ site.data.publications.main.title1 }}</a></div>
          <div class="author">{{ site.data.publications.main.authors1 }}</div>
          <div class="periodical"><em>{{ site.data.publications.main.conference1 }}</em></div>
          <div class="links">
            {% if site.data.publications.main.pdf1 %} 
            <a href="{{ site.data.publications.main.pdf1 }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
            {% endif %}
            {% if site.data.publications.main.code1 %} 
            <a href="{{ site.data.publications.main.code1 }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
            {% endif %}
            {% if site.data.publications.main.page1 %} 
            <a href="{{ site.data.publications.main.page1 }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
            {% endif %}
            {% if site.data.publications.main.bibtex1 %} 
            <a href="{{ site.data.publications.main.bibtex1 }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
            {% endif %}
            {% if site.data.publications.main.web1 %} 
            <a href="{{ site.data.publications.main.web1 }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Website</a>
            {% endif %}
            {% if site.data.publications.main.notes1 %} 
            <strong> <i style="color:#e74d3c">{{ site.data.publications.main.notes1 }}</i></strong>
            {% endif %}
            {% if site.data.publications.main.others1 %} 
            {{ site.data.publications.main.others1 }}
            {% endif %}
          </div>
      </div>
    </div>
</li>

{% for link in site.data.publications.main2 %}
<li>
        <div class="publication-entry" style="margin-bottom: 30px;">
          <div class="col-sm-12 abbr" style="position: relative; text-align: center; padding: 15px;">
              <img src="{{ link.image2 }}" class="teaser img-fluid z-depth-1" style="width: auto; height: auto; object-fit: contain; margin-bottom: 20px;">
              <abbr class="badge" style="position: absolute; top: 10px; left: 10px; background: #002D72; color: white; padding: 5px;">{{ link.conference_short2 }}</abbr>
          </div>
          <div class="col-sm-12" style="padding: 15px; text-align: center; margin-top: 15px;">
              <div class="title"><a href="{{ link.pdf2 }}">{{ link.title2 }}</a></div>
              <div class="author">{{ link.authors2 }}</div>
              <div class="periodical"><em>{{ link.conference2 }}</em></div>
              <div class="links">
                {% if link.pdf2 %} 
                <a href="{{ link.pdf2 }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
                {% endif %}
                {% if link.code2 %} 
                <a href="{{ link.code2 }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
                {% endif %}
                {% if link.page2 %} 
                <a href="{{ link.page2 }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
                {% endif %}
                {% if link.bibtex2 %} 
                <a href="{{ link.bibtex2 }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
                {% endif %}
                {% if link.web2 %} 
                <a href="{{ link.web2 }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Website</a>
                {% endif %}
                {% if link.notes2 %} 
                <strong> <i style="color:#e74d3c">{{ link.notes2 }}</i></strong>
                {% endif %}
                {% if link.others2 %} 
                {{ link.others2 }}
                {% endif %}
              </div>
          </div>
        </div>
        
</li>
{% endfor %}
<br>

