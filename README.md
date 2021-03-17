# Bilibili_User_info.py 和Main_Run.py  
都是独立的模块，可以单独运行，没有任何依赖关系
Bilibili_User_info.py  
可以获得 B站进入直播间用户信息，发送弹幕的内容，用户在这个直播间的等级，用户发送的小礼物信息，用户头像等  
Main_Run.py   
只能发送弹幕信息  
## Bilibili_live_Danmaku
Get Bilibili live Danmaku and send message for TCP  
[env]  
python3.7   
windows  

国内：  
打开cmd命令行工具  
pip install --upgrade pip    
pip install -i https://pypi.douban.com/simple/ -r requirestment.txt  

说明  ：    
1，通过bilibili客户端，进入直播房间，点击主播获取主播房间号    
2，修改配置文件里面id 后面的房间号  
3，运行python文件  

How to start :  
1,cmd  
2,pip install --upgrade pip  
3,use cd +'your path' to enter your file dir  
3,pip install -i -r requirestment.txt
4,open config.ini ,and set id='room_id'  
5,run main_run and default ip=127.0.0.1,port=9950



