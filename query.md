1 - SELECT * FROM `students` WHERE YEAR(date_of_birth) = 1990;

2 - SELECT * FROM `courses` WHERE cfu > 10;

3 - SELECT * FROM `students` WHERE TIMESTAMPDIFF(YEAR,`date_of_birth`,1 - CURRENT_DATE) > 30;

4 - SELECT * FROM `courses` WHERE `year` = 1 AND `period` = 'I semestre';

5 - SELECT * FROM `exams` WHERE `date` = '2020-06-20' AND `hour` > '14:00:00';

6 - SELECT * FROM `degrees` WHERE `level` = 'magistrale';