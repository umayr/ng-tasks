Click here and fork the [plunk](http://plnkr.co/edit/zEEAp84GgBVLk9J0jIp8?p=preview)

###The Data
Your data is available on a scope variable called countries. countries is an array of objects. The objects are of the form:

```
name: country name
code: country code
1960: population size in 1960
1961: population size in 1961
...n: population size in ...n
Years 1960 to 2012 are covered.
```

###Requirements
Using only built-in filters and directives, modify the template so that you have a table displaying a row for each country in countries. 

- Each row should contain the following:
```
Country name
1960 population
1970 population
1980 population
1990 population
2000 population
2010 population
Percentage growth between 1960 and 2010
```
- There should be a table header for each column.
- In row entries, numbers should be displayed with commas and no decimal places.
- The rows should be ordered by country name.
It's up to you to write CSS to make this table look pretty.
