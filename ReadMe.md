############ 11/11/20 ################
Jekyll is a static site generator
Gems are code you can include in Ruby projects. 
A Gemfile is a list of gems used by your site.
Bundler is a gem that installs all gems in your Gemfile.
To install gems in your Gemfile using Bundler, run the following in the directory that has the Gemfile:
	bundle install
	bundle exec jekyll serve
Liquid is a templating language which has three main parts: objects, tags and filters.
{{page.title}} Objects tell Liquid where to output content.
{% if page.show_sidebar %} Tags create the logic and control flow for templates.
{{ "hi"| capitalize }} Filters change the output of a Liquid object.


0. create DIRECTORY e.g. "JelyllTest"
Generates a Gemfile into the current working directory
1. $ bundle init

Now edit the Gemfile and add jekyll as a dependency:
bundle add <gem-name> <version>
2. gem "jekyll"
install missing gems (based on Gemfile)
3. $ bundle install

4. $ bundle exec jekyll new . --force

5. $ bundle exec jekyll serve
6. $ bundle exec jekyll serve --livereload

changes to _config.yml 
bundle exec jekyll build
bundle
e.g. bundle info minima


theme slate, Github Pages: changes to _config.yml, Gemfile
$ bundle install
$ bundle update github-pages
$ bundle update 


