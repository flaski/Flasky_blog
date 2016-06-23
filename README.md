#Python +Flask搭建blog

##有几个坑，值得注意一下
### mail配置的时候 格式
export FLASKY_ADMIN='email_address'

##第九章，99页有个role_id要自己手动加

##部署到heroku上的坑
###一开始create的时候，输上的命令不管用了
heroku create appname --buildpack heroku/python
### 配置数据库：
书上的命令不适用了，应该是Heroku升级了。
创建数据库

heroku addons:create heroku-postgresql:hobby-dev


##参考资料
http://cocode.cc/t/flask-heroku/4253

http://cocode.cc/t/flasky-heroku/6589

http://cocode.cc/t/flask-heroku/5949