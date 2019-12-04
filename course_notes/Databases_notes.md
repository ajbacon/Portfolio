# Database Notes


## pg

Example of executing a QUERY in ```pg```

``` ruby
connection = PG.connect(dbname: 'bookmark_manager')
result = connection.exec("SELECT * FROM bookmarks;")
```


## Useful links

[SQL Cheatsheet 1](http://www.cheat-sheets.org/sites/sql.su/)
[SQL Cheatsheet 2](https://blog.jasonmeridth.com/posts/postgresql-command-line-cheat-sheet/)
