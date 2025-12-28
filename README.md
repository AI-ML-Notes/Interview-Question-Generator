# Interview-Question-Generator

For Software Engineers. 

Questions are generated and evaluated by Gemini APIs.


## How to get started?

1. Go to the [notebook](https://github.com/AI-ML-Notes/Interview-Question-Generator/blob/main/Interview_Question_Generator.ipynb)

2. Generate you Gemini API Key on [Google AI Studio](https://aistudio.google.com/app/api-keys). <br> Update it on line number 25. 
(os.environ["GOOGLE_API_KEY"] = ""    # YOUR_GEMINI_API_KEY)

3. Uncomment the first line of code. <br>
("# #@title Interview Question Generator" &nbsp;&nbsp;-> &nbsp;&nbsp;"#@title Interview Question Generator") <br>
And, toggle the code cell.

4. Run the code cell. A widget will appear. <br> Fill in the details and proceed. <br> Answer the questions and click submit to evaluate.


## Generate 4 kinds of questions.

#### 1. MCQ (Single Correct)
![1. MCQ (Single Correct)](docs/MCQ_Single_Correct.png)

#### 2. MCQ (Multiple Correct)
![2. MCQ (Multiple Correct)](docs/MCQ_Multiple_Correct.png)

#### 3. Theoretical (answer in 30 words)
![3. Theoretical (answer in 30 words)](docs/Theoretical_answer_in_30_words.png)

#### 4. Programming (Hands-on)
![4. Programming (Hands-on)](docs/Programming_Hands_on.png)
