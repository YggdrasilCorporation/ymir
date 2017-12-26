source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# Specify your gem's dependencies in ymir.gemspec
gemspec

group :doc do
  gem 'yard'
  gem 'asciidoctor'
  gem 'asciidoctor-diagram'
end

group :development do
  gem 'etude_for_aws', '~> 0.7.10'
  gem 'etude_for_ops', git: 'https://github.com/k2works/etude_for_ops.git', branch: 'feature/aws_ruby_staging'
end
