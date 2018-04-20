# JWT-CodeIgniter
JSON Web Token native library for PHP

## Introduction
`jwt_helper.php` 文件为封装好的一个类，可直接使用，使用方法如下：

配置 `application/config/autoload.php` 中，修改 `$autoload['helper'] = array()` 为 `$autoload['helper'] = array('jwt');`


调用方法：
- `jwt_helper::validate(<token>)` 验证token
- `jwt_helper::decode(<token>)` 解码token
- `jwt_helper::create(<userId>)` 创建token userId 为你要存放的字段

## How to Use ?
1. 复制 `helpers`、`libraries` 里面的文件到相应的目录
2. 按照说明引入

## Donate
如果我的付出能够帮助到你，我也乐于接受你的帮助，小小的赞赏是我们持续进步的动力。

![支付宝支付](http://o99llmab0.bkt.clouddn.com/alipay.png)
![微信支付](http://o99llmab0.bkt.clouddn.com/wechat.png)

## Thanks
JWT for CodeIgniter: https://github.com/b3457m0d3/JWT-CodeIgniter


