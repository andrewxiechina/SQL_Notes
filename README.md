# SQL_Notes

# Unique
```SQL
SELECT DISTINCT city FROM station WHERE countrycode = 'US'
```

# Count
```SQL
SELECT (COUNT(city) - COUNT(DISTINCT city)) FROM station
```
