#------------------------------------------------------------------------
# Gemfile
#------------------------------------------------------------------------

source 'http://rubygems.org'

gem "middleman",            "~> 3.4"
gem "middleman-deploy"
gem "middleman-imageoptim", "~> 0.2"
gem "middleman-livereload", "~> 3.4"
gem "middleman-minify-html"

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

# Cross-templating language block fix for Ruby 1.8
platforms :mri_18 do
  gem "ruby18_source_location"
end
