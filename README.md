Дипломный проект Яндекс практикум.

Предварительно должны быть созданы виртуальные машины, проект не предусматривает автоматическое создание машин.

Для деплоя склонировать репозиторий на свою машину, после чего выполнить команды из корня проекта:
1. ansible-playbook playbook.yaml --tags="install_packages"
2. ansible-playbook playbook.yaml --tags="configure_pg_master"
3. ansible-playbook playbook.yaml --tags="configure_pg_replica"
4. ansible-playbook playbook.yaml --tags="configure_mediawiki_01"
5. ansible-playbook playbook.yaml --tags="configure_mediawiki_02"
6. ansible-playbook playbook.yaml --tags="configure_nginx_lb"
7. ansible-playbook playbook.yaml --tags="configure_zbx_mon"
8. ansible-playbook playbook.yaml --tags="configure_ans_bkp"
