# AskMe - Prpject
 People ask questions and others answers them
### files-based system
* Every time the user run it, you see the previous state (users/questions/answers)
* Multiple users can use it in same time (parallel)
    - You send question. I see it
    - I answer the question or remove it, you see this update
### Login/Sign up/Sign Out
* Any system allow a user to sign up (name, email, password, username, password)
* Allowing anonymous questions
### User operations
* Print questions: From you, To you, Feed Questions
* Ask and answer questions.
* Delete a question 
### system generated ID
* Every user has a ID
* Same for every question
### A thread question
* If a question is answered. Others can ask questions in the original question thread
* E.g. original question is parent for all of them
* If this parent question is removed, the whole thread is removed
### Correctness
*  E.g. you can’t remove a question asked to someone else!
* You can only see/edit the details of your question

## Screenshots
<img src="https://github.com/DBGad/AskMe/assets/122947749/986dd0c3-0db8-4579-8990-fad092825002" width = 300 >
<div>
  <img src="https://github.com/DBGad/AskMe/assets/122947749/6eb59677-d56f-49dd-a7ea-75d980b6d797" width = 250 height = 150>
  <img src="https://github.com/DBGad/AskMe/assets/122947749/3870b5bf-ca0c-46f6-b8e4-1dc90cc2ef9f" width =250 height = 150>
</div>
<img src ="https://github.com/DBGad/AskMe/assets/122947749/b3629e39-2572-4199-975a-3b30612ccd08" width = 400 height = 150>


## Run Locally

Clone the project

```bash
  git clone https://github.com/DBGad/AskMe.git
```

Go to the project directory

```bash
  cd AskMe
```

Run the .cpp file with any c++ compiler
