部署方法：
五步即可完成部署：
1. 登录 Cloudflare： https://www.cloudflare.com 创建workers，复制update-workers的代码，然后部署

2. 新建一个名为CARD_ORDER的KV存储

3. 添加环境变量，用于设置后台管理密码。变量名为ADMIN_PASSWORD，值your_password换成你自己的密码

4. 将workers的CARD_ORDER变量与新建的KV存储绑定，用于存储书签

5. 添加域名
