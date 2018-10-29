# iOSAPPInstall

一共三个文件
1. 显示安装的网页 http: //xxx.com/index.html，存储在七牛；  
2. plist 文件，需要 https 链接，存储在 GitHub；  
3. ipa 文件，不需要 https，存储在七牛。  

plist 文件中图片链接不能为空，不然会安装失败，可以随便找个图片，下载完成后会替换为 app 图片。
