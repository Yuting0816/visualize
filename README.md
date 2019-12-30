# 群眾募資-Kickstarter募資平台
### kickstarter眾籌環境介紹
Kickstarter 提供了媒合「有創意、有想法，但缺乏資金」與「有資金，也願意捐款支持好創意」的平台。
專案類型包括時尚、遊戲、食品、影視等。
因募資平台的特性，Kickstarter規定人們不能透過投資專案來賺錢，也就是說被投資方不可能回報金錢。
在Kickstarter建立專案，需選擇最後期限和最低資金為目標。若專案沒有達到目標，專案所有者將一無所獲。
例如：如果一個專案的目標是500美元，即使它募集到了499美元，該專案也不會成功。

### kaggle資料集
 >資料來源
 
 [Kickstarter Projects](https://www.kaggle.com/kemical/kickstarter-projects#ks-projects-201801.csv)

> 資料欄位

+ ID -專案ID
+ Name -專案名稱
+ Category -分類
+ Main_category -專案類別
+ Currency -幣別
+ Deadline -最後期限
+ Goal -專案目標
+ Launched -專案上傳時間
+ Pledged -募集總額
+ Status -最終狀態
+ Backers -支持者
+ Country -國家

![image](https://github.com/Yuting0816/visualize/blob/master/%E5%9C%96%E7%89%873.png)

### 分析
#### 分析1:專案類型與募資結果的關聯
##### 說明
專案類型分為15類:影視、音樂、出版、遊戲、科技、設計、藝術、食物、時尚、劇場、漫畫、攝影、工藝、新聞和舞蹈。

募資結果分為2種:成功及不成功，不成功包含失敗、取消、未知等等。

##### 各專案類型比例
![image](https://github.com/Yuting0816/visualize/blob/master/1577692731831.jpg)

1. 影視 專案數量63585

2. 音樂 專案數量51917

3. 出版 專案數量39874

4. 遊戲 專案數量35230

5. 科技 專案數量32569

6. 設計 專案數量30070

7. 藝術 專案數量28153

8. 食物 專案數量24601

9. 時尚 專案數量22816

10. 劇場 專案數量10913

11. 漫畫 專案數量10819

12. 攝影 專案數量10779

13. 工藝 專案數量8809

14. 新聞 專案數量4755

15. 舞蹈 專案數量3767

##### 各專案類型募資成功率
![image](https://github.com/Yuting0816/visualize/blob/master/1577608076589.jpg)

1. 舞蹈 專案成功數2338 成功率62.07%

2. 劇場 專案成功數6534 成功率59.87%

3. 漫畫 專案成功數5842 成功率54.00%

4. 音樂 專案成功數24196 成功率46.61%

5. 藝術 專案成功數11510 成功率40.88%

6. 影視 專案成功數23623 成功率37.15%

7. 遊戲 專案成功數12518 成功率35.53%

8. 設計 專案成功數10550 成功率35.08%

9. 出版 專案成功數12300  成功率30.85%

10. 攝影 專案成功數3305 成功率30.66%

11. 食物 專案成功數6085 成功率24.73%

12. 時尚 專案成功數5593 成功率24.51%

13. 工藝 專案成功數2115 成功率24.01%

14. 新聞 專案成功數1012 成功率21.28%

15. 科技 專案成功數6434 成功率19.75%

##### 分析結果
1. 並不是募資成功率越高的專案類型投稿的人數就越多。
2. 募資成功的專案大部分目標金額較低。

#### 分析2:各國的募資偏好
##### 說明
資料集中的國家包含美國(US)、奧地利(AT)、澳大利亞(AU)、比利時(BE)、加拿大(CA)、瑞士(CH)、德國(DE)、丹麥(DK)、西班牙(ES)、法國(FR)、英國(GB)、香港(HK)、愛爾蘭(IE)、義大利(IT)、日本(JP)、盧森堡(LU)、墨西哥(MX)、荷蘭(NL)、挪威(NO)、紐西蘭(NZ)、瑞典(SE)、新加坡(SG)。

##### 各國投稿數比例
![image](https://github.com/Yuting0816/visualize/blob/master/%E4%B8%8B%E8%BC%89.png)

##### 各國投稿數TOP3的專案類型
1. 美國
+ 影視 17.7436%
+ 音樂 14.7756%
+ 出版 10.8419%

2. 奧地利
+ 科技 21.7755%
+ 設計 13.7353%
+ 遊戲 11.5578%

3. 澳大利亞
+ 科技 15.4994%
+ 遊戲 12.2592%
+ 影視 11.9913%

4. 比利時
+ 科技 15.8833%
+ 遊戲 15.8833%
+ 設計 11.5073%

5. 加拿大
+ 科技 13.0388%
+ 遊戲 12.7677%
+ 影視 11.5411%

6. 瑞士
+ 科技 27.0696%
+ 設計 17.3456%
+ 遊戲 8.5414%
+ 時尚 8.5414%

7. 德國
+ 科技 20.1151%
+ 遊戲 15.9434%
+ 設計 13.4980%

8. 丹麥
+ 科技 16.9811%
+ 設計 15.7233%
+ 影視 10.0629%


9. 西班牙
+ 遊戲 22.2759%
+ 科技 17.9701%
+ 設計 9.5782%


10. 法國
+ 科技 21.9462%
+ 遊戲 17.0806%
+ 設計 10.3437%


11. 英國
+ 影視 17.1715%
+ 遊戲 11.9149%
+ 出版 9.7143%

12. 香港
+ 設計 38.1877%
+ 科技 25.4045%
+ 遊戲 12.2977%

13. 愛爾蘭
+ 科技 15.1665%
+ 出版 13.1936%
+ 影視 11.2207%

14. 義大利
+ 科技 20.0834%
+ 遊戲 13.6206%
+ 設計 13.2731%

15. 日本
+ 遊戲 25.0000%
+ 時尚 20.0000%
+ 設計 20.0000%

16. 盧森堡
+ 科技 16.1290%
+ 出版 14.5161%
+ 攝影 11.2903%

17. 墨西哥
+ 影視 18.0936%
+ 科技 12.8995%
+ 音樂 11.8151%

18. 荷蘭
+ 科技 20.7462%
+ 遊戲 14.3654%
+ 設計 12.0642%

19. 挪威
+ 科技 16.5254%
+ 遊戲 12.0056%
+ 音樂 11.5819%

20. 紐西蘭
+ 科技 14.4437%
+ 影視 13.0615%
+ 遊戲 12.6469%

21. 瑞典

+ 遊戲 15.6517%
+ 出版 11.6107%
+ 影視 11.4969%

22. 新加坡
+ 設計 25.2252%
+ 時尚 18.7387%
+ 科技 14.5946%


![image](https://github.com/Yuting0816/visualize/blob/master/%E5%90%84%E5%9C%8B%E5%AE%B6%E7%9A%84%E5%8B%9F%E8%B3%87%E5%81%8F%E5%A5%BD.png)

##### 分析結果
1. 大部分的國家專案數前三名的分類都是科技、設計、遊戲。
2. 美國專案數量遠大於其他國家，故美國的募資偏好會對專案類型的分布造成極大影響。
3. 部分國家專案數量較少，所以無法明確得知該國偏好。

### Infographics資訊圖表
![image](https://github.com/Yuting0816/visualize/blob/master/Kickstarter%20%E5%8B%9F%E8%B3%87%E5%B9%B3%E5%8F%B0.png)

