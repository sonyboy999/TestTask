Здравствуйте.

К сожалению я не смог нормально обработать json файл  по этой ссылке 
https://www.cbr-xml-daily.ru/daily_json.js в Android studio т.к он слишком не удобный, если бы
он был более валидным т.е его объекты находились бы в массиве, то проевсти его парсинг и впоследсвтии выести его 
как список в ListView не составило бы труда.

Но зато я смог десериализовать json файл в самом java путём использования GSON, и вытащить 
все объекты из этого файла.

В папке AllValutes находятся все валюты со всеми свойтсвами.
в классе ValuteParser я произвёл десериализацию json файла.