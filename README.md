# docker-vm

个人配置

1. 主机名：`master`

2. 账号密码： 

   mysql：

   - `root`

   - `mongs123`

   redis：

   - `mongs123`

   elastic：

   - `elastic`
   - `mongs123`

   rabbitmq:

   - `rabbit`
   - `mongs123`

   mongodb:

   - `mongo`
   - `mongs123`



部署方式

1. elk

```shell
docker-compose -f docker-elk/docker-compose.yml up -d
```

2. mysql，redis，rabbitmq，mongodb

```shell
docker-compose -f docker-kit/docker-compose.yml up -d
```

