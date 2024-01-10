# SQLBolt-Exercise-Answers
I've completed the SQL Bolt practice exercises and am happy to share my solutions! Below are the queries for each exercise.

Feel free to use these as a reference or contribute improvements. If you have any questions or suggestions, please don't hesitate to reach out.

Happy coding!

## SQL Lesson 1: SELECT queries 101

### 1. Find the title of each film
```sql
SELECT title FROM movies;
```

### 2. Find the director of each film
```sql
SELECT director FROM movies;
```

### 3. Find the title and director of each film
```sql
SELECT title, director FROM movies;
```

### 4. Find the title and year of each film
```sql
SELECT title, year FROM movies; 
```

### 5. Find all the information about each film
```sql
SELECT * FROM movies;
```

## SQL Lesson 2: Queries with constraints (Pt. 1)

### 1. Find the movie with a row id of 6
```sql
SELECT id, title FROM movies 
WHERE id = 6;
```

### 2. Find the movies released in the years between 2000 and 2010
```sql
SELECT title, year FROM movies
WHERE year BETWEEN 2000 AND 2010;
```

### 3. Find the movies not released in the years between 2000 and 2010
```sql
SELECT title, year FROM movies
WHERE year < 2000 OR year > 2010;
```


### 4. Find the first 5 Pixar movies and their release year
```sql
SELECT title, year FROM movies
WHERE year <= 2003;
```
