# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

gemspec

gem "rubocop-shopify", require: false

group :deployment, :development do
  gem "rake"
end

group :development do
  gem "minitest", "< 5.26.2" # minitest v5.26.2 has dropped support for Ruby 2.7 & 3.0
end

group :test do
  gem "rubocop"
end
