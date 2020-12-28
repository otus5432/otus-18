# otus-18
otus-18 -  web server configs from lesson 18

1. Copy repository to web-server

```
git clone https://github.com/otus5432/otus-18.git

```
2. Change default ip 127.0.0.1 in configs if needed

3. Make apache Listen on ports 8080,8081,8082

```
Listen 8080
Listen 8081
Listen 8082

```

4. Copy Virtualhost configs for apache backend from apache directory

5. Edit default nginx conf add lines from nginx/nginx.conf

6. Copy html files from files/ folder

```
cp -r ./otus18/files/var/www/ /var/www

```
