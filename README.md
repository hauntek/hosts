# hosts  

## Note  
每日自动更新 github, docker 和 tinyMediaManager 的 IP 地址。  

hosts Url:   
Raw Url: ``` https://raw.githubusercontent.com/shidahuilang/hosts/main/hosts ```  
CDN Url: ``` https://gcore.jsdelivr.net/gh/shidahuilang/hosts@main/hosts ```  
CDN Url: ``` https://cdn.staticaly.com/gh/shidahuilang/hosts/main/hosts ```    ```(推荐)```  

## Used  
Windows/MacOS:  
```
推荐使用 SwitchHosts
```
![image](https://github.com/shidahuilang/hosts/raw/main/1.png)

Linux:
```
# 删除
sudo sed -i '/# ING Hosts Start/,/# ING Hosts End/d' /etc/hosts
# 添加
curl -s -L https://raw.githubusercontent.com/shidahuilang/hosts/main/hosts | sudo tee -a /etc/hosts
```
