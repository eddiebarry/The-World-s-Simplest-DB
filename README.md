# Presenting the worlds simplest key - value db

###### Seriously, it's just a bash script

#### To run, first import the db into your env
```
source simple_db.sh
```

#### Only two functions are exposed, 

##### Set
```
db_set GameOfThronesSeason8 '{"writing":"Terrible","acting":"They did what they could","dany":"BAE<3","jon":"KING"}'
```

##### Get
```
db_get GameOfThronesSeason8
```

#### Please dont use this as anything except in the most rudimentary cases
## For the love of GOD please don't use in prod