1. bash pre_get_data.sh 获取到mongodb数据文件
2. docker-compose run init_leanote_db 初始化 mongodb 的数据（如果指明的账号密码 leanote 会出现问题，可能是mongodb版本的原因，3.0没问题 ）
3. docker-compose up -d leanote 启动监听 9000端口
