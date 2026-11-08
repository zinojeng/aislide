# Slide 09 — Medical Chatbot Architecture

[回目錄](../README.md) · [發音指南](../pronunciation-guide.md)

## 這頁在說什麼

從病人提問連接到醫學來源的架構。

## 先練這一句（新增重點句，不取代完整講稿）

The system finds useful information before it writes an answer.

## 英文完整講稿

This picture shows how a medical chatbot can connect a patient question with medical sources. Start at the center, with the LINE user.

The first task is to understand the question. The next task is to find useful information. The system then prepares an answer, with a way for the care team to check it.

For example, a pregnant patient asks, “Can I drink this sugar-free drink?” The words “sugar-free” are not enough. We need the ingredients and the pregnancy context. The system should find guidance that fits that question.

The LLM Wiki is a way to organize medical information and common questions. It should still point back to the original source. A summary is useful, but it does not replace the evidence behind it.

Human review also needs a real process. Someone must know when to check an answer and what to do if there is a problem.

The circles in this picture show planned roles. They do not prove that every answer will be correct. If the question asks for an insulin dose, or if key details are missing, the system needs a clear route back to the care team.

[Look at the slide and discuss]
Please take twenty seconds to look at the slide again. Who should check an answer when the system is unsure?
[Pause for 40–70 seconds. Invite one answer, or give a short example from your own work.]

[Next slide]
Let us move to the next slide and look at the next part of the topic.

## 本頁發音重點

| 字詞 | 類型 | 練習提示 |
| --- | --- | --- |
| clear | L / R | cl- 的 L 舌尖接觸齒齦；美式字尾 R 舌頭不接觸。 |
| review | R | /r/ 舌頭不碰齒齦；重音在 view。 |
| patient | A / 尾音 | /ˈpeɪʃənt/：A 是 /eɪ/ 滑動音；最後 /nt/ 收住。 |
| information | 重音 / 尾音 | 重音在 -MA- /meɪ/，末尾 /ʃən/；不要每節一樣重。 |
| check | 尾音 | 最後 /k/ 要有收住的動作，不加一個「可」。 |
| insulin | L | 中間 /l/ 保留；重音在 IN-。 |

## 更清楚的表達方式

- 介紹畫面：This slide shows…
- 說明主要意思：The main point is…
- 提醒限制：This does not prove…
- 每次說一個重點；數字之後停一下，保留原稿的研究限制。

## 中文對照講稿

講述安排：約 3–5 分鐘，含圖表解說與 60–90 秒互動。中英文擇一講述。

前一頁看到患者的需要，這一頁則回答：資訊應該如何進入醫療對話？請從中央的 LINE 使用者往外看。系統先理解問題，再連結到知識層與醫學指引，並保留人工驗證。這些層次的目的，是讓每個回答都能說明根據與適用範圍。
例如孕婦問「這種代糖飲料能不能喝」，理解層要辨認這是飲食與孕期情境，還要確認成分，而不是看到「無糖」就直接回答。檢索層找適當來源，知識層協助組織內容，最後把結論改寫為患者能理解的說明。下一張會展示對話範例。
這裡要特別分清知識組織與證據來源。LLM Wiki 可以整合常見問題，但衍生摘要仍應連回原始指引；人工覆核也需要有負責人與實際流程。圖中的圓圈不是效果保證，而是要落實的責任分工。當資料不足、問題涉及劑量或超出服務範圍時，系統應能清楚停下來，交回照護團隊。

【延伸說明】
可以用一個高血糖問題來走一次架構：先確認病人在問知識還是正在求助，再確認需要哪些背景，接著找相關來源，最後決定能否回答或需要人工介入。這種逐步檢查，讓每個元件的責任變得具體，也有助於回頭分析錯誤發生在哪裡。

【看圖與討論】
請大家先花約二十秒回看這一頁，找出最支持主要訊息的部分。接著思考：這個問題如果缺少目前藥名，系統應補問、提供一般衛教，還是轉交人工？
【停頓與互動 40–70 秒】邀請一位聽眾回答，或由講者以自己的門診／教學經驗回應。將答案連回本頁的資料與限制，不另推定未提供的個案結果。

【轉場】
接下來我們看「GPT, RAG and LINE: GDM Examples」，把這一頁的重點放到下一個情境。
