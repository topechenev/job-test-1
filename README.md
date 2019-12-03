1. Склонить репо
2. `cd <local-repo-location>`
3. `docker-compose build`
4. `docker-compose up`
  
Поднимется 3 контейнера: 
1. webapp [http://\<your-ip>:80/]  
/enable - включить приложение  
/disable - отключить приложение  
/status - статус on/off ok/overloaded  
/metrics - метрики для prometheus  
/<any-path> - записывает для каждого клиента путь запроса/время и выводит это  
  
2. prometheus - снимает метрики приложения  
3. grafana - [http://\<your-ip:3000/] admin/secret  
    Смотреть дашборд WEB-APP
