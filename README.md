Role lighthouse-role
=========

Эта роль устанавливает и настраивает lighthouse на целевых хостах, обеспечивая автоматизацию процесса настройки и управления производительностью веб-приложений.

Requirements
------------

- ​​Ansible 2.10.8

Role Variables
--------------

В роли могут быть определены переменные, которые можно настраивать. Все переменные, которые могут быть переопределены, хранятся в файле defaults/main.yml

Dependencies
------------

Для корректной работы инструмента требуется стабильное интернет-соединение, так как он анализирует загружаемые ресурсы сайта.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: lighthouse
  become: true
  roles:
    - lighthouse-role


License
-------

BSD

Author Information
------------------

Эта роль была создана в 2024 году [Evgenii](mailto:your.email@example.com)
