# README

## A noter que :
Je Me suis arrêté après avoir crée les Tags et le seed correspondant...
Il était déjà trop tard...


* Ruby version : 2.7.1

* Rails 5.2.4.2

Lancement :

Aller à la racine (freedoc chez moi) là ou se trouve le Gemfile

$ bundle install

au choix :

execution du seed.rb :

$ rails db:seed

puis allez dans la console pour tester

$ rails console



###  A noter que mon Gemfile a été enrichi comme ci-dessous :
# Gemfile adds 
gem 'tzinfo-data', '>= 1.2016.7'

# gem added specialy for this project 
gem 'table_print'
gem 'faker'