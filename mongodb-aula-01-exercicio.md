# MongoDB - Aula 01 - Exercício
autor: ELVILSEY SOUZA PEREIRA

## Importando os restaurantes

 ```
    mongoimport --db be-mean --collection restaurantes --drop --file restaurantes.json
    connected to: 127.0.0.1
    2015-11-09T21:25:45.460-0200 dropping: be-mean.restaurantes
    2015-11-09T21:25:48.004-0200 		Progress: 5823100/11880944	49%
    2015-11-09T21:25:48.004-0200 			10800	3600/second
    2015-11-09T21:25:49.292-0200 check 9 25359
    2015-11-09T21:25:49.292-0200 imported 25359 objects
 ```

 ## Contando os restaurantes

  ```
    > use be-mean
    switched to db be-mean
    > db.restaurantes.find({}).count();
    25359
    >
   ```
