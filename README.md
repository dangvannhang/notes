# Install-everything
Here is place that I will show the way how to install packages, libraries, framework

## 1.Install laravel
#### 1.1 Required:
+ Install nodejs
+ Install composer
#### 1.2 Way to install
+ composer create-project laravel/laravel my-laravel
#### 1.3 Run app
+ php artisan serve

## 2.Install vuejs
#### 2.2.1 Way to install 
+ npm install -g @vue/cli
+ vue create my-vue
#### 2.2.2 Way to install with template "webpack"
+ npm install --global vue-cli
+ vue init webpack my-vue
#### 2.3 Run app
+ npm run serve
+ npm run dev

## 3 Install vuejs in laravel
#### 3.1 Required:
+ install laravel first
#### 3.2 Way to install
+ composer require laravel/ui
+ php artisan ui vue
#### 3.3 Run app:
+ php artisan serve
+ npm install && npm run dev

## 4.Docker
#### 4.1 Required:
+ Your computer must be  windows 10 professional and Enterprise edition
+ Or you can follow https://www.itechtics.com/enable-hyper-v-windows-10-home/ to see the way to open Hyper-v for windows 10 home
#### 4.2 Way to install
+ When you setup docker, it will give you instruction to setup, if you get errors, you can search it on google
+ Your docker desktop must be running
#### 4.3 run app
+ docker-compose up -d --build
+ docker ps
+ docker exec -it <tencontainer> /bin/bash de log vo container
+ docker-compose down khi khong can dung, de tat cac service
+ 127.0.0.1:{port}
  
## 5. Install scss in vuejs
#### 5.2. Way to install
+ npm install -D sass-loader node-sass
+ npm install sass-loader sass webpack --save-dev

## 6. Install Less 
#### 6.1 Required
+ Installed Nodejs
#### 6.2 Way to install
+ npm install -g less
#### 6.3 Run Less
+ lessc style.less style.css

## 7. Install sass
#### 7.1 Required
+ Install Nodejs
#### 7.2 Way to install
+ npm install -g sass
#### 7.3 Run sass
+ sass style.sass style.css



