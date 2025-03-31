https://disk.yandex.ru/d/OASXSecnwN2I6A


Новое....




curl -fsSL https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo gpg --dearmor -o /usr/share/keyrings/pgadmin-archive-keyring.gpg



echo "deb [signed-by=/usr/share/keyrings/pgadmin-archive-keyring.gpg] https://apt.postgresql.org/pub/repos/apt/ $(lsb_release -cs)-pgdg main" | sudo tee /etc/apt/sources.list.d/pgadmin.list



sudo rm -f /etc/apt/sources.list.d/pgadmin.list


curl -fsSL https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo gpg --dearmor -o /usr/share/keyrings/pgadmin-archive-keyring.gpg



echo "deb [signed-by=/usr/share/keyrings/pgadmin-archive-keyring.gpg] https://apt.postgresql.org/pub/repos/apt/ jammy-pgdg main" | sudo tee /etc/apt/sources.list.d/pgadmin.list



cat /etc/apt/sources.list.d/pgadmin.list


sudo rm -f /etc/apt/sources.list.d/pgadmin.list
curl -fsSL https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo gpg --dearmor -o /usr/share/keyrings/pgadmin-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/pgadmin-archive-keyring.gpg] https://apt.postgresql.org/pub/repos/apt/ jammy-pgdg main" | sudo tee /etc/apt/sources.list.d/pgadmin.list


apt-cache policy pgadmin4


