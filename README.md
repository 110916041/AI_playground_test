# AI_playground_test

利用上課所學到的AI Playground的操作方法，試著在影像辨識當中展現一些新花樣，並確認其便是結果

方法：

  1. 先透過市面上已存在的換臉程式，進行性別的轉換。

  2. 將一般未經過修改的圖像，透過AI_playground進行模型的訓練。

       ![image](https://github.com/110916041/AI_playground_test/blob/f8524a29e0f6534d1b6b1f4603f94ba2f5429df5/image/train.png)

  3. 將第一步驟的所更改的照片，放進步驟二所產生出的model進行性別的辨識，並與正常照片進行比較。

   ***有礙觀瞻 注意！！！***

  ![image](https://github.com/110916041/AI_playground_test/blob/f8524a29e0f6534d1b6b1f4603f94ba2f5429df5/image/test.png)
  ![image](https://github.com/110916041/AI_playground_test/blob/f8524a29e0f6534d1b6b1f4603f94ba2f5429df5/image/test_ori.png)

心得：

  1. 樣本圖內的其他物件可能會影響到判讀結果。

  2. 一張圖內若出現兩個同類型的訓練模型，可能會導致電腦判讀結果不合。

  3. 我們利用原圖和換臉之後的照片做測試，發現若是男生換臉成女生之後，電腦也真的會判斷是女生。
