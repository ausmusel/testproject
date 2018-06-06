<!DOCTYPE html>
<html lang="{{ site.lang | default: "en-US" }}">

  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width,maximum-scale=2">
    <link rel="stylesheet" type="text/css" media="screen" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">

{% seo %}
  </head>

  <body>

    <!-- HEADER -->
    <div id="header_wrap" class="outer">
        <header class="inner">
          <a id="forkme_banner" href="{{ site.github.repository_url }}">View on GitHub</a>

          <h1 id="project_title">{{ site.title | default: site.github.repository_name }}</h1>
          <h2 id="project_tagline">{{ site.description | default: site.github.project_tagline }}</h2>

          {% if site.show_downloads %}
            <section id="downloads">
              <a class="zip_download_link" href="{{ site.github.zip_url }}">Download this project as a .zip file</a>
              <a class="tar_download_link" href="{{ site.github.tar_url }}">Download this project as a tar.gz file</a>
            </section>
          {% endif %}
        </header>
    </div>

    <!-- MAIN CONTENT -->
    <div id="main_content_wrap" class="outer">
      <section id="main_content" class="inner">
        {{ content }}
      </section>
    </div>

    <!-- FOOTER  -->
    <div id="footer_wrap" class="outer">
      <footer class="inner">
        {% if site.github.is_project_page %}
        <p class="copyright">{{ site.title | default: site.github.repository_name }} maintained by <a href="{{ site.github.owner_url }}">{{ site.github.owner_name }}</a></p>
        {% endif %}
        <p>Published with <a href="https://pages.github.com">GitHub Pages</a></p>
      </footer>
    </div>

    {% if site.google_analytics %}
      <script>
        (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
        (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
        m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
        })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
        ga('create', '{{ site.google_analytics }}', 'auto');
        ga('send', 'pageview');
      </script>
    {% endif %}
  </body>
</html>
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ausmusel/testproject/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ausmusel/testproject/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
