# Slide 09 — Medical Chatbot Architecture

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

## 發音練習

- **clear** — cl- 的 L 舌尖接觸齒齦；美式字尾 R 舌頭不接觸。
- **patient** — /ˈpeɪʃənt/：A 是 /eɪ/ 滑動音；最後 /nt/ 收住。
- **information** — 重音在 -MA- /meɪ/，末尾 /ʃən/；不要每節一樣重。

[回目錄](../README.md)
