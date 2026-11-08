# Slide 12 — Seven Components of the Chatbot Workflow

[回目錄](../README.md) · [發音指南](../pronunciation-guide.md)

## 這頁在說什麼

七個組件如何完成一次問答。

## 先練這一句（新增重點句，不取代完整講稿）

Let us follow one message through the system.

## 英文完整講稿

This diagram shows seven parts of a chatbot service. Let us follow one message from left to right.

The patient sends a question through LINE. A webhook carries the message to the system. You can think of the webhook as the connection that passes the message along.

The next part checks what the patient is asking. Then the search finds useful medical information. The knowledge layer helps organize it. The writing step turns it into a reply. Monitoring covers the whole process.

Consider this message: “I ate too much at dinner. My glucose is 11.2. Should I take more insulin?” First, we must check the unit. Second, this is a dose question. The word “dinner” does not make it a simple food-education question.

The system needs to send it to the right care process. It should not freely invent a dose. Also, old chat messages are not a current prescription.

Each part needs a clear job and a plan for errors. If the final answer is wrong, we should be able to find where the problem started. A good service depends on the whole process, not just the language model.

[Look at the slide and discuss]
Please take twenty seconds to look at the slide again. At which step should this insulin-dose question reach the care team?
[Pause for 40–70 seconds. Invite one answer, or give a short example from your own work.]

[Next slide]
Let us move to the next slide and look at the next part of the topic.

## 本頁發音重點

| 字詞 | 類型 | 練習提示 |
| --- | --- | --- |
| glucose | L | /l/；gl- 接起來，不在 g 與 l 中間加母音。 |
| right | R / 尾音 | /raɪt/：R 不碰齒齦，最後 /t/ 收住，不加母音。 |
| plan | A | /plæn/：A 是 /æ/，嘴張開，舌頭靠前；不是 plane。 |
| patient | A / 尾音 | /ˈpeɪʃənt/：A 是 /eɪ/ 滑動音；最後 /nt/ 收住。 |
| clear | L / R | cl- 的 L 舌尖接觸齒齦；美式字尾 R 舌頭不接觸。 |
| make | A / 尾音 | /meɪk/：A 是 /eɪ/；最後 /k/ 收住，不多加母音。 |

## 更清楚的表達方式

- 介紹畫面：This slide shows…
- 說明主要意思：The main point is…
- 提醒限制：This does not prove…
- 每次說一個重點；數字之後停一下，保留原稿的研究限制。

## 中文對照講稿

講述安排：約 3–5 分鐘，含圖表解說與 60–90 秒互動。中英文擇一講述。

要把這個原則變成日常服務，需要清楚的元件分工。請沿著圖由左至右看：LINE 接收提問，webhook 傳遞訊息並保留必要上下文，理解模組辨認意圖與範圍，RAG 找資料，LLM Wiki 整理知識，生成模組形成回覆。上方的維運監控涵蓋整條流程。
原稿用一個很實際的例子：「晚餐吃多了，血糖 11.2，需要加打胰島素嗎？」首先要確認單位，不能把 mmol/L 與 mg/dL 混用；其次，這是劑量問題，應走專業評估路徑，不能只因提到晚餐就歸入一般飲食衛教。對話記憶可以補充背景，但不是最新處方的替代品。
這套架構的價值，是讓我們知道哪一步判錯、哪個來源不足，以及何時需要人工介入。反應速度與同時服務人數要實測，不能從架構圖推論。每個元件都有明確的輸入、輸出與失敗處理，才能讓看起來簡單的一則訊息，背後有可檢查的照護流程。

【延伸說明】
系統測試可以刻意放入不完整問題、錯別字、超出範圍的問題，以及需要人工協助的訊息。觀察的不只是最後回答，還包括系統是否選對路徑。這樣才能把看不見的流程錯誤找出來，而不只是修飾回覆文字。

【看圖與討論】
請大家先花約二十秒回看這一頁，找出最支持主要訊息的部分。接著思考：這七個環節中，哪一個失敗最容易在最後的回答中被隱藏？
【停頓與互動 40–70 秒】邀請一位聽眾回答，或由講者以自己的門診／教學經驗回應。將答案連回本頁的資料與限制，不另推定未提供的個案結果。

【轉場】
接下來我們看「From Guidelines to Structured Knowledge」，把這一頁的重點放到下一個情境。
