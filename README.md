# text-generator
Код, генерирующий текст на основе цепей Маркова.

reader.py – считывает обучающий текст из файла и токенизирует его. Загружает полученный словарь в файл dict.txt

main.py – содержит класс Generator, который по словарю из файла dict.txt строит цепочку. 

input.txt – файл с обучающим текстом
