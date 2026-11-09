# Simple English + Optional Explanation

51 slides. Read the short script first; choose extra paragraphs when time allows.

## Slide 01 — Generative AI in Diabetes Management

## Short script

Today, I will show how AI can help with diabetes care. It can bring meal photos, glucose data, and patient questions together. Our goal is to make daily work easier. The care team still checks the information and makes treatment decisions.

## Optional explanation

In daily practice, we receive many kinds of information. We see glucose numbers, meal photos, insulin records, and questions from patients. These often arrive at different times and in different places. We spend a lot of time putting them together.

Please look at the picture on the right. It shows a glucose value of 156 and a time in range of 68 percent. These numbers are examples. They are not results from a clinical study. The idea is to turn a long list of numbers into a short, useful explanation.

For example, AI may notice that glucose often rises after lunch. It can ask us to review lunch, insulin timing, and activity. It cannot know the cause from the glucose line alone.

Our goal is to make records easier for patients and easier for the care team to review. The team still checks the information and makes treatment decisions.

As you listen, think about one task in your own clinic. Which task takes too much time? We can start with one small problem and see whether AI really helps.

## 中文提示

從零散資料到臨床理解；畫面數字是示意。

---

## Slide 02 — Outline

## Short script

This talk covers six topics: meal records, chatbots, insulin pumps, dose adjustment, glucose reports, and medical teaching. For each topic, we will ask three questions. What does the tool do? Who checks the result? How can it help patients and the care team?

## Optional explanation

First, we will look at meal photos and voice records. AI can help turn them into a food record. The patient still needs to check the food and the amount eaten.

Second, we will look at chatbots. A chatbot can answer common questions and collect information between clinic visits. An automatic reply does not mean that a doctor is watching all the time.

Third, we will discuss automated insulin delivery, or AID. We will use a pregnancy case to explain pump settings and follow-up. Fourth, we will look at tools that support insulin dose changes. A pump control system, a dose-adjustment app, and a language model are different tools. They need different types of testing.

Fifth, we will see how AI can help write CGM reports. CGM means continuous glucose monitoring. Finally, we will discuss medical education. AI can help turn a meeting video or a research paper into teaching material.

For each part, I will ask the same practical questions. What information do we need? What does the tool do? Who checks the result? These questions help us decide where a tool may fit in real care.

## 中文提示

六個主題及其順序。

---

## Slide 03 — Multimodal Meal Analysis and Structured Output

## Short script

A meal photo can help us start a food record. AI can name foods and estimate the amount. But the photo may miss cooking oil, ingredients, or food left on the plate. The patient should check the record before we compare it with glucose data.

## Optional explanation

Writing down every meal takes effort. This slide shows a simpler way to start. The patient takes a photo and adds a short voice message. For example: “I ate chicken, rice, and vegetables. I ate half the rice.”

The photo shows what the food looks like. The voice message adds details that the photo cannot show. Was the drink sweetened? Did the patient finish the meal? Was there extra sauce?

AI can put these details into clear fields, such as food name, portion, carbohydrate, and calories. A portion means the amount of food. The patient or dietitian then checks the record.

The numbers on this slide are examples. A photo does not measure carbohydrate with perfect accuracy. A deep bowl may hold much more rice than a shallow bowl.

The useful result is a record we can correct and connect with glucose data. We should not use an unconfirmed photo estimate by itself to decide an insulin dose.

## 中文提示

餐點照片轉成可檢查的飲食紀錄。

---

## Slide 04 — Google Gemini Pro Meal Assessment

## Short script

This app uses Google Gemini Pro to review a breakfast photo. It tries to name the foods and estimate calories. These are estimates, not measurements. A wrong food name can lead to a wrong result. We need to check the food and portion size with the patient.

## Optional explanation

There is already a useful lesson here. The original description calls the food in the bowl purple rice porridge. The English picture calls it a rice drink. We should ask the user which one is correct.

Many patients ask whether whole-grain food is always better for glucose. The answer depends on more than the name. Cooking, portion size, added sugar, and the other foods in the meal all matter.

The glycemic index, or GI, describes how a food affects glucose under test conditions. A photo cannot measure the GI of this breakfast. Numbers such as 70 or 50 in an AI reply are estimates, not measured results. A zero label for egg or oil also does not mean that any amount is suitable.

The app can still help us start a useful conversation before the meal. We can check the rice portion and the drink ingredients. We can explain what is known and what still needs checking. That is more useful than giving one exact-looking number and calling the whole meal safe.

## 中文提示

Gemini 辨識早餐與估算熱量的示範。

---

## Slide 05 — Paired Glucose Testing and Dietary Education

## Short script

Paired testing compares glucose before and after a meal. We also look at the food, insulin timing, and activity. This helps patients learn about their own response. A glucose rise alone does not tell us the cause. We need to review the full situation.

## Optional explanation

If we use a reading two hours after eating, we need to agree when the clock starts. Readings taken at different times should not be compared as if they were the same.

Look at the meals on the right. In one example, glucose rises from 83 to 134. That is a rise of 51 milligrams per deciliter. In another example, it rises from 88 to 108. That is a rise of 20.

These are useful observations. But a larger rise is not always dangerous. We also cannot say that one food explains the whole difference. The starting glucose, insulin, activity, and amount eaten may be different.

A good teaching approach is to choose one small change. For example, the patient may change a drink or a rice portion. We then review several meals under similar conditions.

This makes the discussion personal. The patient sees their own food and their own glucose. Our goal is to find choices they can keep using, rather than label a food good or bad after one meal.

## 中文提示

比較餐前餐後血糖，連結飲食衛教。

---

## Slide 06 — Meal Records and CGM Integration

## Short script

This workflow connects food records with CGM data. The patient takes a photo, checks the food, and saves the meal time. We then compare the meal with the glucose curve. Putting these records together helps the care team ask more useful questions.

## Optional explanation

The table on the left shows one way to store the information. Google Sheets can help organize records. The table alone, however, is not a complete clinical care system.

The most important detail may be the time. The photo time, meal time, and insulin time can be different. A patient may take a photo at noon and eat at one o'clock. If we use noon as the meal time, our explanation of the glucose rise may be wrong.

We also need to know whether the patient finished the food. A photo of a full plate does not tell us how much was eaten.

The glucose chart helps us find times worth reviewing. An AGP chart combines many days. It cannot prove that one meal photo caused one part of that chart. We should return to the matching day and check the details.

Once the records line up correctly, AI can help the team ask better questions. The value comes from clearer information, not just a more colorful chart.

## 中文提示

把飲食、時間與 CGM 資料放在一起。

---

## Slide 07 — LINE Chatbot and Patient Communication

## Short script

A LINE chatbot gives patients a familiar way to ask questions and share records. It can answer common questions between clinic visits. The team still needs a clear plan for urgent problems. An automatic reply does not mean a doctor is watching the messages all the time.

## Optional explanation

A familiar app can make it easier to send a glucose reading, a meal photo, or a question. Patients do not have to learn a completely new system.

Suppose a patient sends a glucose value of 156. The chatbot should first ask about the situation. Was this before or after a meal? Are there symptoms? What other records are available?

A few finger-stick readings cannot give us a reliable CGM time in range. Also, a high reading after lunch does not prove that the patient ate too much rice.

AI can help explain medical ideas in everyday language. It can also ask for missing details. The reply should be short enough to read and clear enough to use.

We must explain when staff check messages and where patients should seek urgent help. An automatic reply is not the same as a doctor being present all day and night. Patients should feel supported because the care process is clear and useful.

## 中文提示

以 LINE 作為患者與照護團隊的溝通入口。

---

## Slide 08 — Observational Data from a GDM Chatbot

## Short script

This study looked at Dina, a chatbot for women with gestational diabetes. It shows what users asked and how the system handled those questions. Response coverage is not the same as medical accuracy. We should not assume that every answer was correct or that health outcomes improved.

## Optional explanation

The researchers reviewed 610 conversations with 2,838 questions. Questions about glucose, GDM, food, and activity made up about 59 percent of the total. These are common parts of diabetes education. Patients often need to hear the information again when they use it at home.

The chatbot could answer 88.51 percent of questions. This tells us how many questions received an answer. It does not tell us that 88.51 percent of the answers were medically correct or safe.

The study also used two different data-collection periods. They were not pregnancy and postpartum periods in the same group of women. We should not explain the change in use as a fall in need after delivery.

For our service, we can use this study to choose common questions to prepare first. We should also review questions the chatbot cannot answer. Some need better information. Others need a person.

The study did not prove better glucose control or less anxiety. We would need to measure those outcomes separately.

## 中文提示

Dina 妊娠糖尿病聊天機器人的觀察資料。

---

## Slide 09 — Medical Chatbot Architecture

## Short script

This diagram shows how a chatbot links a patient question to medical sources. It finds useful information and uses it to prepare an answer. The source and the answer both need checking. Clear wording helps, but it does not make an incorrect answer safe.

## Optional explanation

The first task is to understand the question. The next task is to find useful information. The system then prepares an answer, with a way for the care team to check it.

For example, a pregnant patient asks, “Can I drink this sugar-free drink?” The words “sugar-free” are not enough. We need the ingredients and the pregnancy context. The system should find guidance that fits that question.

The LLM Wiki is a way to organize medical information and common questions. It should still point back to the original source. A summary is useful, but it does not replace the evidence behind it.

Human review also needs a real process. Someone must know when to check an answer and what to do if there is a problem.

The circles in this picture show planned roles. They do not prove that every answer will be correct. If the question asks for an insulin dose, or if key details are missing, the system needs a clear route back to the care team.

## 中文提示

從病人提問連接到醫學來源的架構。

---

## Slide 10 — GPT, RAG and LINE: GDM Examples

## Short script

These examples combine GPT, a search step called RAG, and LINE. First, the system finds useful source information. Then it writes an answer in simple language. We still need to check the source, the date, and whether the answer fits the patient's situation.

## Optional explanation

The questions here are about alcohol and sweeteners during pregnancy. They look like simple questions, but the details matter. We may need to know the ingredient, the amount, and the person's health situation.

For sweeteners, we should not treat all products as the same. Permission to use an ingredient does not mean that every amount is suitable for every pregnant person.

The reply shown on the slide is an example from the app. It is not a full, checked list of pregnancy advice. Statements about each ingredient still need a matching source.

A helpful reply can have two parts. First, give a short answer to the patient's question. Then offer a simple explanation and a source if the patient wants more detail.

If the sources disagree, say so. If information is missing, ask for it. The aim is not to sound completely certain. The aim is to help the patient understand the next step, while allowing the team to check and correct the answer.

## 中文提示

GPT、RAG 與 LINE 的妊娠糖尿病問答例子。

---

## Slide 11 — The Core Philosophy of Medical AI

## Short script

A language model can turn a difficult question into a clear explanation. But its memory should not be our only source of medical facts. We need reliable sources and a review process. The goal is to help the care team explain and check information more easily.

## Optional explanation

On the left, a question goes straight to the model. The model may give a correct answer. It may also use old information or invent a reference. A clear and confident reply can still be wrong.

On the right, the model first connects with a checked collection of medical sources. The slide calls this the Medical Vault. The model finds relevant information and explains it in language the patient can understand.

This gives us a way to check where the answer came from. We can see the source and its date. We can also ask whether it fits this patient.

Even this process can make mistakes. The search may choose the wrong page. A table note may be missing. The model may say more than the source supports.

So the main question is not only, “Does this answer sound good?” We should also ask, “What is it based on, and does it fit this situation?” That is the key message of this slide.

## 中文提示

語言模型負責表達，醫學知識須有來源。

---

## Slide 12 — Seven Components of the Chatbot Workflow

## Short script

This diagram shows seven parts of the chatbot workflow. A message enters the system, useful information is found, and an answer is prepared. Each part has a different job. Following one message through the process helps us see where errors may happen and where checks are needed.

## Optional explanation

The patient sends a question through LINE. A webhook carries the message to the system. You can think of the webhook as the connection that passes the message along.

The next part checks what the patient is asking. Then the search finds useful medical information. The knowledge layer helps organize it. The writing step turns it into a reply. Monitoring covers the whole process.

Consider this message: “I ate too much at dinner. My glucose is 11.2. Should I take more insulin?” First, we must check the unit. Second, this is a dose question. The word “dinner” does not make it a simple food-education question.

The system needs to send it to the right care process. It should not freely invent a dose. Also, old chat messages are not a current prescription.

Each part needs a clear job and a plan for errors. If the final answer is wrong, we should be able to find where the problem started. A good service depends on the whole process, not just the language model.

## 中文提示

七個組件如何完成一次問答。

---

## Slide 13 — From Guidelines to Structured Knowledge

## Short script

Uploading a guideline is only the first step. We need to keep its source, date, and clinical context. The text should be divided into useful sections without losing important limits. This makes it easier to find the right information and check where an answer came from.

## Optional explanation

This picture uses a conveyor belt to show the process. First, clean the text. Remove repeated page headings and check errors from scanned pages. Then keep the sections, recommendations, tables, and notes in a clear order.

Tables are especially important. Imagine that the system finds a treatment number but loses the row saying which patients it applies to. The number may be correct, while the advice is wrong for the patient.

We therefore need to keep the table heading and notes with the data. Different documents may need different methods. Cutting every page into equal pieces may not work well.

Next, add the source, date, and patient group. When a guideline changes, the system should know which version to use.

Finally, check the prepared content. Look closely at numbers and words such as “not.” A missing “not” can reverse the meaning. Good source preparation reduces errors, but the final answer still needs checking.

## 中文提示

將指引整理成可搜尋、有條件限制的知識。

---

## Slide 14 — Hybrid Retrieval for Clinical Questions

## Short script

Patients and guidelines may use different words for the same problem. A search system can combine exact words with similar meanings. This may help it find useful information. We still need to check whether the result fits the question before using it in an answer.

## Optional explanation

This slide combines several ways to search. One method looks for similar meaning. Another looks for exact words, such as a drug name or a lab test. A prepared set of common questions can help with frequent topics. Source labels help select the right patient group and document date.

Why use more than one method? A search based only on similar meaning may find advice for the wrong group. Pregnancy advice and advice for an older adult may contain similar words but have different goals.

The system should first confirm the patient's situation. It should then select sources that fit. If two guidelines disagree, we need to keep that difference visible. We should not force them into one certain answer.

Also, several websites may copy the same study. That still counts as one study, not several separate pieces of evidence.

The goal of the search is a small set of useful sources that we can check. Better search gives the model a stronger starting point for its reply.

## 中文提示

結合不同搜尋方式以找到相關內容。

---

## Slide 15 — Automated Insulin Delivery with MiniMed 780G

## Short script

Automated insulin delivery, or AID, is different from a chatbot. A chatbot writes replies. An AID system uses glucose data and its own rules to adjust insulin delivery. This MiniMed 780G example helps us discuss how the device works and why careful follow-up remains important.

## Optional explanation

The next case involves a woman with type 2 diabetes at about twenty weeks of pregnancy. Type 2 diabetes that was present before pregnancy is different from GDM diagnosed during pregnancy.

The pump does not remove the need for teaching and follow-up. The patient still needs to understand meal entries, alerts, and what to do when something goes wrong. The care team needs to review settings and glucose patterns.

Pregnancy also uses different glucose goals. We should not apply the usual adult range of 70 to 180 to every pregnancy report. The range of 63 to 140 is often used for pregnancy CGM. The percentage goals and evidence still depend on the type of diabetes.

We will discuss this as one supervised clinical case. It is not proof that the same device and settings fit every pregnant patient. Device approval and local rules also need checking.

With that background, let us look at how the starting settings were estimated.

## 中文提示

自動化胰島素輸注與聊天模型的差別。

---

## Slide 16 — Pregnancy Case: Initial Pump Settings

## Short script

This case starts with a total insulin dose of 80 units per day. The team uses the clinical information to plan the starting pump settings. These calculations belong to this case. They are not settings for every patient, and they need review as glucose and insulin needs change.

## Optional explanation

In this case, the team used 80 percent of that amount as a starting estimate. Eighty times 0.8 gives 64 units. Twenty percent of 64 gives 12.8 units for basal insulin. Dividing by 24 gives about 0.53 units per hour.

These are choices made for this case. They are not rules for every pregnant patient.

The sensitivity estimate is 1800 divided by 64, or about 28 milligrams per deciliter per unit. The carbohydrate ratio is 400 divided by 64, or about 6.25 grams per unit. Please keep the units clear. These two numbers mean different things.

The slide also lists a two-hour active insulin time, or AIT. This is a setting used by the system. It does not mean insulin stops working after two hours. A shorter AIT may lead to more correction insulin.

The manual basal setting is also different from SmartGuard automatic basal delivery. We need to know which mode is running. The starting formula is only the beginning. Follow-up data are needed to judge the settings.

## 中文提示

妊娠個案的初始幫浦設定與計算。

---

## Slide 17 — The First Day of SmartGuard

## Short script

This slide shows the first day of SmartGuard use. We can review meal entries, insulin timing, and the glucose curve together. The aim is to find questions that need follow-up. One day can show us the process, but it cannot prove a long-term benefit.

## Optional explanation

The original case discussion focused on glucose rising after a meal and falling later. Before changing anything, we need to check when insulin was given, how much food was entered, and what was actually eaten.

There are two different pump features to remember. Automatic correction gives correction insulin under the system's rules. Safe Meal Bolus checks a meal dose and may reduce it if the system predicts a low. They are not the same feature.

The slide discusses giving meal insulin earlier and handling larger carbohydrate meals. These are case discussions, not fixed rules for all pregnant patients. A low glucose before eating or an uncertain meal can change the plan. The available pump functions also matter.

Patients should record food honestly. They should not enter food they did not eat to make the pump give extra insulin.

The first day is also a chance to ask about the patient's experience. Which step was difficult? Were the alerts clear? Good teaching supports both safer use and better data.

## 中文提示

SmartGuard 第一天的飲食與血糖回顧。

---

## Slide 18 — AI-Assisted Insulin Adjustment

## Short script

AI may help organize the records needed for insulin dose changes. These include glucose, meals, activity, and current medication. A clear summary can support the review. The care team must still check the dose plan and the patient's situation before making a treatment decision.

## Optional explanation

The tool names on the slide are possible parts of a system. Their presence does not prove that the system has been tested for clinical use.

Suppose glucose is often high after lunch. AI can help list questions. Was the carbohydrate estimate too low? Was meal insulin late? Did activity or another medicine change? These are possible explanations to check. The glucose curve does not prove which one is correct.

The system can prepare a short decision card. It should show what the data say, why a suggestion is being considered, and which details are missing. A clinician then reviews the card and decides what to do.

This is especially important when the patient's condition changes. For example, a patient may stop eating during an illness. Yesterday's glucose readings may no longer describe today's needs.

The aim is to reduce time spent searching through records. We still need to measure whether the system saves time and how often its output needs correction. A fast approval button is not the same as a good clinical decision.

## 中文提示

AI 協助整理胰島素調整所需資料。

---

## Slide 19 — How Users Perceive Digital Titration

## Short script

This slide shows how patients and clinicians felt about a digital insulin tool. Their feedback can help us improve the service. But a survey measures what people report. It does not directly prove that work time fell or that glucose control improved.

## Optional explanation

This slide shows survey responses from both groups. Many clinicians felt that the tool reduced phone contact, made dose adjustment easier, or gave a better view of the patient's condition. Patients reported better understanding and more confidence in handling insulin.

These are useful findings, but we must read the percentages correctly. If 70 percent of respondents say a task feels easier, it does not mean that the task takes 70 percent less time. It also does not prove better glucose control.

We should ask who answered the survey. Did people who stopped using the tool also respond? Their experience may be different.

In our own clinic, we can compare feelings with real work records. Count the calls and messages. Measure the time needed to handle them. Ask whether patients understand when they should contact the team.

The tool may make the treatment plan clearer. That is worth studying. But improved trust, lower workload, and better glucose are separate outcomes. We should measure each one.

## 中文提示

患者與醫療人員對數位劑量調整的感受。

---

## Slide 20 — Engagement and Real-World Titration Outcomes

## Short script

This slide compares app use with glucose results. People who used the tool more often also had better results. This is a link, not proof of cause. The groups may differ in other ways, such as support or motivation, so we should read the findings with care.

## Optional explanation

That is different from a randomized trial. In a randomized trial, chance decides the treatment group. Here, people form groups through their own use of the app.

Frequent users may have more support, stronger phone skills, or different glucose levels at the start. They may also find the tool easier to use. These differences could affect the result.

So we can say that use and outcomes are related. We cannot say that more logins alone caused better glucose control. App use is also only one part of following a treatment plan.

For patients who use it less, start with a simple question: “Which step is difficult?” The problem may be small text, poor internet, too many entries, or an unclear purpose. Some patients may already be stable and need less use.

This kind of study can help us choose what to improve next. We can test a simpler step or more support, then check both app use and glucose results.

## 中文提示

使用頻率與血糖結果之間的關聯。

---

## Slide 21 — The Insultrate Care Workflow

## Short script

Insultrate supports changes in basal insulin, the background insulin used across the day and night. Patients record glucose and follow a care plan for dose changes. The tool helps organize the process. Clear instructions, safety checks, and follow-up remain part of the service.

## Optional explanation

The clinician sets the plan. The patient enters fasting glucose readings. The tool follows the planned rules and gives a dose suggestion. The patient records the dose used, and the team can review progress.

This is different from asking a general chatbot to invent a dose. A dose-adjustment tool needs clear rules and a defined care process.

Let us follow one day's record. Was the glucose truly fasting? Was the number entered correctly? Did the patient take the suggested dose? If any of these details are wrong, the next suggestion may be based on the wrong information.

It helps to keep three things separate: the suggested dose, the patient's confirmation, and the dose actually taken. A suggestion on the screen does not prove that it happened.

Patients also need to know when to stop and contact the team. Staff need to know who will review problems.

The value of the tool is a clear path between visits. We should be able to look back and understand why each suggestion was made and what happened after it.

## 中文提示

Insultrate 基礎胰島素調整的照護流程。

---

## Slide 22 — The Randomized Trial Design

## Short script

This was a 24-week study with about 200 people. They were assigned by chance to two groups. Before reading the results, we should check what each group received and how outcomes were measured. This helps us understand what the study can and cannot tell us.

## Optional explanation

One group received digital support with basal insulin care. The other received usual care. It was an open-label study. This means that patients and staff knew which group they were in.

Knowing the group may change behavior. Patients may check more often, and staff may give more attention. We therefore need to understand the education and follow-up provided to both groups.

We should also ask how many people finished the study and how missing data were handled. Assigning groups by chance helps make a fair comparison, but it does not remove every problem.

The report did not show a clear difference in adherence, meaning how well people followed the treatment plan. We should not claim that better adherence explains the glucose result without evidence.

Before bringing this tool to our clinic, we need to compare the study process with our own service. If the study included regular support calls, can we provide them? The tool and the care around it both matter.

## 中文提示

24 週隨機試驗的設計與比較組。

---

## Slide 23 — HbA1c Improvement at 24 Weeks

## Short script

This chart shows HbA1c over 24 weeks. HbA1c gives us a longer view of glucose control. We compare the starting values and the change in each group. A difference in HbA1c should be described in percentage points. Safety and follow-up also matter when we judge the result.

## Optional explanation

The app-supported group started near 8.8 percent and finished near 7.94 percent. The usual-care group started near 8.74 percent and finished near 8.32 percent. Both groups improved.

The average falls were about 0.87 and 0.43 percentage points. After the study's adjustment for other factors, the difference between groups was about 0.40 percentage points. The reported P value was 0.0109.

Please note the words “percentage points.” We are not saying that HbA1c fell by forty percent. We are describing the difference between two HbA1c percentages.

The main point is that the digital-support group had a greater average improvement under these study conditions. It does not mean every patient improved by the same amount.

Also, the average value was still above seven percent. The tool did not solve every treatment problem. We need to consider the patient's own target, low glucose, and the effort needed to use the tool.

When discussing this with a patient, we can say there was an extra benefit on average, while explaining that individual results may differ.

## 中文提示

24 週 HbA1c 變化。

---

## Slide 24 — Fasting Glucose Outcomes

## Short script

This chart shows fasting glucose over time. Both groups started at about 187 milligrams per deciliter. We compare how much glucose changed in each group. We also need to know how the measurements were collected and whether low-glucose events occurred during treatment.

## Optional explanation

At twenty-four weeks, the digital-support group was near 131. The usual-care group was near 142. The average falls were about 56 and 45 milligrams per deciliter.

The adjusted difference was about 11 milligrams per deciliter, with a reported P value of 0.0258. This supports the finding of better glucose results in the digital-support group.

Fasting glucose is useful when reviewing basal insulin. But it tells us only part of the story. A person may have good fasting readings and still have high glucose after meals. Low glucose during the night may also be missed.

We need to check how the readings were collected. Were they taken before breakfast? How many readings were used? Were there missing days? A reading taken after breakfast should not be treated as fasting.

This is why we look at fasting glucose together with HbA1c, low-glucose events, and the dose records. One good result should not hide another problem.

The chart helps us understand the effect of the care process, while the rest of the data help us judge the overall result.

## 中文提示

空腹血糖的兩組變化。

---

## Slide 25 — Dose Titration and Time to Target

## Short script

This slide shows insulin dose changes and the time taken to reach the glucose target. The pattern may suggest a difference between groups. But a trend is not always a clear study finding. We should check the statistical result before saying that one method worked faster.

## Optional explanation

A digital tool may help patients review their readings between visits. It may also help them follow the planned dose changes. Looking at the timing of these changes can tell us more than looking only at the final dose.

A higher dose is not automatically a better result. We still want good glucose control, fewer lows, and a plan the patient can follow.

The displayed time to first target is about 2.17 weeks in one group and 2.94 weeks in the other. The first number is smaller, but the P value is about 0.27. This study did not show a statistically clear difference for that result.

We can say that one group reached the target earlier in the numbers shown. We should not say that the study proved faster target achievement.

Also, reaching the target once is different from staying in the target range. We need to know how the study defined success.

This is a good example of reading the numbers and the study methods together. A gap between two bars does not tell the whole story.

## 中文提示

劑量變化與到達目標所需時間。

---

## Slide 26 — Hypoglycemia and Safety

## Short script

Better glucose results must be considered together with safety. This table shows low-glucose events. We should check how each event was defined and counted. Severe hypoglycemia means the person needs help from someone else. It is not defined by a glucose number alone.

## Optional explanation

One result concerns low glucose at night, at or below seventy milligrams per deciliter. The rates shown are about 0.26 and 1.15 events per person-year.

A person-year combines the number of people and their follow-up time. It is different from the number of people who had an event. It is also different from the total number of events.

For example, one person may have several low-glucose events. That adds several events, but only one person to the number affected. Both views are useful.

A difference in one category does not prove that every type of low glucose improved. Also, no clear difference in another category does not mean there is no risk. The study may have too few events to give a clear answer.

How we measure glucose also matters. More frequent checks may find more lows. We should understand the measurement and reporting process before comparing groups.

The main message is to review benefit and risk together. HbA1c alone is not enough to judge whether a tool improves care.

## 中文提示

低血糖事件與安全性。

---

## Slide 27 — What the Titration Trial Supports

## Short script

This trial suggests that digital support can help with some glucose outcomes under the study conditions. It does not show that every app will have the same effect. We need to consider who joined the study, what support they received, and how safety was monitored.

## Optional explanation

This does not mean every patient can manage insulin without support. It also does not mean that a general chatbot would give the same result.

The study included more than software. It included education, clinician settings, and follow-up. If our clinic removes those parts, our results may be different.

A useful next step is a small pilot. We can choose a group of patients who can use the tool and define when staff should step in. We also need to decide who checks the data and how quickly the team can respond.

At the end of the pilot, we should review glucose control and low-glucose events. We should also ask who stopped using the tool and why. Staff time matters too.

If something is not working, we need to find the reason. Is the record incomplete? Is the app hard to use? Is follow-up missing?

The goal is to learn whether the whole care process works in our setting. We can then improve it before offering it to more patients.

## 中文提示

整理試驗可支持的結論與限制。

---

## Slide 28 — LLM-Assisted CGM Reporting

## Short script

CGM produces a large amount of data. A language model can help turn those data into a clear draft report. The care team still needs to check the numbers and the chart. Example reports show a possible workflow; they do not prove that the system improves patient outcomes.

## Optional explanation

We use two steps. First, a computer program calculates the numbers. Second, the language model helps explain them. The model should not guess exact percentages by looking at the chart.

The values on this slide are examples for a report design. They include a time in range of 68 percent and time below range of 4 percent. They do not prove that a real patient was observed for fourteen days.

For a real report, we first check the dates, how much data are available, and which glucose range is being used. Then we calculate the measures.

AI can help connect the results with meal, activity, and symptom records. It may say, “Glucose is often high in the afternoon. Please review lunch and insulin timing.” That is a useful question, not proof of the cause.

A good report separates what we know from what we think may be happening. It also shows what is missing. This helps the clinician review the report and plan the next conversation with the patient.

## 中文提示

將 CGM 資料轉成可供檢查的報告。

---

## Slide 29 — Reading the CGM Metrics Correctly

## Short script

Before interpreting a CGM report, check the numbers and units. Add the low-glucose groups together when reporting total time below range. Do the same for high glucose. A coefficient of variation of 0.41 means 41 percent. GMI is an estimate, not a laboratory HbA1c result.

## Optional explanation

Their percentages are 0.15, 3.50, 61.28, 20.21, and 14.86. Together, they add up to 100 percent.

To find all time below range, we add the two low groups. The answer is 3.65 percent. To find all time above range, we add the two high groups. That gives 35.07 percent. Using only the high group would miss the very high readings.

The report also shows a CV of 0.41. CV describes how much glucose varies. Here, 0.41 means 41 percent. It does not mean 0.41 percent.

GMI means glucose management indicator. It is based on sensor glucose. It is not the same as a laboratory HbA1c result. GRI is another risk measure, not a percentage of time.

These checks are good tasks for a computer program. The language model can then explain the checked results.

The totals do not tell us when the lows happened. To answer that question, we need the time chart and the daily records.

## 中文提示

核對 CGM 分類百分比與變異係數。

---

## Slide 30 — Interpreting the Ambulatory Glucose Profile

## Short script

AGP puts glucose data from several days onto one 24-hour chart. It helps us find patterns at similar times of day. We should also review individual days. A repeated pattern may guide our questions, but the chart alone cannot tell us its cause.

## Optional explanation

The middle line shows the median, or middle value. The shaded areas show how widely the readings spread. A wide area means the days can be quite different.

We should not assume that every day looks like the middle line. A few important low-glucose events may be hidden by an otherwise steady-looking summary.

I first look for times when glucose may be too low. Then I look at repeated highs and wider shaded areas. After that, I return to individual days to understand the pattern.

A rise near lunchtime does not prove that lunch caused it. We still need meal and medication times. We should also check the number of days and any gaps in sensor use.

For example, a wide band at night may come from only a few unusual nights. Or it may show a problem that happens often. These need different follow-up questions.

The AGP helps us decide where to look more closely. It does not replace the daily data.

## 中文提示

把多日血糖疊在 24 小時圖上找模式。

---

## Slide 31 — An Integrated CGM Interpretation

## Short script

This page combines CGM numbers with the glucose chart. We use both to describe the main pattern and identify questions for the patient. Meals, insulin timing, and activity may help explain what happened. A useful report separates what the data show from what still needs checking.

## Optional explanation

The CV is about 41 percent. These values should all come from the same period and use the same glucose ranges. Otherwise, the summary may look clear while mixing different information.

The report also includes insulin entries. We need to be careful with their meaning. An entry time may be the time someone typed the record, not the time insulin was actually given. The number of entries is not the number of glucose events.

Before discussing repeated doses, we need the insulin type, the prescribed plan, and the real injection times. Incomplete records can lead to the wrong explanation.

A useful report ends with a few clear questions. For example: “Was this dose actually taken?” or “When did the meal start?” We do not need a long list of every possible cause.

The aim is to help the visit move forward. AI should make important gaps easier to see, so the clinician and patient can resolve them together.

## 中文提示

把 CGM 數字、圖形與情境整合。

---

## Slide 32 — AI-Assisted Medical Education

## Short script

AI can help prepare teaching material for doctors, trainees, educators, and patients. Each group needs a different level of detail. We can use simpler language while keeping the meaning of the evidence. The final material still needs review for accuracy and clear explanations.

## Optional explanation

For doctors, we may focus on the study design, results, and limits. For patients, we may explain what the idea means in daily life. Changing the title alone is not enough. We need to change the depth and wording.

We should first decide what the learner needs to understand. Then we can choose a short summary, a case, a picture, or a set of questions.

For example, students can compare two CGM reports with similar average glucose but different amounts of low glucose. Patients may learn better by looking at their own day and discussing one change.

AI can help write these different versions. The teacher still needs to check the source, the correct answer, and the level of difficulty.

The number of slides or videos does not show whether people learned. A better test is to give a new case and ask the learner to explain what they would look for.

The goal is clear understanding that people can use in another situation.

## 中文提示

為不同學習對象調整醫學教材。

---

## Slide 33 — Turning Conference Content into Learning Resources

## Short script

After a conference, we may have many videos, slides, and abstracts. AI can help organize them into learning material. We should keep links to the original sources. This makes it easier to check the findings and avoids treating an AI summary as the original evidence.

## Optional explanation

This slide uses ADA 2026 as an example of a more organized process. We start with the meeting sources. We turn speech into text, prepare a checked summary, and then make different teaching formats.

One topic may become a professional summary, a short video, or an audio lesson. The source information should stay with each version.

The process does not need to depend on one model brand. But the tools still need to work together, and their output needs checking. We should not assume that every step is fully automatic or can be finished in a few minutes.

A meeting presentation may also differ from the later research paper. We should say what source we are using and when it was available.

A practical start is to complete one talk from beginning to end. Check where errors appear. If drug names are often wrong in the transcript, fix that step before making many videos.

The aim is to save repeated work while keeping the science clear and easy to check.

## 中文提示

把會議影片、簡報與摘要變成教材。

---

## Slide 34 — A Conference Knowledge Hub

## Short script

This page brings conference resources into one place. Users can find talks and return to the material later. A useful collection should make the source, topic, and date easy to see. Good organization saves searching time and helps users check the information they need.

## Optional explanation

The counts on the screen describe that page at that time. They do not prove that every meeting talk is included or that every summary has been checked.

We need to separate two questions. Can users find the material? And is the content correct? A correct title and speaker name help with the first question. They do not answer the second.

Each item should show its original source and its status. For example, we can label it “title only,” “summary ready,” or “checked.” Then users know what they can expect.

It is also helpful to show the summary date. If the source changes, the team can see which version may need review.

Imagine searching for a topic and finding no summary. That may mean the work is not finished. It does not mean there is no evidence on the topic.

A useful resource page helps people reach the original material, understand what has been prepared, and know what still needs checking. A large number on the front page is not enough.

## 中文提示

會議知識中心的整理方式。

---

## Slide 35 — Searchable Conference Sessions

## Short script

A search tool should match the questions clinicians ask. Users may search by disease, drug, patient group, or clinical problem. The results should lead back to the source. Finding a matching term is only the first step; we still need to read the study's meaning and limits.

## Optional explanation

We may not remember the exact title of a talk. The system should therefore keep the original title and add clear topic labels. Common everyday words and medical terms should lead to useful results.

We also need to keep different types of records separate. A meeting session may contain several talks. The chair of a session may not be the author of a study. A talk is not always the same as a published paper.

Dates and times also need care, especially when meetings use different time zones.

To test the search, use a real question from your clinic. For example, try to find a trial in a particular patient group. Then check whether the results really match the question.

If there are too many results, useful filters can narrow them. If nothing is found, the system should say that its collection may be incomplete.

The goal is to help the user find relevant evidence, not just a page containing the same drug name.

## 中文提示

以臨床問題搜尋會議內容。

---

## Slide 36 — A Multimedia Learning Library

## Short script

This page offers several ways to learn: text, audio, video, and slides. People can choose the format that suits them. Each version should keep the same main message and link to the source. A simple format should not remove important study limits or change the findings.

## Optional explanation

Different formats fit different situations. A short summary may help before clinic. Audio may fit a commute. A figure may be better for a group discussion.

All versions should come from the same checked content. A shorter version should keep the main limits of the result. It should not sound more certain simply because it is shorter.

We also need to remember that several formats are not several studies. One paper turned into four resources is still one piece of evidence.

If an error is found, we should be able to locate every version that used it. Otherwise, we may fix the text while leaving an old video online.

A useful topic card can offer a short overview first, then a longer explanation and the source. This lets users choose how deeply to read.

The main questions are simple. Can people find the resource? Can they understand it? Can they check where it came from? Those are better goals than simply filling the page with more content.

## 中文提示

文字、語音、影片與簡報等學習形式。

---

## Slide 37 — Step Two: Extracting Narrative and Clinical Meaning

## Short script

A transcript records the words spoken in a video. It may contain repetition and unclear sentences. We can turn it into a shorter explanation, but we must keep the original meaning. Study numbers, comparison groups, and limits should be checked against the source.

## Optional explanation

The next step is to turn it into a clear clinical summary. Tools such as Gemini or Codex can help organize the study question, patient group, treatment, comparison group, results, and limits.

We need to keep the important numbers. Sample size, follow-up time, and the size of the treatment effect should stay linked to the source page or video time.

Small words matter too. “No clear increase” is different from “no increase.” A missing word can change the message.

Audio alone may not explain a chart fully. If the speaker points to a forest plot without reading every number, we need the original slide as well.

After review, the summary becomes a shared starting point for scripts, questions, and teaching slides. It is not automatically correct because AI wrote it.

When we find an error, we should correct this shared summary first. That helps keep the later Chinese, English, audio, and video versions consistent.

## 中文提示

從逐字稿擷取敘事與臨床重點。

---

## Slide 38 — Dual Inputs for NotebookLM

## Short script

This workflow uses both a written summary and the original slide images. The text tells the main story. The images keep details that a summary may miss, such as chart labels and units. Using both helps us check the explanation, but it does not remove the need for review.

## Optional explanation

The text helps organize the explanation. The images show the lines, labels, tables, and small notes. Together, they give the tool more of the original information.

We can ask NotebookLM or another tool to check important charts and values. But the request itself does not prove that the tool read them correctly.

For example, a survival curve needs more than a quick look at two lines. We also need the follow-up time and the number of people still being followed.

If the text and the image disagree, we should stop and check the source. The model should not simply choose the version that sounds better.

Using both inputs can reduce missing information. It cannot promise that every later answer will be correct.

The final teaching material should still point back to the source. This lets the teacher check a key statement and helps the team update the material when new information appears.

## 中文提示

NotebookLM 同時使用文字與原始圖像。

---

## Slide 39 — Final Video Assembly

## Short script

This step matches the audio with the right slides. The correct figure should appear when it is being explained. We need to check the timing, labels, and spoken numbers. A smooth video is useful only if its sound and images tell the same accurate story.

## Optional explanation

A tool may help match the meaning of the audio with a slide. But we still need to watch the full video. The right image may appear too early, too late, or for too short a time.

When a study result is discussed, viewers need time to read the groups, the axis, and the main numbers. Important limits should be spoken or clearly visible. Tiny text is easy to miss.

We should also check drug names, numbers, and captions. A small spoken error can change the meaning of a medical result.

For a short lesson, we can choose the most useful slides. We do not need to include every page from the original meeting talk. But we must not remove a note that changes the conclusion.

Ask a colleague who did not make the video to watch it. Can they follow the story? Do they have enough time to read?

The final goal is a clear lesson with the needed evidence. Fewer slides alone do not guarantee that people understand more.

## 中文提示

讓配音與正確的投影片同步。

---

## Slide 40 — An Integrated Knowledge Production Architecture

## Short script

This diagram shows the full teaching workflow. Videos, audio, and images enter the process. AI tools help organize the material, and learning resources come out at the end. Each step needs a clear purpose and a check before the result is shared.

## Optional explanation

The value is not only speed. We want a process that we can repeat, check, and update.

Different tools may do different jobs. One may prepare text. Another may make audio. Another may match the slides. If we replace a tool, we still need to test that the next step works properly.

Every output should show which source and version it used. Suppose a research paper is corrected. We need to find the summary, questions, and videos that used the old result.

If we can only update the main page but cannot find the videos, the process is still hard to maintain.

The user may see a simple page. Behind that page, the links between sources and outputs need to stay clear.

As we move from research to patient education, we can make the language easier. But the important conditions and limits must remain. That is how this process can support teaching over time.

## 中文提示

從輸入影音到輸出教材的整體流程。

---

## Slide 41 — The Cost Paradox of Metabolic Surgery

## Short script

This example shows why the time period matters when comparing the costs of metabolic surgery. An option may cost more at the start but have a different total cost over time. We need to state the time period and assumptions clearly before calling an approach cheaper.

## Optional explanation

Surgery has a large cost near the beginning. Medicines and ongoing care may create costs year after year. A comparison over one year can therefore look different from a comparison over twenty years.

The picture shows this idea. It is not a cost prediction for one patient, and it does not prove that surgery always saves money.

We need to ask what the comparison includes. Which treatment is the other choice? What follow-up, complications, and medicines are included? Whose costs are we counting: the hospital's, the payer's, or the patient's?

Patients may also consider travel, time away from work, and help at home. These costs may not appear in a hospital bill.

There is another useful distinction. A treatment can be worth its extra cost without saving money. It may cost more and still provide important health benefits.

When using AI to explain this figure, we should keep these conditions clear. The lesson is to ask better questions about the cost comparison, rather than promise the same financial result for everyone.

## 中文提示

代謝手術短期成本與長期成本的不同。

---

## Slide 42 — Structured Microlearning and Clinical Competency

## Short script

This example is a 14-chapter course on thyroid and neck ultrasound. Short lessons help organize the material into manageable topics. They can support learning and review. Completing an online lesson does not, by itself, prove clinical skill or replace supervised practice.

## Optional explanation

The wider idea is useful for diabetes education too. We can take a large amount of information and organize it into a clear learning path. But this screen is an ultrasound example. It does not show a completed diabetes course.

For diabetes training, we could create shorter lessons on CGM, glucose reports, pump use, and pregnancy care. A lesson might include a short video, a key-point picture, a case, and a few questions.

The important step is to decide what learners should be able to do. Watching a video is not the same as being able to use a pump or read a report safely.

We can ask learners to explain a new case or show a practical skill. Their answers help teachers see what needs more work.

AI can help sort the material and prepare drafts. Teachers still check the content and observe performance. A few quiz answers cannot guarantee clinical skill.

The goal is a clear course with useful practice and feedback, rather than simply a larger video collection.

## 中文提示

以甲狀腺超音波課程示範微學習架構。

---

## Slide 43 — Thyroid Ultrasound: From Video to Knowledge

## Short script

This example turns a thyroid ultrasound video into teaching material. We want learners to find the right section and check the explanation against the image. Keeping the original visual details is important. A written summary should support image review, not replace it.

## Optional explanation

A short clip can show an image feature better than a single still picture. We should keep the original clip and the time at which the teaching image was taken.

AI can help describe the image or prepare a question. But a bright spot should not automatically become a diagnosis. Features such as a comet-tail appearance need the surrounding image and the clinical setting.

We should check whether the arrow points to the correct place. We should also ask whether another view is needed. The wording should match what we can actually see.

One teaching method is to hide the label first. Ask the learner to describe the image in their own words. Then show the checked explanation and discuss the difference.

If the AI label seems wrong, return to the video. Do not accept it only because it sounds professional.

This slide shows a way to organize and teach from medical video. It does not prove that the model can diagnose thyroid disease on its own.

## 中文提示

甲狀腺超音波影片轉成可查核知識。

---

## Slide 44 — Conclusion

## Short script

AI can help with meal records, patient questions, insulin support, glucose reports, and teaching. The best starting point is one useful task with a clear way to check the result. Keep the care team involved, review errors, and expand only when the service works well.

## Optional explanation

These tools do different jobs. Some are ready for a limited role. Others still need more testing. We should judge each one by the problem it is meant to solve.

AI can help put scattered information together. It can help explain medical ideas and prepare a first draft. That may give the team more time to listen and think.

But a clear answer can still be wrong. A link between two things does not prove that one caused the other. A good survey response does not prove a clinical benefit.

We need clear sources, checked calculations, and a defined person responsible for review. Treatment decisions need the right clinical oversight. When information is missing, the system should say so.

A good first step is one small task. We can measure time, errors, patient experience, and staff workload. Then we can decide whether to improve the process or use it more widely.

Thank you for listening. I hope these examples help you choose one useful next step for your own team.

## 中文提示

回顧飲食、溝通、胰島素、CGM 與教學。

---

## Slide 45 — Discussion and Transition

## Short script

This blank slide gives us time to discuss our own work. Which task would you like to make easier? What information would the tool need, and who would check its answer? Choose one small change that your team could test and review.

## Optional explanation

Choose one repeated task. It could be reviewing meal photos, preparing a CGM report, answering a common question, or turning a lecture into teaching notes.

Before choosing an AI tool, describe the problem. Who does the task now? Which part takes too much time? What would a better process look like?

Next, think about the information you already have. What is missing? Which step could a computer help with? Which step still needs a person to check it?

Now choose one way to measure improvement. “More efficient” is too broad. We could measure minutes needed for one report. “More accurate” could mean fewer important sentences needing correction.

Please take a moment to form a one-sentence plan. For example: “We will help our educators prepare meal summaries and check whether preparation time falls.”

We do not need to solve everything today. The aim is a small project with a clear owner and a clear test of whether it helps. After this discussion, we can use the extra slides for questions.

## 中文提示

空白討論頁，用自身工作情境反思。

---

## Slide 46 — Appendix: Clinician and Patient Feedback

## Short script

This extra slide shows feedback from clinicians and patients using an insulin-adjustment app. Their experience can help improve the tool. Reported satisfaction or time savings should be described as survey findings. They are different from directly measured changes in workload or health outcomes.

## Optional explanation

On the clinician side, about 71 percent of responses reported fewer phone contacts. About 70 percent reported easier dose adjustment or a better view of the patient's condition.

On the patient side, about 71 percent reported better understanding of insulin. A similar number felt that the clinician knew more about their health. About 68 percent felt more confident handling treatment.

These numbers describe people's answers to a survey. They do not show that phone calls fell by 71 percent. They also do not measure how much confidence increased.

The sample was small, so we should be careful about applying the result to everyone. We also need to hear from people who stopped using the app.

If a patient feels safer, ask why. Is the plan clearer? Is it easier to contact staff? Or does the patient think someone is always watching the data?

The survey can help improve the service. It should be considered together with real workload, reasons for stopping, and glucose results.

## 中文提示

附錄：醫療人員與患者對 app 的回饋。

---

## Slide 47 — Appendix: A Separate Titration App Trial

## Short script

This is a separate study of My Dose Coach in Germany. It compared an app with a written plan for basal insulin dose changes. We should keep its participants, follow-up period, and results separate from the Insultrate trial. Different studies should not be combined as if they were one.

## Optional explanation

The study lasted twelve weeks and included 251 people. There were 128 in the app group and 123 in the written-plan group. Patients and staff knew the group assignment.

The app group had an extra HbA1c fall of about 0.31 percentage points after the study's adjustment. The reported P value was 0.0388. This is different from saying that HbA1c fell by 31 percent.

Both groups improved. The written plan and the care given to both groups also mattered.

The picture on the right shows individual results against starting HbA1c. It helps us see the spread of responses. It does not prove that every starting level had the same clear benefit.

This is not the same trial as the twenty-four-week Insultrate study discussed earlier. We should not mix their numbers.

The result suggests an added benefit from this app under these study conditions. Before using it in our clinic, we should also consider low glucose, ease of use, and the support patients need.

## 中文提示

附錄：另一個 My Dose Coach 隨機試驗。

---

## Slide 48 — Appendix: Interpreting the Safety Table

## Short script

This safety table comes from the 12-week trial. Read it alongside the HbA1c result. Check the number of people, the event definitions, and how long they were followed. If no events were observed, we should say that clearly. It does not mean the treatment has no risk.

## Optional explanation

Any adverse event was reported in sixteen people in the control group and thirteen in the app group. That is about 13 percent and 10.2 percent. The difference was not statistically clear. We should not call the app safer based only on these numbers.

Neither group had an observed severe low-glucose event. Severe hypoglycemia means an event in which the person needs help from someone else. It is not the same as every reading below 54 milligrams per deciliter.

The table separately counts low readings per thousand measurements. The values are about 1.2 and 1.1. Notice the unit: measurements, not patients and not years of follow-up.

High readings above 250 were less frequent in the app group in the numbers shown. We still need to consider the uncertainty of that comparison.

The study did not find a clear increase in risk. That is useful. But a short study with few events cannot rule out every risk. Education, follow-up, and a way to report problems remain important.

## 中文提示

附錄：12 週試驗的安全性表格。

---

## Slide 49 — Appendix: Frequency of Use and Outcomes

## Short script

This study grouped 2,517 users by how often they used the app each week. Higher use was linked with better results. But this was an observation, not proof that more use caused the improvement. Other differences between the groups may help explain the findings.

## Optional explanation

In the first set of bars, the fasting-glucose target was reached by about 75.1 percent of high users, 26.4 percent of moderate users, and 3.7 percent of low users.

The other sets of bars show groups with different lengths of dose adjustment. We should not read them as three copies of the same result.

On the right, the average falls in fasting glucose were about 45.4, 40.7, and 31.0 milligrams per deciliter. More frequent use was linked with better results in this analysis.

But people were not assigned by chance to use the app more or less. Starting glucose, support, phone skills, and motivation may explain some of the difference. Missing data may matter too.

The lesson is to notice low use and ask about barriers. It is not proof that everyone will get the same result by opening the app more than three days a week.

## 中文提示

附錄：2,517 人的使用頻率觀察資料。

---

## Slide 50 — Pregnancy Case: Week 23 versus Week 30

## Short script

This case compares insulin use at 23 and 30 weeks of pregnancy. Insulin needs increased between these visits. We should check the total dose, meal doses, and glucose results together. These numbers describe one case; they do not show that every pregnant patient will need the same change.

## Optional explanation

The basal and meal amounts shown add up to 25.7 units at twenty-three weeks and 70.7 units at thirty weeks. The later amount is about 2.75 times the earlier amount.

It is clearer to say “became almost three times as much” than “increased by three times.” We should also check whether correction insulin is already included in the total.

Most of the increase is in meal insulin, from 18 to 56.7 units. Basal insulin rises from 7.7 to 14 units.

These numbers describe this patient's course. They do not prove that the same bowl of rice needed three times as much insulin. Food intake, weight, pump use, and glucose results also need review.

A rising dose can worry a pregnant patient. We can explain that insulin needs may change during pregnancy. A higher dose does not mean the patient has failed. But it is also not proof that the baby is growing well.

The team should review glucose and low-glucose risk over time. Each change needs a reason based on the patient's current information.

## 中文提示

妊娠 23 週與 30 週胰島素用量比較。

---

## Slide 51 — Distributing Educational Content Across Platforms

## Short script

This slide shows how teaching material can be shared across platforms. A full video can be supported by shorter clips and written summaries. Each version should keep the main message and source. More views may increase reach, but they do not automatically mean better learning or health outcomes.

## Optional explanation

First, keep the full video in a main place, such as YouTube. Include a clear title, sources, and a version date. This gives people a place to return for the complete explanation.

Second, offer other formats. An audio version may suit listening while traveling. A short summary may suit a professional LINE group.

Third, use a social post with key points and a link to the full video. Link previews and automatic posting may work differently on each platform. They need to be checked in practice.

We also need to adjust the content for the audience. A version for doctors and a version for patients should differ in depth and language, not only in length.

Views are useful, but they do not prove learning or better care. Ask a question linked to the teaching goal. Review the answers and the questions people send back.

That feedback can improve the next version. Sharing then becomes part of an ongoing teaching process. The goal is to help people understand and use the information, not simply to send the same video to more places.

## 中文提示

教育內容跨平台發布與成效評估。

---
