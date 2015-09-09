# Akita

The backend of <http://single.dog>


### Requirements

- Ruby 2.1.6 +
- PostgreSQL 9.3 +


### How to development

```
git clone https://github.com/1dog/akita.git
cd akita
cp config/database{,.yml}
cp config/secrets{,.yml}

emacs config/database.yml   # edit username, password

rake db:create              # create database
rake db:migrate             # sync schema

rails server                # Goto http://localhost:3000

```


### License

© 2015 Single.dog

Released under the [MIT license](http://www.opensource.org/licenses/MIT).
