# Local_quiz_app
Local cusmomizable quiz app

To insert your own questions edit the Json file. 
  In the "question" filed insert your question.
  In the "options" filed insert the options for the answers, including the correct one.
  In the "answer" filed insert the correct answer.
Don't add more than 4 options for anwser. If you wish to insert more than that you have do edit the code.
You can insert as much questions as you wish.

To modify the number of the question in the batch you have do mdify "size_displayed_questions"(now it is set =10). 
(example: I have 25 questions in my Json file, but i want to show to my student just 10 random questions from those 25. 
For this i edit "size_displayed_questions=10").

To generate an exe file run in cmd the following commands:

pip install auto-py-to-exe
auto-py-to-exe
->Script location -> Upload Quzz_app.py
->Select "One File"
->Select "Windows based"
->Click "Convert .PY to .EXE"
