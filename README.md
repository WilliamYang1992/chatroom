# chatroom
在线聊天室DEMO  

##### 基于Django+Vue+RabbitMQ构建  
##### 根据这篇博客进行练习 https://danidee10.github.io/2018/01/01/realtime-django-1.html  
### 运行指引  
1. clone项目后, 运行python manage.py migrate
2. 进入chatroom-frontend文件夹, 运行npm install  
3. 在chatroom-frontend文件夹路径中, 运行npm run dev运行webpack dev server  
4. 回到chatroom文件夹中, 运行python manage.py runserver开启Django test server
