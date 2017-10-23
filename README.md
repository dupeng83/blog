# 博客 网站

这是跟随PACKT出版的书 [Django by Example](http://djangobyexample.com/) 所做的博客网站

运行 `git clone https://github.com/dupeng83/blog` 克隆以后运行下列命令:

`cd blog`

`virtualenv my_env`

`source my_env/bin/activate`

`pip install Django==1.11.2`

`pip install pytz`

`pip install django-taggit==0.22.1`

`pip install Markdown==2.6.9`

`python manage.py migrate`

`python manage.py runserver`

网站可以在后台添加博客，在前台显示

每条博客下面都有一个“分享这篇文章”的链接，点击之后用户输入一个邮箱地址，可以把这篇博客作为邮件发送给这个邮箱

此外还有添加评论的功能
