# RIADD-2021
RIADD-2021，參賽國家共40國，參賽人數共1185人，共50隊，很榮幸本團隊於該國際競賽獲得第五名。RIADD挑戰是由IEEE ISBI 2021所發起的世界級比賽，其目標為評估使用視網膜眼底圖像對不同眼病進行自動分類的算法，並且挑戰共分成2大任務。任務1為疾病篩查(Disease Screening)，對影像做 2 元分類，判斷是否有眼疾。該任務的困難點是測試集資料是不同儀器所拍攝出的眼底鏡影像，因此模型的泛化能力非常重要。本團隊模型選用EfficientNet B3-B7，前處理使用CLAHE和Green Channel，這兩種前處理被證明在眼底鏡影像上能有效提升正確率的方法。任務 2 為疾病分類(Disease Classification)，對影像做多標籤分類，判斷單一影像中有45種病徵有哪幾種符合。本團隊模型選用於各項分類任務皆表現優良的EfficientNet B3-B7和於多標籤分類任務中表現優良的TResNet，最後將多個模型的結果做 Soft voting以提升模型的泛化能力，加強於測試集的表現。Loss選用對多標籤分類任務特化的Asymmetric Loss。最後於驗證集拿到85.78%的綜合成績獲得第7名挺進決賽，並於最終測試集拿到85.72%的綜合成績獲得第5名。


![image](https://github.com/Kevin7720/ISBI2021-RIADD-2021/blob/master/certificate%20of%20merit%20%26%20speech%20of%20ppt/certificate%20of%20merit.png)
