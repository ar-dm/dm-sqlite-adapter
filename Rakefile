require 'rubygems'
require 'rake'

begin

  require 'jeweler'

  Jeweler::Tasks.new do |gem|
    gem.name        = 'dm-sqlite-adapter'
    gem.summary     = 'Sqlite3 Adapter for DataMapper'
    gem.description = gem.summary
    gem.authors     = ["Dan Kubb"]
    gem.email       = %q{dan.kubb@gmail.com}
    gem.homepage    = 'http://github.com/datamapper/dm-sqlite-adapter'

    gem.add_dependency 'do_sqlite3',        '~> 0.10.1'
    gem.add_dependency 'dm-do-adapter',     '~> 0.10.3'

    gem.add_development_dependency 'rspec', '~> 1.3'
    gem.add_development_dependency 'yard',  '~> 0.5'
  end

  Jeweler::GemcutterTasks.new

  FileList['tasks/**/*.rake'].each { |task| import task }
rescue LoadError
  puts 'Jeweler (or a dependency) not available. Install it with: gem install jeweler'
end