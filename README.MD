ES 1

SELECT \* FROM `students` WHERE `date_of_birth`LIKE '1990-%' RESULT(160)

ES 2
SELECT \* FROM `courses` WHERE `cfu`>10; RESULT(479)

ES 3
SELECT \* FROM `students` WHERE `date_of_birth`<'1994'; RESULT(3646)

ES4
SELECT \* FROM `courses` WHERE `period`='I semestre'&& `year`=1; RESULT(286)

ES5
SELECT \* FROM `exams` WHERE`date`='2020-06-20' && `hour` >'14:00:00'; RESULT(21)

ES6
SELECT \* FROM `degrees`WHERE `name` LIKE '%Laurea Magistrale%'; RESULT(38)

ES7
SELECT COUNT(\*) FROM `departments`; RESULT(12)

ES8
SELECT \* FROM `teachers` WHERE `phone`IS null; RESULT(50)

ES9
