机密变量配置路径
 
仓库后台 →  Settings  →  Secrets and variables  →  Actions ，点击新建仓库机密，依次添加以下变量
 
一、核心必填变量
 
1. SUB_URL
 
变量释义：订阅链接
 
2. USERS_JSON
 
变量释义：账号配置信息（JSON 格式）
格式化工具：JSON在线格式化
填写格式参考
 
单账号格式
 
json
  

    {
        "username": "邮箱",
        "password": "密码",
        "serverId": "服务器ID"
    }

 
 
多账号格式
 
json
  

    {
        "username": "邮箱",
        "password": "密码",
        "serverId": "服务器ID"
    },
    {
        "username": "邮箱",
        "password": "密码",
        "serverId": "服务器ID"
    }

 
 
3. TG_BOT_TOKEN
 
变量释义：Telegram 机器人 Token
 
4. TG_CHAT_ID
 
变量释义：Telegram 消息接收ID（个人ID/频道ID）
 
二、可选配置变量
 
TG_THREAD_ID
 
变量释义：Telegram 话题ID
使用场景：如需将消息发送至群组内特定话题时填写，无需求可留空
