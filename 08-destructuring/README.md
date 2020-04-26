# Домашка
1. Создай репозиторий skillup-hw-js-08
1. Задания выполнены в отдельном файле task-номер_задания.js
1. Используй общий html файл для подключения js файлов.

# Задание
1. Используя rest оператор и деструктуризацию, создать функцию, которая принимает любое количество аргументов и возвращает объект, содержащий первый аргумент и массив из остатка:
   ```
   func(‘a’, ‘b’, ‘c’, ‘d’) → 
   {
     first: ‘a’,
     other: [‘b’, ‘c’, ‘d’]
   }
   ```
   
1. Организовать функцию getInfo, которая принимает объект вида
   
   `{ name: ...,  info: { employees: [...], partners: [ … ]  } }`
   
   и выводит в консоль имя (если имени нет, показывать ‘Unknown’) и первые две компании из массива partners:
   
   ```
   const organisation = {  
     name: 'Google',   
     info: { employees: [‘Vlad’, ‘Olga’], partners: ['Microsoft', 'Facebook', 'Xing']   } 
   };
   getInfo(organisation); → 
   Name: Google 
   Partners: Microsoft Facebook
   ```

   
   
