# README
rails new search-books-with-ransack --database=postgresql

rails generate scaffold book isbn:bigint name author year:integer price:decimal{7-2} status:boolean genre:integer

rails db:create 

rails db:migrate

rails db:seed


# search-books-with-ransack
