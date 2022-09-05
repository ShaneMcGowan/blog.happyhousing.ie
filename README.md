<h1>🏠 The Happy Housing Blog 🏠</h1>

The source to our jekyll blog which is based off the [**Yet Another Theme**](https://github.com/jeffreytse/jekyll-theme-yat/) theme.

## ✨ Features

- Support beautiful __Night Mode__.
- Modern responsive web design.
- Full layouts `home`, `post`, `tags`, `archive` and `about`.
- Uses font awesome 5 for icons.
- Beautiful Syntax Highlight using [hilight.js][hilight-js].
- RSS support using [Jekyll Feed][jekyll-feed] gem.
- Optimized for search engines using [Jekyll Seo Tag][jekyll-seo-tag] gem.
- Sitemap support using [Jekyll Sitemap][jekyll-sitemap] gem.
- New post tag support.

## 🛠️ Setting up Jekyll for local development

Windows docs (can be ignored if following below steps but will include for refreence) https://jekyllrb.com/docs/installation/windows/

- Install Ruby+Devkit V2.7.5 from https://rubyinstaller.org/downloads/
- run `bundle install` to install dependencies.
- running `jekyll -v` at this point will verify if the install worked correctly. If it shows the version number then that means it worked. if not, try restarting and running `bundle install` again.
- run `bundle exec jekyll serve` 
- server will now be available at `http://localhost:4000`

## Theme Config

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at . This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_data`, `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `jekyll-theme-yat.gemspec` accordingly.