# ssh-generator
ssh自动连接脚本生成器

#### 此脚本主要为了方便linux环境下的运维工作，又不想装一个类似xshell的软件多此一举

#### 依赖：
    1. python3
    2. expect (ubuntu下安装 > sudo apt-get -y install expect)

#### 使用方法

    1. 首先创建ssh自动连接expect脚本: ssh-generator [hostname] [ip] [username] [password] [port]
    2. 然后创建打开连接shell: ssh-generator [hostname]
    
#### 如果您想同时打开多个ssh连接，那么可以使用相同的 [hostname] 创建连接脚本，当运行连接脚本时，将同时打开相同 [hostname] 的远程连接
