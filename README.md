# Questions

For each of the following questions, you should write a single SQL query that outputs the results specified by each problem. Your response must take the form of a single SQL query. You should not assume anything about the ids of any particular rows: your queries should be accurate even if the ids were different. Finally, each query should return only the data necessary to answer the question.

## 1.sql
Your colleague is preparing a map of all public schools in Massachusetts. In 1.sql, write a SQL query to find the names and cities of all public schools in Massachusetts.

Keep in mind that not all schools in the schools table are considered traditional public schools. Massachusetts also recognizes charter schools, which (according to DESE!) are considered distinct.

## 2.sql
Your team is working on archiving old data. In 2.sql, write a SQL query to find the names of districts that are no longer operational.

Districts that are no longer operational have “(non-op)” at the end of their name.

## 3.sql
The Massachusetts Legislature would like to learn how much money, on average, districts spent per-pupil last year. In 3.sql, write a SQL query to find the average per-pupil expenditure. Name the column “Average District Per-Pupil Expenditure”.

Note the per_pupil_expenditure column in the expenditures table contains the average amount, per pupil, each district spent last year. You’ve been asked to find the average of this set of averages, weighting all districts equally regardless of their size.

## 4.sql
Some cities have more public schools than others. In 4.sql, write a SQL query to find the 10 cities with the most public schools. Your query should return the names of the cities and the number of public schools within them, ordered from greatest number of public schools to least. If two cities have the same number of public schools, order them alphabetically.

## 5.sql
DESE would like you to determine in what cities additional public schools might be needed. In 5.sql, write a SQL query to find cities with 3 or fewer public schools. Your query should return the names of the cities and the number of public schools within them, ordered from greatest number of public schools to least. If two cities have the same number of public schools, order them alphabetically.

## 6.sql
DESE wants to assess which schools achieved a 100% graduation rate. In 6.sql, write a SQL query to find the names of schools (public or charter!) that reported a 100% graduation rate.

## 7.sql
DESE is preparing a report on schools in the Cambridge school district. In 7.sql, write a SQL query to find the names of schools (public or charter!) in the Cambridge school district. Keep in mind that Cambridge, the city, contains a few school districts, but DESE is interested in the district whose name is “Cambridge.”

## 8.sql
A parent wants to send their child to a district with few other students. In 8.sql, write a SQL query to find the name (or names) of the school district(s) with the single least number of pupils. Report only the name(s).
 per-pupil expenditure (high to low).


# Hand-in

Test your solution by executing the following command on the bash terminal:

```shell
$ pytest
```

When you are satisified, execute the following commands to submit:

```shell
$ git add -A
$ git commit -m 'submit'
$ git push
```
