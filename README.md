# tinkertree.github.io

This is a quick and easy blog for our family's nature, science and technology adventures.

It uses Jekyll, runs on GitHub Pages, and is based on the [Millennial theme](https://github.com/LeNPaul/Millennial).

Visit us at [tinkertree.org](https://www.tinkertree.org).


## Installation

### Local Testing

Run:
```
jekyll serve
```

Your site should be up and running locally at [http://localhost:4000](http://localhost:4000).

### Github Pages

Set up GitHub Pages for your repo.

Then, push your changes to the repo, and then your website will be posted at your project's `github.io` location.

### Directory Structure

If you are familiar with Jekyll, then the Millennial directory structure shouldn't be too difficult to navigate. The following some highlights of the differences you might notice between the default directory structure. More information on what these folders and files do can be found in the [Jekyll documentation site](https://jekyllrb.com/docs/structure/).

```bash
Millennial/
├── _data                      # Data files
|  └── settings.yml            # Theme settings and custom text
├── _includes                  # Theme includes
├── _layouts                   # Theme layouts (see below for details)
├── _posts                     # Where all your posts will go
├── assets                     # Style sheets and images are found here
|  ├── css                     # Style sheets go here
|  |  └── _sass                # Folder containing SCSS files
|  |  └── main.scss            # Main SCSS file
|  |  └── syntax.css           # Style sheet for code syntax highlighting
|  └── img                     # Images go here
├── pages                      # Category pages
├── _config.yml                # Site build settings
├── Gemfile                    # Ruby Gemfile for managing Jekyll plugins
├── index.md                   # Home page
├── LICENSE.md                 # License for this theme
├── README.md                  # Includes all of the documentation for this theme
└── rss-feed.xml               # Generates RSS 2.0 file which Jekyll points to
```


## Licensing

The content created for this project, including writings and images, is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0). For more details, see the [LICENSE-CONTENT.md](./LICENSE-CONTENT.md) file or visit [http://creativecommons.org/licenses/by-nc-sa/4.0/](http://creativecommons.org/licenses/by-nc-sa/4.0/).

The Millennial Jekyll theme used in this project is licensed under the MIT License. For more details, see the [LICENSE-THEME.md](./LICENSE-THEME.md) file.