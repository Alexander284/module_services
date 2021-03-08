# service_postData
1. Для использования модуля необходимо установить npm пакеты:
   - npm init -y
   - npm install webpack webpack-cli --save-dev

2. Важно обращать внимания на пути в файле webpack.config.js

3. Для импорта в нужный js файл (путь указан из корня того файла, в который производится импорт): 

```javascript   
   import {postData} from '../services/services';
```
  - первый аргумент url - путь, куда передается запрос;
  - второй агрумент data - данные, которые передаются, например в формате JSON
  	
4. Чтобы собрать с помощью webpack, использовать команду: npx webpack.
