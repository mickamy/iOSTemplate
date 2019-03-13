source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem 'fastlane'
gem 'rake'
gem 'synx'

install_if -> { RUBY_PLATFORM =~ /darwin/ } do
  gem 'cocoapods'
  gem 'cocoapods-deintegrate'
end

