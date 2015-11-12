# akkaTestProject
To run project just set program arguments:
first - name of file, from which to read data;
second - name of file, to which to write data;
third - number of handlers to handle data.
Then run main() in Main.class.
Task:
We have file on 100 000 lines, lines have data in format "ID; amount"; Total of different ID in file 1000 pieces.
Using Akka we need to aggregate all operations on each ID and write result in individual file.

Задание:
Есть файл на 100000 строк, в нем записи в формате "ID;amount"; Всего уникальных ID в файле 1000 штук. 
Используя Akka необходимо просуммировать все операции по каждому ID и записать агрегированный результат в отдельный файл.
