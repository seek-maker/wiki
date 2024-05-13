# 大陆源设置和中文输入法安装与使用

## 视频教程

<figure markdown>
<iframe width="640" height="390" src="//player.bilibili.com/player.html?aid=1404713470&bvid=BV1br421j7C7&cid=1543654415&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</figure>

!!! info "视频有画面，没有声音"
        请点击视频画面的右下角，把静音按钮关闭即可。


### 中国大陆源服务器的设置

``` bash
sudo cp /etc/apt/sources.list  /etc/apt/sources.list_backup 

sudo nano /etc/apt/sources.list 

#把官方网址改成国内源的网址
mirrors.aliyun.com

sudo apt-get update
```

### 中文输入法的安装

``` bash
sudo apt-get install fcitx fcitx-googlepinyin fcitx-module-cloudpinyin fcitx-sunpinyin 
```
