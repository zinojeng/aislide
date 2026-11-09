# English-first bilingual scripts

51 short scripts. English first; brief Chinese reminder follows.

## Slide 01 — Generative AI in Diabetes Management

Today, I will show how AI can help with diabetes care. It can bring meal photos, glucose data, and patient questions together. Our goal is to make daily work easier. The care team still checks the information and makes treatment decisions.

### 中文提示

從零散資料到臨床理解；畫面數字是示意。

## Slide 02 — Outline

This talk covers six topics: meal records, chatbots, insulin pumps, dose adjustment, glucose reports, and medical teaching. For each topic, we will ask three questions. What does the tool do? Who checks the result? How can it help patients and the care team?

### 中文提示

六個主題及其順序。

## Slide 03 — Multimodal Meal Analysis and Structured Output

A meal photo can help us start a food record. AI can name foods and estimate the amount. But the photo may miss cooking oil, ingredients, or food left on the plate. The patient should check the record before we compare it with glucose data.

### 中文提示

餐點照片轉成可檢查的飲食紀錄。

## Slide 04 — Google Gemini Pro Meal Assessment

This app uses Google Gemini Pro to review a breakfast photo. It tries to name the foods and estimate calories. These are estimates, not measurements. A wrong food name can lead to a wrong result. We need to check the food and portion size with the patient.

### 中文提示

Gemini 辨識早餐與估算熱量的示範。

## Slide 05 — Paired Glucose Testing and Dietary Education

Paired testing compares glucose before and after a meal. We also look at the food, insulin timing, and activity. This helps patients learn about their own response. A glucose rise alone does not tell us the cause. We need to review the full situation.

### 中文提示

比較餐前餐後血糖，連結飲食衛教。

## Slide 06 — Meal Records and CGM Integration

This workflow connects food records with CGM data. The patient takes a photo, checks the food, and saves the meal time. We then compare the meal with the glucose curve. Putting these records together helps the care team ask more useful questions.

### 中文提示

把飲食、時間與 CGM 資料放在一起。

## Slide 07 — LINE Chatbot and Patient Communication

A LINE chatbot gives patients a familiar way to ask questions and share records. It can answer common questions between clinic visits. The team still needs a clear plan for urgent problems. An automatic reply does not mean a doctor is watching the messages all the time.

### 中文提示

以 LINE 作為患者與照護團隊的溝通入口。

## Slide 08 — Observational Data from a GDM Chatbot

This study looked at Dina, a chatbot for women with gestational diabetes. It shows what users asked and how the system handled those questions. Response coverage is not the same as medical accuracy. We should not assume that every answer was correct or that health outcomes improved.

### 中文提示

Dina 妊娠糖尿病聊天機器人的觀察資料。

## Slide 09 — Medical Chatbot Architecture

This diagram shows how a chatbot links a patient question to medical sources. It finds useful information and uses it to prepare an answer. The source and the answer both need checking. Clear wording helps, but it does not make an incorrect answer safe.

### 中文提示

從病人提問連接到醫學來源的架構。

## Slide 10 — GPT, RAG and LINE: GDM Examples

These examples combine GPT, a search step called RAG, and LINE. First, the system finds useful source information. Then it writes an answer in simple language. We still need to check the source, the date, and whether the answer fits the patient's situation.

### 中文提示

GPT、RAG 與 LINE 的妊娠糖尿病問答例子。

## Slide 11 — The Core Philosophy of Medical AI

A language model can turn a difficult question into a clear explanation. But its memory should not be our only source of medical facts. We need reliable sources and a review process. The goal is to help the care team explain and check information more easily.

### 中文提示

語言模型負責表達，醫學知識須有來源。

## Slide 12 — Seven Components of the Chatbot Workflow

This diagram shows seven parts of the chatbot workflow. A message enters the system, useful information is found, and an answer is prepared. Each part has a different job. Following one message through the process helps us see where errors may happen and where checks are needed.

### 中文提示

七個組件如何完成一次問答。

## Slide 13 — From Guidelines to Structured Knowledge

Uploading a guideline is only the first step. We need to keep its source, date, and clinical context. The text should be divided into useful sections without losing important limits. This makes it easier to find the right information and check where an answer came from.

### 中文提示

將指引整理成可搜尋、有條件限制的知識。

## Slide 14 — Hybrid Retrieval for Clinical Questions

Patients and guidelines may use different words for the same problem. A search system can combine exact words with similar meanings. This may help it find useful information. We still need to check whether the result fits the question before using it in an answer.

### 中文提示

結合不同搜尋方式以找到相關內容。

## Slide 15 — Automated Insulin Delivery with MiniMed 780G

Automated insulin delivery, or AID, is different from a chatbot. A chatbot writes replies. An AID system uses glucose data and its own rules to adjust insulin delivery. This MiniMed 780G example helps us discuss how the device works and why careful follow-up remains important.

### 中文提示

自動化胰島素輸注與聊天模型的差別。

## Slide 16 — Pregnancy Case: Initial Pump Settings

This case starts with a total insulin dose of 80 units per day. The team uses the clinical information to plan the starting pump settings. These calculations belong to this case. They are not settings for every patient, and they need review as glucose and insulin needs change.

### 中文提示

妊娠個案的初始幫浦設定與計算。

## Slide 17 — The First Day of SmartGuard

This slide shows the first day of SmartGuard use. We can review meal entries, insulin timing, and the glucose curve together. The aim is to find questions that need follow-up. One day can show us the process, but it cannot prove a long-term benefit.

### 中文提示

SmartGuard 第一天的飲食與血糖回顧。

## Slide 18 — AI-Assisted Insulin Adjustment

AI may help organize the records needed for insulin dose changes. These include glucose, meals, activity, and current medication. A clear summary can support the review. The care team must still check the dose plan and the patient's situation before making a treatment decision.

### 中文提示

AI 協助整理胰島素調整所需資料。

## Slide 19 — How Users Perceive Digital Titration

This slide shows how patients and clinicians felt about a digital insulin tool. Their feedback can help us improve the service. But a survey measures what people report. It does not directly prove that work time fell or that glucose control improved.

### 中文提示

患者與醫療人員對數位劑量調整的感受。

## Slide 20 — Engagement and Real-World Titration Outcomes

This slide compares app use with glucose results. People who used the tool more often also had better results. This is a link, not proof of cause. The groups may differ in other ways, such as support or motivation, so we should read the findings with care.

### 中文提示

使用頻率與血糖結果之間的關聯。

## Slide 21 — The Insultrate Care Workflow

Insultrate supports changes in basal insulin, the background insulin used across the day and night. Patients record glucose and follow a care plan for dose changes. The tool helps organize the process. Clear instructions, safety checks, and follow-up remain part of the service.

### 中文提示

Insultrate 基礎胰島素調整的照護流程。

## Slide 22 — The Randomized Trial Design

This was a 24-week study with about 200 people. They were assigned by chance to two groups. Before reading the results, we should check what each group received and how outcomes were measured. This helps us understand what the study can and cannot tell us.

### 中文提示

24 週隨機試驗的設計與比較組。

## Slide 23 — HbA1c Improvement at 24 Weeks

This chart shows HbA1c over 24 weeks. HbA1c gives us a longer view of glucose control. We compare the starting values and the change in each group. A difference in HbA1c should be described in percentage points. Safety and follow-up also matter when we judge the result.

### 中文提示

24 週 HbA1c 變化。

## Slide 24 — Fasting Glucose Outcomes

This chart shows fasting glucose over time. Both groups started at about 187 milligrams per deciliter. We compare how much glucose changed in each group. We also need to know how the measurements were collected and whether low-glucose events occurred during treatment.

### 中文提示

空腹血糖的兩組變化。

## Slide 25 — Dose Titration and Time to Target

This slide shows insulin dose changes and the time taken to reach the glucose target. The pattern may suggest a difference between groups. But a trend is not always a clear study finding. We should check the statistical result before saying that one method worked faster.

### 中文提示

劑量變化與到達目標所需時間。

## Slide 26 — Hypoglycemia and Safety

Better glucose results must be considered together with safety. This table shows low-glucose events. We should check how each event was defined and counted. Severe hypoglycemia means the person needs help from someone else. It is not defined by a glucose number alone.

### 中文提示

低血糖事件與安全性。

## Slide 27 — What the Titration Trial Supports

This trial suggests that digital support can help with some glucose outcomes under the study conditions. It does not show that every app will have the same effect. We need to consider who joined the study, what support they received, and how safety was monitored.

### 中文提示

整理試驗可支持的結論與限制。

## Slide 28 — LLM-Assisted CGM Reporting

CGM produces a large amount of data. A language model can help turn those data into a clear draft report. The care team still needs to check the numbers and the chart. Example reports show a possible workflow; they do not prove that the system improves patient outcomes.

### 中文提示

將 CGM 資料轉成可供檢查的報告。

## Slide 29 — Reading the CGM Metrics Correctly

Before interpreting a CGM report, check the numbers and units. Add the low-glucose groups together when reporting total time below range. Do the same for high glucose. A coefficient of variation of 0.41 means 41 percent. GMI is an estimate, not a laboratory HbA1c result.

### 中文提示

核對 CGM 分類百分比與變異係數。

## Slide 30 — Interpreting the Ambulatory Glucose Profile

AGP puts glucose data from several days onto one 24-hour chart. It helps us find patterns at similar times of day. We should also review individual days. A repeated pattern may guide our questions, but the chart alone cannot tell us its cause.

### 中文提示

把多日血糖疊在 24 小時圖上找模式。

## Slide 31 — An Integrated CGM Interpretation

This page combines CGM numbers with the glucose chart. We use both to describe the main pattern and identify questions for the patient. Meals, insulin timing, and activity may help explain what happened. A useful report separates what the data show from what still needs checking.

### 中文提示

把 CGM 數字、圖形與情境整合。

## Slide 32 — AI-Assisted Medical Education

AI can help prepare teaching material for doctors, trainees, educators, and patients. Each group needs a different level of detail. We can use simpler language while keeping the meaning of the evidence. The final material still needs review for accuracy and clear explanations.

### 中文提示

為不同學習對象調整醫學教材。

## Slide 33 — Turning Conference Content into Learning Resources

After a conference, we may have many videos, slides, and abstracts. AI can help organize them into learning material. We should keep links to the original sources. This makes it easier to check the findings and avoids treating an AI summary as the original evidence.

### 中文提示

把會議影片、簡報與摘要變成教材。

## Slide 34 — A Conference Knowledge Hub

This page brings conference resources into one place. Users can find talks and return to the material later. A useful collection should make the source, topic, and date easy to see. Good organization saves searching time and helps users check the information they need.

### 中文提示

會議知識中心的整理方式。

## Slide 35 — Searchable Conference Sessions

A search tool should match the questions clinicians ask. Users may search by disease, drug, patient group, or clinical problem. The results should lead back to the source. Finding a matching term is only the first step; we still need to read the study's meaning and limits.

### 中文提示

以臨床問題搜尋會議內容。

## Slide 36 — A Multimedia Learning Library

This page offers several ways to learn: text, audio, video, and slides. People can choose the format that suits them. Each version should keep the same main message and link to the source. A simple format should not remove important study limits or change the findings.

### 中文提示

文字、語音、影片與簡報等學習形式。

## Slide 37 — Step Two: Extracting Narrative and Clinical Meaning

A transcript records the words spoken in a video. It may contain repetition and unclear sentences. We can turn it into a shorter explanation, but we must keep the original meaning. Study numbers, comparison groups, and limits should be checked against the source.

### 中文提示

從逐字稿擷取敘事與臨床重點。

## Slide 38 — Dual Inputs for NotebookLM

This workflow uses both a written summary and the original slide images. The text tells the main story. The images keep details that a summary may miss, such as chart labels and units. Using both helps us check the explanation, but it does not remove the need for review.

### 中文提示

NotebookLM 同時使用文字與原始圖像。

## Slide 39 — Final Video Assembly

This step matches the audio with the right slides. The correct figure should appear when it is being explained. We need to check the timing, labels, and spoken numbers. A smooth video is useful only if its sound and images tell the same accurate story.

### 中文提示

讓配音與正確的投影片同步。

## Slide 40 — An Integrated Knowledge Production Architecture

This diagram shows the full teaching workflow. Videos, audio, and images enter the process. AI tools help organize the material, and learning resources come out at the end. Each step needs a clear purpose and a check before the result is shared.

### 中文提示

從輸入影音到輸出教材的整體流程。

## Slide 41 — The Cost Paradox of Metabolic Surgery

This example shows why the time period matters when comparing the costs of metabolic surgery. An option may cost more at the start but have a different total cost over time. We need to state the time period and assumptions clearly before calling an approach cheaper.

### 中文提示

代謝手術短期成本與長期成本的不同。

## Slide 42 — Structured Microlearning and Clinical Competency

This example is a 14-chapter course on thyroid and neck ultrasound. Short lessons help organize the material into manageable topics. They can support learning and review. Completing an online lesson does not, by itself, prove clinical skill or replace supervised practice.

### 中文提示

以甲狀腺超音波課程示範微學習架構。

## Slide 43 — Thyroid Ultrasound: From Video to Knowledge

This example turns a thyroid ultrasound video into teaching material. We want learners to find the right section and check the explanation against the image. Keeping the original visual details is important. A written summary should support image review, not replace it.

### 中文提示

甲狀腺超音波影片轉成可查核知識。

## Slide 44 — Conclusion

AI can help with meal records, patient questions, insulin support, glucose reports, and teaching. The best starting point is one useful task with a clear way to check the result. Keep the care team involved, review errors, and expand only when the service works well.

### 中文提示

回顧飲食、溝通、胰島素、CGM 與教學。

## Slide 45 — Discussion and Transition

This blank slide gives us time to discuss our own work. Which task would you like to make easier? What information would the tool need, and who would check its answer? Choose one small change that your team could test and review.

### 中文提示

空白討論頁，用自身工作情境反思。

## Slide 46 — Appendix: Clinician and Patient Feedback

This extra slide shows feedback from clinicians and patients using an insulin-adjustment app. Their experience can help improve the tool. Reported satisfaction or time savings should be described as survey findings. They are different from directly measured changes in workload or health outcomes.

### 中文提示

附錄：醫療人員與患者對 app 的回饋。

## Slide 47 — Appendix: A Separate Titration App Trial

This is a separate study of My Dose Coach in Germany. It compared an app with a written plan for basal insulin dose changes. We should keep its participants, follow-up period, and results separate from the Insultrate trial. Different studies should not be combined as if they were one.

### 中文提示

附錄：另一個 My Dose Coach 隨機試驗。

## Slide 48 — Appendix: Interpreting the Safety Table

This safety table comes from the 12-week trial. Read it alongside the HbA1c result. Check the number of people, the event definitions, and how long they were followed. If no events were observed, we should say that clearly. It does not mean the treatment has no risk.

### 中文提示

附錄：12 週試驗的安全性表格。

## Slide 49 — Appendix: Frequency of Use and Outcomes

This study grouped 2,517 users by how often they used the app each week. Higher use was linked with better results. But this was an observation, not proof that more use caused the improvement. Other differences between the groups may help explain the findings.

### 中文提示

附錄：2,517 人的使用頻率觀察資料。

## Slide 50 — Pregnancy Case: Week 23 versus Week 30

This case compares insulin use at 23 and 30 weeks of pregnancy. Insulin needs increased between these visits. We should check the total dose, meal doses, and glucose results together. These numbers describe one case; they do not show that every pregnant patient will need the same change.

### 中文提示

妊娠 23 週與 30 週胰島素用量比較。

## Slide 51 — Distributing Educational Content Across Platforms

This slide shows how teaching material can be shared across platforms. A full video can be supported by shorter clips and written summaries. Each version should keep the main message and source. More views may increase reach, but they do not automatically mean better learning or health outcomes.

### 中文提示

教育內容跨平台發布與成效評估。
