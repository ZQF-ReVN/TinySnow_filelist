# TinySnow_filelist
用于GarBro，缺少几个文件名（游戏未使用，恢复文件名较麻烦）  
通过替换RhapsodyCrypt的两个密钥，并修过.\GameData\kirikiri_rhapsody.lst  
https://github.com/morkt/GARbro/blob/master/ArcFormats/KiriKiri/CryptAlgorithms.cs#L1122 

搜索密钥参见：https://github.com/YeLikERs/NvlKR2Extract/tree/main/HowToFindKey  
TinySnow 可从 plugin 目录中的 wump3.dll 可以获得两密钥  
分别为：   
LittleEndian.Pack(0xAD1AAEFBU, array, 4);  
LittleEndian.Pack(0x46258BE4U, array, 8);  
        
文件名可以直接dump如下地址，此处将dump得到所有引擎解密文件尝试路径。  
由于Garbro可以自行识别正确文件名，即多余/错误文件名不影响。
![image](https://github.com/Dir-A/TinySnow_filelist/blob/main/QQ%E6%88%AA%E5%9B%BE20220513154737.png)
