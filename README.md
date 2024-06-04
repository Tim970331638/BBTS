# Electric-Code

开发电力数据处理项目

项目介绍：集成一套有关风力发电的数据处理可视化程序。包含数据预处理，缺失值检测，错误数据检测等。这是一个长期的项目，要知道，拉一坨屎和把一坨屎变成蛋糕所需的时间是完全不一样的。

运行：
进入到局部文件（运行命令 cd DjangoProject）后，输入指令 python manage.py runserver 正常启动Django后 进入 127.0.0.1:8000/csvEditor

常见报错：
运行服务器命令 python manage.py runserver 8000 时，出现错误“You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.Run 'python manage.py migrate' to apply them.” 可用 python manage.py migrate 命令迁移数据解决
