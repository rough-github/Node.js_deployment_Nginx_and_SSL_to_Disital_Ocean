Brad youtube "Node.js Deployment with Nginx, SSL"

Steps to deploy a Node.js app to Disital Ocean using PM2, NGINX as a reverse proxy and SSL from LstsEncrypt.

[`gist here`](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa1RIelFNcHpkaEN6UTVYREE0eS0zZ0JpNGxFZ3xBQ3Jtc0tta3VyR25LNnNXeUV5YS01bWlkWUxpMTdfcEw5bm9QQUN1dnFEMlpaRUNUQS12YS1DcnZFdGZNQmtrUVg2dTJ6S3ZBYVl0ZGJ5V2NMUUc2d1BvUThsRnFjampRR2RYS2NwM1J3WTdEUFFRQUZrZUdXdw&q=https%3A%2F%2Fgist.github.com%2Fbradtraversy%2Fcd90d1ed3c462fe3bddd11bf8953a896);


1. Sign in Disital Ocean
2. SSH to Disital Ocean
3. install Node.js, npm 
4. mkdir /app
5. git clone this app.
6. npm install
7. npm i -g pm2 (pm2 is Advanced, production process manager for Node.js)
8. pm2 commands.
9. ufw commands. (firewall) http, https
10. install NGINX
11. setup file (sudo nano /etc/nginx/sites-available/default)
12. sudo nginx -t (test)
13. Register and/or setup domain register (Namecheap)
14. Add SSL with LetsEncrypt