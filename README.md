# docker-web
docker web 环境

首次运行容器/或者修改compose-compose.yml: 

	docker-compose up -d

启动容器:

	docker-compose start

启动指定容器:

	docker-compose start xxx //xxx为容器name或者id

查看运行容器状态: 

	docker ps

重启容器:

	docker-compose restart

重启指定容器:

	docker-compose restart xxx // xxx为容器name或者ID

停止容器:

	docker-compose stop

停止指定容器:

	docker-compose stop xxx // xxx为容器name或者id


yml配置文件volumes说明

将本地C:/phpStudy/PHPTutorial/WWW隐射到容器/var/www/html/中,并且设置rw权限

C:/phpStudy/PHPTutorial/WWW:/var/www/html/:rw
