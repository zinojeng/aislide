# Slide 12 — Seven Components of the Chatbot Workflow

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

## 發音練習



[回目錄](../README.md)
