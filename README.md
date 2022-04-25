=================

bWAPP curso SQL Injection

* Instalação do MySQL

    - [Mysql](https://www.mysql.com/)

* Criar o usuário com as devidas permisões:

      CREATE  USER 'admin' IDENTIFIED  by 'root';
      GRANT ALL PRIVILEGES  ON *.* TO 'admin'@'%';
      FLUSH PRIVILEGES;
  
Se certificar de que as informações estão corretas no arquivo de configuração:

      /admin/settings.php
      
Navegar até até /localhost/bWAPP/install.php e clicar em 'install'.


