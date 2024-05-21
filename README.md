### Day 25: May 21, 2024

# Day 25 of 100 Days of Code: Deep Learning and Strategic Technology Planning

## Today's Progress

Continued "Practical Deep Learning for Coders: Lesson 1" from FastAI. Also created a technology radar.

Using the technology radar I map out essential skills after finishing the "Recovering from a Job Loss in Technology" course on LinkedIn Learning.

Additionally, I began the "Postman Essential Training" and completed the setup.

## Thoughts

Today was about blending continued deep learning study with strategic planning and skill acquisition. Creating the technology radar felt good; helping me focus my learning on technologies that will shape my career trajectory.

## Hashtags

\#100DaysOfCode \#WebDevelopment \#JavaScript \#FastAI \#MachineLearning \#Poastman

### Day 24: May 20, 2024

# Day 24 of 100 Days of Code: More Deep Learning Journey with FastAI

## Today's Progress

27 minutes into the "Practical Deep Learning for Coders: Lesson 1".

I cloned the FastAI repository, updated my Jupyter Notebook to the latest version.

## Thoughts

I'm excited about the upcoming sessions and the potential to significantly enhance my understanding and skills in this cutting-edge field.

## Hashtags

\#100DaysOfCode \#WebDevelopment \#JavaScript \#CSS \#FastAI \#MachineLearning

<hr style="border-width: 3px;">

### Day 23: May 19, 2024

# Day 23 of 100 Days of Code: Image Classification with FastAI

## Today's Progress

Installed and set up the FastAI and Fastbook libraries, using them for a script that searches, downloads, and categorizes images for classification.

Successfully fine-tuned a model on these images after setting up the necessary data structures and training environments.

## Thoughts

Today's progress on debugging and refining the process was particularly enlightening, reinforcing the importance of precision in machine learning.

## Hashtags

\#100DaysOfCode \#WebDevelopment \#JavaScript \#CSS \#FastAI \#MachineLearning

<hr style="border-width: 3px;">

### Day 22: May 18, 2024

# Day 22 of 100 Days of Code: Portfolio Testing and Diving into Machine Learning with fast.ai

## Today's Progress

Tested my newly deployed portfolio and began exploring machine learning with fast.ai.

Identified several bugs in my portfolio and noted key areas for improvement, particularly with the CSS. While I'll continue to refine these elements daily, I also kicked off a new learning phase with fast.ai.

I set up my Kaggle account, intending to follow along with Lesson 1 of fast.ai. However, I encountered numerous errors, which proved to be a significant learning curve. Troubleshooting these will be my focus tomorrow.

## Thoughts

Balancing portfolio improvements with advancing my technical skills in machine learning is challenging but enriching. Each error is a step forward in understanding more about data science and its practical applications.

## Link to Work

Portfoli: [https://jason-hargrove-portfolio-5abbf0f5084c.herokuapp.com/](https://jason-hargrove-portfolio-5abbf0f5084c.herokuapp.com/)

## Hashtags

\#100DaysOfCode \#WebDevelopment \#JavaScript \#CSS \#FastAI \#MachineLearning

<hr style="border-width: 3px;">

### Day 21: May 17, 2024

# Day 21 of 100 Days of Code: Major Deployment Day on Heroku!

## Today's Progress

Deployed multiple applications on Heroku that are featured in my software engineering portfolio. This includes:

- **Search the MET**: A full-stack MERN application that utilizes the Metropolitan Museum of Art's API to search their collection. Currently troubleshooting some functionality issues.
- **For Goodness Cakes**: Collaborated with a cross-functional team to turn an Instagram bakery concept into a robust full-stack web application.
- **Radioactive Sticker Store**: Deployed a full CRUD multi-page application.
- **Accumulative Dose**: Launched a 'choose your own adventure' game built with HTML, CSS, and JavaScript.

## Thoughts

Encountered a few snags, particularly with the "Search the MET" application that isn't working as expected. Manual testing and debugging are on my immediate agenda to ensure all applications run smoothly and efficiently.

## Link to Work

Portfoli: [https://jason-hargrove-portfolio-5abbf0f5084c.herokuapp.com/](https://jason-hargrove-portfolio-5abbf0f5084c.herokuapp.com/)

## Hashtags

\#100DaysOfCode \#Heroku \#JavaScript \#GitHub \#WebDevelopment

<hr style="border-width: 3px;">

### Day 20: May 16, 2024

# Day 20 of 100 Days of Code: Redeploying My Portfolio on Heroku

## Today's Progress

Today, I took a significant step forward by redeploying my full-stack software engineering portfolio on Heroku.

## Thoughts

While the deployment is up, I still need to conduct thorough testing to ensure all links and functionalities are working as expected. There's a bit of work ahead to refine and optimize the performance of the site.

## Link to Work

Portfoli: [https://jason-hargrove-portfolio-5abbf0f5084c.herokuapp.com/](https://jason-hargrove-portfolio-5abbf0f5084c.herokuapp.com/)

## Hashtags

\#100DaysOfCode \#Heroku \#JavaScript \#GitHub \#WebDevelopment

<hr style="border-width: 3px;">

### Day 19: May 15, 2024

# Day 19 of 100 Days of Code: Python Data Handling, Parsing, and More

## Today's Progress

Finished "Learning Python" on LinkedIn Learning. Today I worked with internet data handling capabilities.

I began by fetching data from the internet using urllib.request and explored JSON data manipulation to enhance my ability to process and interpret web data dynamically. I also tackled SSL issues, ensuring secure data transactions.

Additionally, I practiced parsing and processing HTML with Python's html.parser module, gaining a better understanding of web content manipulation. I then moved on to manipulating XML, learning to parse, modify, and create XML elements which are crucial for managing structured data.

## Thoughts

Feels good to have this course behind me - on to the next!

## Link to Work

Repo: [https://github.com/Jason-Hargrove/learning-python.git](https://github.com/Jason-Hargrove/learning-python.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 18: May 14, 2024

# Day 18 of 100 Days of Code: Python Date and Time Code Challenge and Quiz

## Today's Progress

Python coding challenge that involved working extensively with dates and times using the calendar module.

Count the occurrences of a specific day of the week within a given month and year. I wrote a function count_days that efficiently calculates how often each day appears, such as how many Mondays are in December 2025. Additionally, I enhanced my understanding of Python’s date module by writing a script to predict tomorrow’s day of the week.

Following the coding session, I completed a chapter quiz that tested my knowledge on handling dates and times in Python, reinforcing the concepts I practiced in the challenge.

## Thoughts

Got sidetracked a bit with some of the questions, but learned a lot.

## Code

```python
import calendar
from datetime import date

def count_days(year, month, whichday):
    # Generate the calendar for the month
    cal = calendar.monthcalendar(year, month)
    day_count = 0

    # Count occurrences of the specific day of the week
    for week in cal:
        if week[whichday] != 0: # The day of the week is in this week
            day_count += 1

    return day_count

print(count_days(2025, 12, 0))
# Wxpected result: 5
```

## Link to Work

Repo: [https://github.com/Jason-Hargrove/learning-python.git](https://github.com/Jason-Hargrove/learning-python.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 17: May 13, 2024

# Day 17 of 100 Days of Code: Python's Calendar Module

## Today's Progress

Explored the Python calendar module, for managing and displaying calendars in different formats.

I started by generating plain text calendars, then moved on to creating HTML formatted calendars which can be seamlessly integrated into web applications. I also delved into looping over days of a month to understand how Python handles dates that span multiple months.

Additionally, I utilized the module to find specific days, such as the first Friday of each month for scheduling recurring team meetings. This practical application of the calendar module highlighted its utility in real-world programming scenarios.

## Thoughts

The ability to manipulate and interact with calendar data programmatically opens up numerous possibilities for developing applications that require scheduling and date tracking.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/learning-python.git](https://github.com/Jason-Hargrove/learning-python.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 16: May 12, 2024

# Day 16 of 100 Days of Code: Python's timedelta

## Today's Progress

Experimenting with timedelta objects.

I learned how to manipulate dates and times for different practical applications, like projecting dates in the future and calculating past dates. For example, I calculated what date it would be one year from now, and what the date was exactly one week ago.

## Thoughts

Using timedelta to navigate through time in programming offers a fascinating perspective on how software can interact with real-world time events.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/learning-python.git](https://github.com/Jason-Hargrove/learning-python.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 15: May 11, 2024

# Day 15 of 100 Days of Code: Date and Time Formatting in Python

## Today's Progress

Explored Python's datetime module by diving into different ways to format dates and times.

I utilized datetime.now() to fetch current date and time, and experimented with various formatting options to display these values in user-friendly and locale-specific formats.

## Thoughts

Learning to format date and time according to different locales and requirements has been interesting.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/learning-python.git](https://github.com/Jason-Hargrove/learning-python.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 14: May 10, 2024

# Day 14 of 100 Days of Code: Exploring Date and Time in Python

## Today's Progress

Handling dates and times using Python’s datetime module.

I started by using the simple today() method from the date class to fetch the current date and then printed out its individual components such as year, month, and day. I also retrieved today’s weekday, understanding Python’s system where Monday is 0 and Sunday is 6. Additionally, I explored the datetime class to get not only today's date but also the current time.

## Thoughts

It’s incredibly useful to see how Python can manage date and time data.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/learning-python.git](https://github.com/Jason-Hargrove/learning-python.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 13: May 9, 2024

# Day 13 of 100 Days of Code: Python File Handling and Directory Analysis

## Today's Progress

Python code challenge today: calculating total number of bytes for text files, and chapter quiz.

The task involved filtering to include only .txt files and excluding all others from the byte count. Reinforced my understanding of file operations and directory traversal in Python. Additionally, I completed a chapter quiz to consolidate my learning further.

## Thoughts

Today’s challenge was a great mix of real-world application and theory.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/learning-python.git](https://github.com/Jason-Hargrove/learning-python.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 12: May 8, 2024

# Day 12 of 100 Days of Code: File System Operations in Python

## Today's Progress

Python's OS module, specifically exploring its path utilities. I learned how to check for item existence and type, work with file paths, and retrieve the modification times of files. Additionally, I calculated how long ago an item was modified, which adds a practical aspect to managing file systems.

## Thoughts

Understanding and manipulating the file system with Python's built-in capabilities is incredibly powerful.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/learning-python.git](https://github.com/Jason-Hargrove/learning-python.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

# Day 11 of 100 Days of Code: Python Challenges and File Handling

## Today's Progress

Python coding challenges and quizzes to sharpen my foundational skills. Explored reading and writing files with Python.

## Thoughts

I haven't done coding challenges in a bit. I do enjoy the exposure to different problem-solving approaches.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/learning-python.git](https://github.com/Jason-Hargrove/learning-python.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 10: May 6, 2024

# Day 10 of 100 Days of Code: Python Functions and Control Flow

## Today's Progress

Defining functions in Python, using them to encapsulate reusable blocks of code. Conditional logic, employing if, elif, and else statements to control the flow of my programs. The match-case statement proved invaluable for comparing multiple values easily. I also practiced loops—using while and for loops to iterate over data, incorporating break and continue to fine-tune loop execution, and utilizing the enumerate() function to access index during loops. Additionally, I began working with classes and handling exceptions to manage errors more gracefully.

In today's coding challenge, I tackled creating a function to determine if a string is a palindrome, reinforcing my function writing skills and understanding of Python's string manipulation capabilities.

## Thoughts

Each new Python feature I learn opens up more possibilities for solving problems efficiently and creatively.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/learning-python.git](https://github.com/Jason-Hargrove/learning-python.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 9: May 5, 2024

# Day 9 of 100 Days of Code: Python Basics and Git Setup

## Today's Progress

Setup a new Git repository. Python basics, working with different data types and global and local variables in functions.

Although I had to cut my study time short today, I really enjoyed getting back to basics and look forward to tackling Python functions tomorrow.

## Thoughts

It's fascinating how different languages handle basics like variable scope.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/learning-python.git](https://github.com/Jason-Hargrove/learning-python.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 8: May 4, 2024

# Day 8 of 100 Days of Code: Brushing up on Python

## Today's Progress

Installed latest version of Python and configuring my environment. Solved conflicts in my .zshrc file due to the updated version of Python.

After ensuring everything was set up correctly, I dived into a LinkedIn Learning course on Python. I cloned the course repository and successfully built a small "Hello World" app, marking my first Python project on this new setup.

## Thoughts

Navigating through system configurations and setting up a new programming language was challenging. It's exciting to get back int Python.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git](https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 7: May 3, 2024

# Day 7 of 100 Days of Code: Building an Interactive Assistant in Node.js

## Today's Progress

Created an assistant within my Node app, added threads to capture user input, parsing the assistant response, and LangChain.

## Thoughts

Each step forward in this project opens up new possibilities for creating more intuitive and responsive user interactions.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git](https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 6: May 2, 2024

# Day 6 of 100 Days of Code: Using DALLI-E 3 for Image Generation

## Today's Progress

Integrated DALL-E 3 into my project using Axios for API requests. Used Assistants API playground.

## Thoughts

While the outcomes vary, the process of exploring AI's creative capabilities is consistently intriguing and enjoyable.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git](https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 5: May 1, 2024

# Day 5 of 100 Days of Code: Using AI and Node to Transcribe Audio

## Today's Progress

Today was all about setting up a backend using Node.js. I installed essential packages like dotenv for managing environment variables, axios for making HTTP requests, and form-data for handling form submissions. I also created an .env file to securely store my API key, transitioning from inputting it directly in the terminal—a practice I'm accustomed to and find secure.

The journey wasn’t without its hurdles; I spent a significant portion troubleshooting. At the end, I discovered a couple of bugs—one due to a misspelled variable and another from using the incorrect built-in function.

## Thoughts

The process of debugging and troubleshooting is often more time-consuming than writing the code itself, but it is just as crucial for the development process. Today's session reinforced the importance of attention to detail and the value of a good debugging strategy.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git](https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 4: Apr 30, 2024

# Day 4 of My 100 Days of Code: Venturing into AI with JavaScript

## Today's Progress

Incorporating external APIs, allowing my application to interact dynamically with other services. I implemented a feature using 'readline' to accept user inputs, which has made the interaction more engaging.

One of the highlights of today was creating a function that generates descriptions for images based on their URLs — a fantastic way to merge vision and language models. Additionally, I ventured into audio by recording an MP3 file and successfully transcribing the audio using OpenAI's capabilities through a curl request, demonstrating the versatility of AI in handling various media types.

## Thoughts

Today seemed pretty easy, but long. The ability to transcribe audio and describe images has opened up new possibilities for feature development in my project.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git](https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 3: Apr 29, 2024

# Day 3 of My 100 Days of Code: Venturing into AI with JavaScript

## Today's Progress

I started by generating an API key and setting up a language model to begin crafting AI-driven interactions. I wrote functions to handle AI responses and set up a GitHub repository to track my project. However, I encountered some hurdles with API key permissions and billing issues, which I managed to resolve after some troubleshooting.

I experimented with streams and creating dynamic prompts, and spent some time refactoring my functions to make them cleaner and more efficient. Additionally, I set up templates and customized questions to make the AI interactions more engaging and user-specific.

## Thoughts

Working through the API key and billing challenges was a bit tricky.

## Looking Ahead

Tomorrow, I'll start incorporating external APIs into my project to enhance the functionality and responsiveness of the AI.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git](https://github.com/Jason-Hargrove/ai-programming-for-javascript-developers.git)

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#GitHub \#WebDevelopment \#CodingChallenge \#MachineLearning

<hr style="border-width: 3px;">

### Day 2: Apr 28, 2024

# Day 2 of My 100 Days of Code: Venturing into AI with JavaScript

## Introduction

Diving into "AI Programming for JavaScript Developers" on LinkedIn Learning.

## Today's Progress

I began by exploring AI in the JavaScript ecosystem, understanding how JavaScript developers can leverage AI technologies. I set up my development environment, installed the OpenAI library.

## Thoughts

The setup went smoothly. Tomorrow, I'll add my API key and begin interacting with AI models directly from my code.

## Hashtags

\#100DaysOfCode \#AIProgramming \#JavaScript \#OpenAI \#LinkedInLearning \#WebDevelopment \#CodingChallenge

<hr style="border-width: 3px;">

### Day 1: Apr 27, 2024

# Day 1 of My 100 Days of Code: Kicking Off with Vue.js, Axios, and GitHub Pages!

## Introduction

Today marks the first day of my 100 Days of Code challenge! I'm excited to sharpen my skills in web development. With this project I focused on Vue.js, Axios for API handling, and deployed to GitHub Pages. My journey began when a friend needing help with his computer science homework, and wanted to introduce him to peer programming.

## Today's Progress

I initiated a Vue.js project where my main task was to integrate Axios to fetch JSON data. I successfully pulled in a dataset and implemented filtering logic to manage the data displayed in a user-friendly table format. This involved configuring Bootstrap for the UI to ensure the application looks appealing.

## Thoughts

Working through the initial configurations and integrations posed a good challenge, particularly around handling asynchronous data fetching and rendering it effectively. Overcoming these challenges with Axios and Vue.js filters boosted my confidence and deepened my understanding of frontend development.

## Link to Work

Repo: [https://github.com/Jason-Hargrove/vue-axios-app.git](https://github.com/Jason-Hargrove/vue-axios-app.git)

Visit site: [https://jason-hargrove.github.io/vue-axios-app/](https://jason-hargrove.github.io/vue-axios-app/)

## Hashtags

\#100DaysOfCode \#VueJS \#Axios \#GitHubPages \#WebDevelopment \#CodingChallenge
