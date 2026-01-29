# Kevin Conversation
1-Hi Kevin! I’m starting CSC-113 and I’ve never worked with AI tools before. Can you explain what you do and how you can help me this semester?
Welcome to the major! CSC-113 is usually where the magic happensit’s that "Intro to Programming" level where you go from just using apps to actually understanding how they’re built. Don't sweat it if you feel a little overwhelmed; every senior dev you see started exactly where you are, probably staring at a "Syntax Error" and wondering what they did wrong.
Since it’s 2026, the way we learn coding has changed a lot. We aren't just memorizing commands anymore; we’re learning how to collaborate with AI. Think of me as your Senior Pair Programmer. Here is exactly how I can help you get through this semester without pulling your hair out:
1. I’m your "Concept Translator"
Computer science has a lot of "gatekeeping" language—words like recursion, instantiation, or asynchronous. If your professor explains something in lecture and it sounds like Swahili, come to me. I’ll break it down using real-world analogies (like explaining "Arrays" using a carton of eggs or "Functions" using a recipe).
2. The "Rubber Duck" Debugger
There’s an old IT trick called "Rubber Ducking" where you explain your code to a rubber duck until you realize where you messed up. I’m a rubber duck that talks back!
* What to do: If your code isn’t working, paste it here.
* What I’ll do: Instead of just fixing it for you (which doesn't help you learn), I’ll say, "Hey, look at line 14. You're trying to call a variable that hasn't been defined yet." I’ll help you find the logic error so you actually understand the fix.
3. Learning "AI Fluency" (Prompting)
In 2026, knowing how to talk to an AI is just as important as knowing how to write Python. I can teach you how to write better "prompts."
* Instead of asking: "Write a program that sorts names,"
* I’ll teach you to ask: "Help me write a Python script that takes a list of strings, handles empty inputs, and sorts them alphabetically using a Bubble Sort logic." Learning to be specific is a superpower.
4. Code Reviews & Best Practices
Even if your code works, it might be "messy." I can look at your assignments and give you tips on how to make them "cleaner"—better variable names, more efficient logic, or adding comments so your TA can actually understand what you were thinking.
5. Managing the "AI Crutch"
This is the most important one. It’s tempting to let an AI write your whole assignment, but when you hit the midterm exam and you’re staring at a blank piece of paper, you’ll be in trouble. I’ll help you use AI as a tutor, not a ghostwriter. We’ll focus on making sure you know how the code works.
How about we start small? Do you have your syllabus yet? Or maybe a first small assignment? Tell me what language you're using (Python? Java? C++?) and we can set up your coding environment so you’re ready to rock on day one.

2-What should I know about working with AI assistants like you? Any tips for getting good results?

That is a fantastic question. Honestly, knowing how to "drive" an AI is becoming just as important as knowing the syntax of a programming language. Think of me like a super-smart junior intern: I’ve read every textbook ever written, but I don’t actually know what you are trying to accomplish unless you tell me.
Since we're in 2026, the models are much better at reasoning than they used to be, but they still need a good pilot. Here is the "Kevin from IT" guide to getting the most out of our sessions:
1. Give me the "Why" and the "Context"
If you just say, "Fix this code," I might fix the error but change the logic in a way your professor won't like.
* Pro Tip: Tell me what the assignment is actually asking for.
* Bad Prompt: "My loop isn't working."
* Good Prompt: "I'm working on a Python lab where I need to count how many times the letter 'e' appears in a sentence using a for loop. Here is my code, but it’s giving me a TypeError."
2. The "Explain Your Logic" Rule
In a CSC-113 class, getting the answer is only 10% of the goal. Understanding it is the other 90%.
* The Trick: Ask me to "Think out loud" or "Explain the steps before showing the code." This prevents you from just copy-pasting and helps you learn the "how." If you just copy-paste, the midterm is going to feel like a nightmare.
3. Use the "Rubber Duck" Method
Instead of asking me for the answer, try telling me what you think is happening.
* Say: "I think this if statement is failing because I’m comparing a string to an integer, am I on the right track?"
* This trains your brain to debug, and I can confirm your suspicion or gently nudge you in the right direction.
4. Break it Down (Decomposition)
Don’t try to build the whole app at once. AI works best when you tackle one small piece at a time.
* First, get the input working.
* Then, process the data.
* Then, format the output.
* If you ask for everything at once, the AI might get "distracted" and start hallucinating weird solutions.
5. Trust but Verify (The "Compiler is Boss" Rule)
Even in 2026, AI can make "hallucinations"—which is just a fancy IT way of saying we can be confidently wrong.
* Never assume my code works until you run it in your IDE (like VS Code or Replit).
* If you get an error message from your computer, copy and paste that error back to me. The error message is the best "clue" I have to fix the problem.
6. Ask for "Edge Cases"
This is how you get an A+. Once your code works, ask me: "Hey Kevin, what are some ways this code might break?"
* I might tell you, "What if the user enters a negative number?" or "What if they leave the box blank?"
* Handling those "edge cases" is what separates a student coder from a professional developer.
One final piece of advice: If I ever give you an answer that feels too complicated or uses stuff your professor hasn't taught yet, tell me! Just say, "Whoa, Kevin, we haven't learned 'List Comprehension' yet, can you show me a simpler way using a basic 'for' loop?"
Does that make sense? Are you ready to try your hand at some code, or do you want to talk about how to set up your laptop for the class?


3-Thanks! Here’s my first real question: I need to create a folder structure in GitHub for organizing my SAGE project. What would you recommend?



Nice! Getting your GitHub repo organized right at the start is a "pro move." It makes your life easier, but honestly? It also makes your TA (Teaching Assistant) very happy when they go to grade your work. A messy repo is like a messy room—it’s hard to find anything.
For a semester-long project like SAGE, you want a structure that is clean, scalable, and follows professional standards. Here is what I’d recommend for a solid CSC-113 folder structure:
The "Kevin-Approved" Folder Template
code
Text

sage-project/
├── .gitignore          <-- Tells GitHub what files to ignore (like temp files)
├── README.md           <-- The "homepage" of your project (essential!)
├── docs/               <-- Assignment prompts, diagrams, or your project proposal
├── src/                <-- "Source" code (the actual Python/Java/C++ files)
│   ├── main.py         <-- Your main program
│   └── utils.py        <-- Helper scripts (as you get more advanced)
├── data/               <-- Any text files or CSVs your program needs to read
├── tests/              <-- Where you keep your testing scripts
└── logs/               <-- (Optional) For output files your program generates

Why this works:
1. src/ (Source): This is the most important folder. By putting your code here instead of the "root" (the main folder), you keep your project from getting cluttered with random files.
2. README.md: This is the first thing people see on GitHub. In 2026, you can actually ask me to help you write a "Markdown" template for this. It should explain:
    * What the SAGE project is.
    * How to run your code.
    * What libraries or tools I need to install to make it work.
3. .gitignore: This is a hidden file that is super important. It tells GitHub not to upload "garbage" files like your computer's system settings (.DS_Store on Mac) or those weird __pycache__ folders Python creates.
    * Kevin Tip: You can go to gitignore.io and type "Python" to get a perfect starter file for this.
4. docs/: Professors love this. If they give you a PDF instruction sheet for SAGE, toss it in here. It keeps everything in one place so you don’t have to hunt through your "Downloads" folder later in the semester.
How to set it up:
You don't have to do this through the GitHub website. If you have your terminal or IDE open, you can do it with a few commands, or just right-click and "New Folder" in your project folder.
A quick question for you: Do you already have Git installed on your laptop, or are you using the GitHub Desktop app? (The Desktop app is usually much easier for your first semester!)
And once you've got this folder made, let me know, and I can help you write your first README to make the project look official!
