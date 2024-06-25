Jekyll Website
=======================
#### This is my personal website which you can view [here](https://shreya-boyapati.github.io/start/)

Author
---
Shreya Boyapati

Purpose
---
- Create a custom static site using Ruby, Jekyll, and Sass
- Deploy site to GitHub pages

Home Page
---
- Home page containes content on my background created on [index.html](https://github.com/Shreya-Boyapati/start/blob/gh-pages/index.html)
- Creates jump links to subsections with href attributes
- Each subsection containerized as div
- [FontAwesome](https://fontawesome.com/start) script used for icons

Layout and Formatting
---
- Layout of headings, subheadings, fonts, spacing, and headers created in [_layout.scss](https://github.com/Shreya-Boyapati/start/blob/gh-pages/_sass/_layout.scss)
- Coloring and font selection created in [_base.scss](https://github.com/Shreya-Boyapati/start/blob/gh-pages/_sass/_base.scss)

Page Organization
---
- Each subpage is listed in the [_pages folder](https://github.com/Shreya-Boyapati/start/tree/gh-pages/_pages)
- Each subpage contains title and permalink which is used to populate the navigation menu
- Contains link to my resume and links resume to navigation menu

Configuration
---
- Set _config.yml with key info for site
  - title
  - description: content which will appear in document head meta
  - baseurl: subpath of site eg. /start
  - url: hostname and protocol of site
- Set build settings for site
  - sass_dir: location of sass files to ensure correct compilation
  - include: pages to be included in directory eg. ['_pages']
  - kramdown: type of markdown to be processed

Installing, Compiling and Running site 
---
- To build from the command line Jekyll, Ruby, and Bundler should be installed and configured
- Once all prerequisites are met, clone [start](https://github.com/Shreya-Boyapati/start) using the command ```git clone```
- Load as a new jekyll project
- Run the command ```jekyll serve --config _config.yml,_config_dev.yml``` to watch the project
- Open ```http://localhost:4000``` to view it in your browser. The page will refresh automatically when changes are made.
- To open as a github page, set build and deployment source as ```Deploy from branch``` and branch as ```gh-pages``` with ```(root)``` folder

Testing
---
