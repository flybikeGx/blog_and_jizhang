##blog-and-jizhang


个人博客(基于zinnia)和记账工具


##blog-and-jizhang有哪些功能？


* blog基于django-blog-zinnia
* 整合了highlightjs代码高亮
* 整合了多说评论
* 便捷的记账分类管理
* 记账统计和查找
* 记账的导入导出


##安装
* 安装django>=1.8.3
* 安装django-blog-zinnia
* 安装django-app-namespace-template-loader
* 安装zinnia-theme-bootstrap
* 安装zinnia-wysiwyg-wymeditor
* 设置settings_local.py，配置数据库，refresh.db.sh
* 设置upload路径权限
* 设置属性chown  -R nginx:nginx directoryname
* python manage.py migrate
* python manage.py runserver localhost:8080


##有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流


* 邮件(heibanke~aliyun.com, 把~换成@)