source 'https://rubygems.org'

# eventmachine is a dependency of jekyll for `jekyll serve` CLI
# In order to build eventmachine on MacOs, will require homebrew openssl package :
# `brew install openssl`
# Many solutions around using Bundler will not work.
# The solution is to manually build with `gem install eventmachine -- --with-cppflags=-I/usr/local/opt/openssl/include`
# If you are using RVM and Gemsets, be sure you are in the ruby version/gemset you expect Bundler to use.
# After the `gem install... ` then `bundle` will pass successfully.
# Whew!

# enable pure_ruby engine to allow `jekyll serve --livereload` to work correctly
gem 'webrick'
gem 'jekyll'
gem 'jekyll-redirect-from'
gem 'jekyll-environment-variables'
