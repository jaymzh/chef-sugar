source "https://rubygems.org"
gemspec name: "chef-sugar"

group :debug do
  gem "pry"
  gem "pry-byebug"
  gem "pry-stack_explorer"
end

group :test do
  gem "chefspec", "~> 7.4.0" # supports Chef 13+ aka ruby 2.3+
  gem "rake"
end

group :kitchen do
  gem "kitchen-vagrant"
  gem "test-kitchen"
end
