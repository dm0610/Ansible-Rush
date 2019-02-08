Удаление Vagrant-машины:
vagrant -f destroy
Если нет других хостов, то просто включить явную запись с именем localhost:
localhost ansible_connection=local

при использовании словарей YAML меняется способ доступа к переменным
{{db_primary_host}} vs {{db.primary.host}}