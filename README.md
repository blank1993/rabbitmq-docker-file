# rabbitmq-docker-file
rabbitmq插件版docker file

# 构建

docker build -t rabbitmq:3.8.0-management-delayed .


# 推送

docker login --username=385794624@qq.com registry.cn-shenzhen.aliyuncs.com

docker tag [imageId] registry.cn-shenzhen.aliyuncs.com/blank1993/rabbitmq:latest

docker push registry.cn-shenzhen.aliyuncs.com/blank1993/rabbitmq:latest
