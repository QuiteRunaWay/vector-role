Role Name
=========

Роль устанавливает на ваш хост Vector

Requirements
------------

Особых требований не предъявляется.

Role Variables
--------------

По умолчанию ставить vector версии ```0.21.2```. При необходимости установить другую версию, Вам необходимо переопределить переменную ```vector_version``` в разделе `vars`.

По умолчанию, данная роль ставит vector и собирает логи в корневой папки пользователя `vagrant`. В случае, если Вам необходимо собирать данные от другого пользователя, Вам необходимо переписать путь в конфиге ```vector```, который расположен в `defaults`.


Dependencies
------------

Требования по зависимостям не предъявляются.

Example Playbook
----------------

hosts: your_hostname
 roles: 
   - vector-role

License
-------
BSD