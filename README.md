# laravel-heroku-example

## Procedure to run app

```
git clone https://github.com/sogaoh/laravel-heroku-example.git

cd /path/to/application/run

make local
make up
make chmod

make upb

make web

# In web Container
make npmid    # build js
exit

make app

# In app Container
make fresh    # migration 
exit

open http://localhost:3100
```
