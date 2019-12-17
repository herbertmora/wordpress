rm Gemfile.lock
rm Gemfile
echo "source 'https://rubygems.org'" >> Gemfile
echo "gem 'rake'" >> Gemfile
echo "gem 'activerecord'" >> Gemfile
echo "gem 'pg'" >> Gemfile
bundle install
bundle exec rake -T
echo "gem 'rspec'" >> Gemfile
echo "gem 'faker'" >> Gemfile
bundle install
bundle exec rake -T
