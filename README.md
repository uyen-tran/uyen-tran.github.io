# Uyen's Personal Webpage

Powered by Jekyll and [Minimal Light Theme](https://minimal-light-theme.yliu.me/)
 
## Project Architecture

```
.
├── _data
|   ├── navigation.yml                        # the YAML file for the navigation bar
|   └── publications.yml                      # the YAML file for publications
├── _includes
|   ├── conferences.md                        # the Markdown file for conferences and workshops attended
|   ├── misc.md                               # the Markdown file for miscellaneous
|   ├── navigation-home.md                    # the Markdown file for the navigation bar on homepage
|   ├── navigation.md                         # the Markdown file for the navigation bar on all pages except homepage         
|   ├── publications.md                       # the Markdown file for publications
|   ├── research.md                           # the Markdown file for research related activities
|   ├── service.md                            # the Markdown file for service and outreach
|   └── teaching.md                           # the Markdown file for teaching history, etc.
├── _layouts
|   ├── default.html                          #  the html layout for all pages except homepage               
|   └── homepage.html                         #  the html layout for the homepage 
├── _sass
|   ├── minimal-light.scss                    #  this file will be compiled into a CSS file to control the style of the page              
|   └── minimal-light-no-dark-mode.scss       #  this file is similar to minimal-light.scss with the dark mode disabled
├── assets                                    #  some files
├── html_source_file                          #  compiled HTML files
├── .gitignore                                #  this file specifies intentionally untracked files that Git should ignore
├── CNAME                                     #  the custom domain, will be used by GitHub page service
├── Gemfile                                   #  a RubyGems related file
├── README.md                                 #  the readme file (English)
├── _config.yml                               #  the Jekyll configuration file, including some options of the page  
└── index.md                                  #  the content of the index page, using Markdown
```

### Using the HTML version

The compiled HTML files are available in the `html_source_file` folder. If you don't like Jekyll, you may directly edit and use the HTML version.

## Customizing

### Configuration variables

The Minimal Light theme will respect the following variables, if set in your site's `_config.yml`:

  ```yaml
# Basic Information 
title: Your Name
position: Ph.D. Student
affiliation: Your Affiliation
email: yourname (at) example.edu

# Search Engine Optimization (SEO)
# The following information is used to improve the website traffic from search engines, e.g., Google.
keywords: minimal light
description: The Minimal Light is a simple and elegant jekyll theme for academic personal homepage.
canonical: https://minimal-light-theme.yliu.me/

# Links 
# If you don't need one of them, you may delete the corresponding line.
google_scholar: https://scholar.google.com/
cv_link: assets/files/curriculum_vitae.pdf
github_link: https://github.com/
linkedin: https://www.linkedin.com/
twitter: https://twitter.com/

# Images (e.g., your profile picture and your website's favicon) 
# "favicon" and "favicon_dark" are used for the light and dark modes, respectively. 
avatar: ./assets/img/avatar.png
favicon: ./assets/img/favicon.png
favicon_dark: ./assets/img/favicon-dark.png

# Footnote
# You may use the option to disable the footnote, "Powered by Jekyll and Minimal Light theme."
enable_footnote: true

# Auto Dark Mode
# You may use the option to disable the automatic dark theme
auto_dark_mode: true

# Font
# You can use this option to choose between Serif or Sans Serif fonts.
font: "Serif" # or "Sans Serif"

# Google Analytics ID
# Please remove this if you don't use Google Analytics
google_analytics: UA-111540567-4
  ```
### Edit `index.md`

Create `index.md` and add your personal information. It supports **Markdown** and **HTML** syntax.

### Add/edit tabs on navigation bar
Add a **Markdown** file to `_includes/` and add the data to `_data/navigation.yml`.


### Stylesheet

If you'd like to add your own custom styles, you may edit `_sass/minimal-light.scss`.

### Layouts

If you'd like to change the theme's HTML layout, you may edit `_layouts/homepage.html` and `_layouts/default.html`.

## Acknowledgements

This project uses the source code from the following repositories:

* [https://github.com/yaoyao-liu/minimal-light](https://github.com/yaoyao-liu/minimal-light)

* [https://github.com/yaoyao-liu/yaoyao-liu.github.io](https://github.com/yaoyao-liu/yaoyao-liu.github.io)
