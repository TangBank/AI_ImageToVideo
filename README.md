# 图生视频
## 1.思路流程
ChatGPT4o出来以后，将实景图片风格转化为动画风格已经变得非常容易。只需要一句话就可以将其变成宫崎骏风格。基于这个思路，将真人视频宫崎骏化应该变得可行。
操作思路：![image](https://github.com/user-attachments/assets/b39d4390-2b39-41d0-9f3e-3c2338bdde88)


## 2.实际效果
我截取了《甄嬛传》中甄嬛经典的哭戏片段，

https://github.com/user-attachments/assets/fd8b0a97-c619-47cb-9971-d7d6e5cd71c1

第一帧如下：![image](https://github.com/user-attachments/assets/44d186b2-21c8-43ca-a458-a3ce2775c84b)
宫崎骏效果如下：![image](https://github.com/user-attachments/assets/0a1e271e-fe5e-4c32-b8ad-7a5766d5aeee)
效果方面没得说，质量上乘。
## 3.遇到问题
1.GPT4o有限制：
如果每次提示词一样的话，大概10张以后就会告知平台限制：
![image](https://github.com/user-attachments/assets/481b16dd-a9af-4abb-8062-5a435f0061f5)

解决思路：

（1）每次更换不同的提示词，准备两套提示词，更替交换即可绕过平台限制

（2）用Sora没有限制
## 4.根据图片生成视频
我先将这场哭戏拆分了7个分镜头，并对每个分镜头写了剧本分镜：
![image](https://github.com/user-attachments/assets/f6139c5d-34de-4ae2-b4ad-747a1f982d5a)
然后用Sora和可灵分别生成第一幕的视频，效果如下：


https://github.com/user-attachments/assets/b017ed58-d8b5-4bb1-9c51-62d233a900e6

## 5.配音
因为是二次创作，如果有原生配音是最好。调研了几个市面上的声音克隆AI有：
* https://anyvoice.net/zh
* https://noiz.ai/landing
* F5-TTS








