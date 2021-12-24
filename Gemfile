# frozen_string_literal: true
source "https://rubygems.org"
git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }
gem "github-pages", group: :jekyll_plugins
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "webrick", "~> 1.7"
gem "just-the-docs"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# below is the Gemfile when using `jekyll serve`
# source "https://rubygems.org"
# gem "jekyll", "~> 4.2.1"
# gem "minima", "~> 2.5"
# group :jekyll_plugins do
#     gem "jekyll-feed", "~> 0.12"
# end
# platforms :mingw, :x64_mingw, :mswin, :jruby do
#     gem "tzinfo", "~> 1.2"
#     gem "tzinfo-data"
# end
# gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
# gem "just-the-docs"
# gem "webrick", "~> 1.7"
