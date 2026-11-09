# AI Diabetes — English Speaking Lab

[開啟 ChatGPT 練習網站](https://diabetes-speaking-lab.zinojeng.chatgpt.site)

網站已發布，使用建立此網站的 ChatGPT 帳號登入。不需要登入 Cloudflare。

51 張投影片，每頁包含原始投影片縮圖（滑過放大／點擊固定查看）、短英文稿、可選的延伸說明、中文提示與發音練習。短版與延伸版可分開逐句播放、調整速度、重複跟讀。語音由裝置提供，非預製 MP3。

- [純英文短稿](english-only.md)
- [短稿＋完整延伸說明](optional-explanations.md)
- [發音指南](pronunciation-guide.md)
- [原長版中英講稿](archive/long-version-speaker-notes-latest.md)

此 GitHub 目錄保存講稿；`dist/` 為先前未發布的靜態版本。含投影片縮圖與延伸播放的最新網站由上方 ChatGPT 網址提供。

## Slides

| Slide | English script | 中文重點 |
| --- | --- | --- |
| 01 | [Generative AI in Diabetes Management](slides/slide-01.md) | 從零散資料到臨床理解；畫面數字是示意。 |
| 02 | [Outline](slides/slide-02.md) | 六個主題及其順序。 |
| 03 | [Multimodal Meal Analysis and Structured Output](slides/slide-03.md) | 餐點照片轉成可檢查的飲食紀錄。 |
| 04 | [Google Gemini Pro Meal Assessment](slides/slide-04.md) | Gemini 辨識早餐與估算熱量的示範。 |
| 05 | [Paired Glucose Testing and Dietary Education](slides/slide-05.md) | 比較餐前餐後血糖，連結飲食衛教。 |
| 06 | [Meal Records and CGM Integration](slides/slide-06.md) | 把飲食、時間與 CGM 資料放在一起。 |
| 07 | [LINE Chatbot and Patient Communication](slides/slide-07.md) | 以 LINE 作為患者與照護團隊的溝通入口。 |
| 08 | [Observational Data from a GDM Chatbot](slides/slide-08.md) | Dina 妊娠糖尿病聊天機器人的觀察資料。 |
| 09 | [Medical Chatbot Architecture](slides/slide-09.md) | 從病人提問連接到醫學來源的架構。 |
| 10 | [GPT, RAG and LINE: GDM Examples](slides/slide-10.md) | GPT、RAG 與 LINE 的妊娠糖尿病問答例子。 |
| 11 | [The Core Philosophy of Medical AI](slides/slide-11.md) | 語言模型負責表達，醫學知識須有來源。 |
| 12 | [Seven Components of the Chatbot Workflow](slides/slide-12.md) | 七個組件如何完成一次問答。 |
| 13 | [From Guidelines to Structured Knowledge](slides/slide-13.md) | 將指引整理成可搜尋、有條件限制的知識。 |
| 14 | [Hybrid Retrieval for Clinical Questions](slides/slide-14.md) | 結合不同搜尋方式以找到相關內容。 |
| 15 | [Automated Insulin Delivery with MiniMed 780G](slides/slide-15.md) | 自動化胰島素輸注與聊天模型的差別。 |
| 16 | [Pregnancy Case: Initial Pump Settings](slides/slide-16.md) | 妊娠個案的初始幫浦設定與計算。 |
| 17 | [The First Day of SmartGuard](slides/slide-17.md) | SmartGuard 第一天的飲食與血糖回顧。 |
| 18 | [AI-Assisted Insulin Adjustment](slides/slide-18.md) | AI 協助整理胰島素調整所需資料。 |
| 19 | [How Users Perceive Digital Titration](slides/slide-19.md) | 患者與醫療人員對數位劑量調整的感受。 |
| 20 | [Engagement and Real-World Titration Outcomes](slides/slide-20.md) | 使用頻率與血糖結果之間的關聯。 |
| 21 | [The Insultrate Care Workflow](slides/slide-21.md) | Insultrate 基礎胰島素調整的照護流程。 |
| 22 | [The Randomized Trial Design](slides/slide-22.md) | 24 週隨機試驗的設計與比較組。 |
| 23 | [HbA1c Improvement at 24 Weeks](slides/slide-23.md) | 24 週 HbA1c 變化。 |
| 24 | [Fasting Glucose Outcomes](slides/slide-24.md) | 空腹血糖的兩組變化。 |
| 25 | [Dose Titration and Time to Target](slides/slide-25.md) | 劑量變化與到達目標所需時間。 |
| 26 | [Hypoglycemia and Safety](slides/slide-26.md) | 低血糖事件與安全性。 |
| 27 | [What the Titration Trial Supports](slides/slide-27.md) | 整理試驗可支持的結論與限制。 |
| 28 | [LLM-Assisted CGM Reporting](slides/slide-28.md) | 將 CGM 資料轉成可供檢查的報告。 |
| 29 | [Reading the CGM Metrics Correctly](slides/slide-29.md) | 核對 CGM 分類百分比與變異係數。 |
| 30 | [Interpreting the Ambulatory Glucose Profile](slides/slide-30.md) | 把多日血糖疊在 24 小時圖上找模式。 |
| 31 | [An Integrated CGM Interpretation](slides/slide-31.md) | 把 CGM 數字、圖形與情境整合。 |
| 32 | [AI-Assisted Medical Education](slides/slide-32.md) | 為不同學習對象調整醫學教材。 |
| 33 | [Turning Conference Content into Learning Resources](slides/slide-33.md) | 把會議影片、簡報與摘要變成教材。 |
| 34 | [A Conference Knowledge Hub](slides/slide-34.md) | 會議知識中心的整理方式。 |
| 35 | [Searchable Conference Sessions](slides/slide-35.md) | 以臨床問題搜尋會議內容。 |
| 36 | [A Multimedia Learning Library](slides/slide-36.md) | 文字、語音、影片與簡報等學習形式。 |
| 37 | [Step Two: Extracting Narrative and Clinical Meaning](slides/slide-37.md) | 從逐字稿擷取敘事與臨床重點。 |
| 38 | [Dual Inputs for NotebookLM](slides/slide-38.md) | NotebookLM 同時使用文字與原始圖像。 |
| 39 | [Final Video Assembly](slides/slide-39.md) | 讓配音與正確的投影片同步。 |
| 40 | [An Integrated Knowledge Production Architecture](slides/slide-40.md) | 從輸入影音到輸出教材的整體流程。 |
| 41 | [The Cost Paradox of Metabolic Surgery](slides/slide-41.md) | 代謝手術短期成本與長期成本的不同。 |
| 42 | [Structured Microlearning and Clinical Competency](slides/slide-42.md) | 以甲狀腺超音波課程示範微學習架構。 |
| 43 | [Thyroid Ultrasound: From Video to Knowledge](slides/slide-43.md) | 甲狀腺超音波影片轉成可查核知識。 |
| 44 | [Conclusion](slides/slide-44.md) | 回顧飲食、溝通、胰島素、CGM 與教學。 |
| 45 | [Discussion and Transition](slides/slide-45.md) | 空白討論頁，用自身工作情境反思。 |
| 46 | [Appendix: Clinician and Patient Feedback](slides/slide-46.md) | 附錄：醫療人員與患者對 app 的回饋。 |
| 47 | [Appendix: A Separate Titration App Trial](slides/slide-47.md) | 附錄：另一個 My Dose Coach 隨機試驗。 |
| 48 | [Appendix: Interpreting the Safety Table](slides/slide-48.md) | 附錄：12 週試驗的安全性表格。 |
| 49 | [Appendix: Frequency of Use and Outcomes](slides/slide-49.md) | 附錄：2,517 人的使用頻率觀察資料。 |
| 50 | [Pregnancy Case: Week 23 versus Week 30](slides/slide-50.md) | 妊娠 23 週與 30 週胰島素用量比較。 |
| 51 | [Distributing Educational Content Across Platforms](slides/slide-51.md) | 教育內容跨平台發布與成效評估。 |
