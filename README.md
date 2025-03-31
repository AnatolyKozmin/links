https://disk.yandex.ru/d/OASXSecnwN2I6A


Новое....




curl -fsSL https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo gpg --dearmor -o /usr/share/keyrings/pgadmin-archive-keyring.gpg



echo "deb [signed-by=/usr/share/keyrings/pgadmin-archive-keyring.gpg] https://apt.postgresql.org/pub/repos/apt/ $(lsb_release -cs)-pgdg main" | sudo tee /etc/apt/sources.list.d/pgadmin.list



sudo rm -f /etc/apt/sources.list.d/pgadmin.list


curl -fsSL https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo gpg --dearmor -o /usr/share/keyrings/pgadmin-archive-keyring.gpg



echo "deb [signed-by=/usr/share/keyrings/pgadmin-archive-keyring.gpg] https://apt.postgresql.org/pub/repos/apt/ jammy-pgdg main" | sudo tee /etc/apt/sources.list.d/pgadmin.list


user@user-Standard-PC-Q35-ICH9-2009:~$ sudo apt install pgadmin4 -y
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Package pgadmin4 is not available, but is referred to by another package.
This may mean that the package is missing, has been obsoleted, or
is only available from another source

E: Package 'pgadmin4' has no installation candidate
