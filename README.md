# hosts  

## Note  
每日自动更新 github, docker 和 tinyMediaManager 的 IP 地址。  

hosts Url:   
Raw Url: ``` https://raw.githubusercontent.com/hauntek/hosts/main/hosts ```  

## Used  
Windows/MacOS:  
```
推荐使用 SwitchHosts
```
![image](https://github.com/hauntek/hosts/raw/main/1.png)

Linux:
```
# 删除
sudo sed -i '/# ING Hosts Start/,/# ING Hosts End/d' /etc/hosts
# 添加
curl -s -L https://raw.githubusercontent.com/hauntek/hosts/main/hosts | sudo tee -a /etc/hosts
```
