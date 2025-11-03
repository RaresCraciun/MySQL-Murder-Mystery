# Disclaimer
This is just a MySQL adaptation of the original [SQL Murder Mistery](https://github.com/NUKnightLab/sql-mysteries.git) which used SQLite. This GitHub page is also adapted from the original repository.

# SQL Murder Mystery
There's been a Murder in SQL City! The SQL Murder Mystery is designed to be both a self-directed lesson to learn SQL concepts and commands and a fun game for experienced SQL users to solve an intriguing crime.

If you just want to solve the mystery, use the [MySQL dump file](https://github.com/RaresCraciun/MySQL-Murder-Mystery/blob/main/MySQL_Murder_Mistery_dump.sql) to create the database. 
If you're new to SQL, you may want to start at [the walkthrough](https://mystery.knightlab.com/walkthrough.html). It won't teach you everything about SQL, but it should teach you all that you need to solve the mystery.  

## What you need to solve on your own computer
          
* **MySQL_Murder_Mistery_dump.sql**: This MySQL dump file which creates the data that you will be working with.
* **prompt**: Depending on your experience level with SQL, find the prompt in either the [prompt experienced](https://github.com/RaresCraciun/MySQL-Murder-Mystery/blob/e838fb84439020cb7ec3ddb78d4b21563c39e517/prompt_experienced.pdf) file or the [prompt_beginner](https://github.com/RaresCraciun/MySQL-Murder-Mystery/blob/e838fb84439020cb7ec3ddb78d4b21563c39e517/prompt_beginner.pdf) file.
* **a MySQL environment of your choice**.

## Getting Started

* Download the [MySQL_Murder_Mistery_dump.sql](https://github.com/RaresCraciun/MySQL-Murder-Mystery/blob/main/MySQL_Murder_Mistery_dump.sql) file and use a MySQL environment of your choice to solve the mystery. Read the [prompt_beginner](https://github.com/RaresCraciun/MySQL-Murder-Mystery/blob/e838fb84439020cb7ec3ddb78d4b21563c39e517/prompt_beginner.pdf) or the [prompt_experienced](https://github.com/RaresCraciun/MySQL-Murder-Mystery/blob/main/prompt_beginner.pdf) file. You can use the reference to refresh your memory of SQL. Try to complete the activity all within your SQL environment (without writing down notes)!


## Checking the Solution
Write the following queries in your SQL environment to check whether you've found the right murderer:

```SQL
INSERT INTO solution
VALUES (1, 'Insert the name of the person you found here');

SELECT value FROM check_if_solution_is_correct;
```


## Original Authors

* [Joon Park](https://twitter.com/JoonParkMusic)
* [Cathy He](https://twitter.com/Cathy_MeiyingHe)
  
* Adapted to MySQL by Rareș Crăciun

## Inspiration
This murder mystery was inspired by [a crime in the neighboring Terminal City](https://github.com/veltman/clmystery "command-line murder mystery").

## Copyright and License
Original code for this project is released under [the MIT License](https://github.com/NUKnightLab/sql-mysteries/blob/master/LICENSE). 

Original text and other content is released under [Creative Commons CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). 

SQL query custom web components used here were adapted from code created and released to the public domain by Zi Chong Kao, creator of [Select Star SQL](https://selectstarsql.com/).

[Detective image by rambleron](https://www.vecteezy.com/vector-art/174092-clue-illustration) used under Vecteezy's free license.
