require 'pry'
task :environment do
  require_relative './config/environment'
end

desc 'outputs hello to the terminal'
task greeting:hello do
  puts "hello from Rake!"
end

desc 'outputs hola to the terminal'
task greeting:hola do
puts "hola de Rake!"
end

task :console do
  Pry.start
end
