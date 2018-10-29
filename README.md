# iOSAPPInstall

一共三个文件
1. 显示安装的网页 http: //xxx.com/index.html，存储在腾讯云；  
2. plist 文件，需要 https 链接，存储在 GitHub；  
3. ipa 文件，不需要 https，存储在腾讯云。  

plist 文件中图片链接不能为空，不然会安装失败，可以随便找个图片，下载完成后会替换为 app 图片。

### 快速安装
省略上面的第一步，直接在 Safari 浏览器地址栏粘贴链接
`itms-services://?action=download-manifest&url=https://example.com/xxx.plist`
回车就可以下载
plist 文件中的 ipa 文件存储在腾讯云。
