# w_379
PHP微信固码免签监控系统源码+带搭建教程和APP
<br/></br>
[下载地址](https://www.uuid2.com/379.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>搭建教程：<p>
<p>Linux 服务器，安装好Nginx 1.16.0 mysql 5.6+ php 5.6 +<p>
<p>这套源码是客户花了6K从某站上面买的，搭建的话有一点难度

先去开启mysqli的配置参数先
APP工程文件和生成的APP都有的，自己反编译就好
先上传源码到服务器
可以直接拿去运营的
上传好了就解压到根目录

//数据库引擎
define('DB_ENGINE','MyISAM');
//数据库方式
define('DB_HOOK','mysqli');
//数据库地址
define('DB_HOST','127.0.0.1');
//数据库端口
define('DB_PORT','3306');
//用户名
define('DB_USER','wx');
//密码
define('DB_PWD','pS6XEkLzM4rKfeBL');
//数据库
define('DB_NAME','wx');

然后到etc目录db_config.php修改好自己的数据库信息，
修改好数据库，先去新建一个数据库。
现在去修改我们得数据库文件接着去导入数据库
然后去修改数据库引擎
default_storage_engine = InnoDB
找到这一段，修改成
default_storage_engine = MyISAM
然后重启mysql服务
然后去开启('DB_HOOK','mysqli');
mysqli数据库链接方式，稍等。
打开PHP得配置文件<p>
<p>;extension=php_mysqli.dll

把前面得符号去掉然后保存然后重启好
去设置防跨站把他关掉
后台地址:
域名 +/visa_admin.php
admin      26212155

注册账号之后要后台审核，也可以设置不用审核
上传好码，然后打包好监听就可以了，到账了会自动回调
去woceshi这个文件夹改好你自己得
然后再看看demo
都OK得
APP就是这样，要测试得话需要去配置好数据库先，这里就先不演示了，然后APP的话反编译或者修改的话修改这两个文件就可以了
LoginActivity.smali         Main.smali

注：
GatewayWorker\Applications\BusinessWork\Config\Db.php
etc\db_config.php
GatewayWorker\Applications\real\Config\Db.php
\pay\etc\db_config.php
 <p>
<p>还需要修改这四个地方得数据库配置文件才可以支付<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202105/899e248301.jpg" alt="PHP微信固码免签监控系统源码+带搭建教程和APP"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/899e248256.jpg" alt="PHP微信固码免签监控系统源码+带搭建教程和APP"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/adf4874163.jpg" alt="PHP微信固码免签监控系统源码+带搭建教程和APP"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/adf4874269.jpg" alt="PHP微信固码免签监控系统源码+带搭建教程和APP"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/adf4874252.jpg" alt="PHP微信固码免签监控系统源码+带搭建教程和APP"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/aaa7809334.jpg" alt="PHP微信固码免签监控系统源码+带搭建教程和APP"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/aaa7809354.jpg" alt="PHP微信固码免签监控系统源码+带搭建教程和APP">
