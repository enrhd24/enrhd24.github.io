---
layout: post
title: "jekyll + Theme"
date: 2023-03-21 12:20:00 +0900
categories: jekyll
tag: [ruby, google]
---

> git.io install jekyll
1. username.github.io Create a new repository
2. echo "Hello world" > index.html
3. [Ruby+Devkit](https://rubyinstaller.org/downloads/)
4. gem install jekyll bundler
5. git rm index.html , jekyll new ./ --force 
6. bundle install , bundle exec jekyll serve

---

> git.io jekyll install Theme
1. add gem 'jekyll-theme-hamilton' into Gemfile
   add _config.yml <br>
   ``` plugins: - jekyll-theme-hamilton <br>
        remote_theme : ngzhio/jekyll-theme-hamilton
   ```
2. download zip and move username git.io/ 


