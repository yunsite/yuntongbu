微博云同步 1.0  http://t.cn/zWZ4pCp
<br />
**说明：**
  * 将腾讯微博与新浪微博双向同步
  * 仅将腾讯微博同步新浪微博
  * 仅将新浪微博同步腾讯微博
  * 发微博时，只要在微博信息前加 - (中划线或减号)，这样该微博信息将不会被自动同步到另一微博。


**准备工作：**
  * 申请Sina App Engine(简称SAE) http://sae.sina.com.cn/?m=front
> > 登录成功后开启 服务管理中的 Memcache 、Cron 、 FetchURL
  * 申请 新浪微博开放平台应用 http://open.weibo.com/development
> > 成功后您将获得新浪微博的 App Key 、 App Secret
  * 申请 腾讯微博开放平台应用 http://dev.open.t.qq.com/developer/
> > 成功后您将获得腾讯微博的 App Key 、 App Secret


**安装说明：**
<ol>
<li>下载 <a href='https://code.google.com/p/yuntongbu/downloads/list'>源文件</a> 并解压 或者 <a href='https://yuntongbu.googlecode.com/svn/trunk/'>SVN</a>  到本地</li>
<li>打开config.yaml文件修改‘accesskey’值 （SAE 应用信息->汇总信息 里查看） </li>
<li>打开config.php文件修改新浪微博app key、腾讯微博app key 及其它信息 </li>
<li>将修改后的文件一起上传到SAE平台即可 (上传地址： 应用管理->代码管理->上传代码包)</li>
<ol>

Koole同学写的教程： <a href='http://koole.in/2012/07/04/微博云同步/'>http://koole.in/2012/07/04/微博云同步/</a>