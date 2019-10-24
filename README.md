# cmslist
cms指纹识别,每一个cms的识别规则都是一个文件,存放在plugins目录下。目前采用的识别方式是:匹配header头信息、匹配的body信息 、
匹配ico image的md5值,访问指定的URL,访问不存在的URL去匹配报错信息.

目前已经收集的cms有:wordpress,discuz,drupal,ecshop,emlog,phpcms,phpwind,pigcms,qibosoft,thinkphp....后续会陆续添加cms识别规则

使用方法如图.



![image](https://user-images.githubusercontent.com/55778895/67477607-0539b380-f68d-11e9-825c-a2bd7f09e900.png)