## PWDM
Репозиторий используется как подключаемый модуль серверной и клиентской
частями менеджера паролей: [pwdm_server](https://github.com/BillyBones007/pwdm_server),
[pwdm_client](https://github.com/BillyBones007/pwdm_client).


### Файл /proto/pwdm.proto
#### Взаимодействие сервиса регистрации/аутентификации/авторизации
[1]: /assets/auth_proto.png
![AuthService][1]

#### Взаимодействие с сервисом загрузки и получения данных
[3]: /assets/insert_proto.png
[4]: /assets/select_proto.png
![GiveTakeService][3]
![GiveTakeService][4]

#### Взаимодействие с сервисом получения информации по загруженным данным
[5]: /assets/show_proto.png
![ShowInfoService][5]


#### Взаимодействие с сервисом удаления данных с сервера
[2]: /assets/delete_proto.png
![DeleteService][2]