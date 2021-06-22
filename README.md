KKBOX API小程式

Introduction:  
展現一個小程式能讓使用者隨時能連結到公開的KKBOX裡聽取自己想要聽的歌曲。  

Build process:  
首先要下載Pycharm https://www.jetbrains.com/pycharm/  
然後載入需要的package import requests  
                     from kkbox_developer_sdk.auth_flow import KKBOXOAuth  
之後到kkbox devoloper網站申請一個帳號 https://developer.kkbox.com/#/app  
   ->獲得 Client ID 及 Client Secret (這是之後要連結到帳號的東西)  
   ->取得access token  
   run 程式  
   
Details of the approach:  
  define get_charts()  
  define def get_charts_tracks(chart_id)  
  先自行叫get_charts()  
  讓使用者選擇id 再讓id->chart_id去抓取歌曲網址供使用者選擇  
Results:  
  ![image](https://user-images.githubusercontent.com/86285612/122882468-cf236a00-d36e-11eb-826d-450cfc461047.png)  
  ![image](https://user-images.githubusercontent.com/86285612/122882711-0b56ca80-d36f-11eb-8485-65d74aa7db60.png)  
  ![image](https://user-images.githubusercontent.com/86285612/122882879-33dec480-d36f-11eb-926c-ca783849b6d3.png)  


  

References:  
  https://developer.kkbox.com/#/  
  https://docs-zhtw.kkbox.codes/#overview  
  https://www.learncodewithmike.com/2020/02/python-kkbox-open-api.html  
   

<!--
**1073325/1073325** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
