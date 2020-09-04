## Log

### R1D1
I'm starting with data science/machine learning. CSDojo from Youtube recommended [Stanford's Machine Learning](https://www.coursera.org/learn/machine-learning), and I found [IBM's Introduction to Data Science](https://www.coursera.org/specializations/introduction-data-science) (both from coursera).

Also looked up how to structure learning. When do I learn, when do I code?

### R1D2
I spoke with a few people, and it seems like I was mistaken. Data science is heavy on the math, and some roles don't even code much. Not the path for me. 

I like creating effecient solutions, or optimizing existing solutions. I do not care about front end, or design. I guess more on logic. Which means... back end. As I am now comfortable with Python, will be starting with web developer backend route. The other option is creating software (desktop/mobile), but it's a different stack and would set me back.

Also found [a pretty good guide](https://www.educative.io/blog/web-development-in-python#suited) on what technologies are needed to be a web developer.

### R1D3
Met someone who works in Google. He recommended I create a simple chat application using sockets to understand Python more. It would be local to my computer. Looked up a [tutorial](https://realpython.com/python-sockets/) with the [code in github](https://github.com/realpython/materials/tree/master/python-sockets-tutorial) and doing this today.

Started to understand how TCP connections work, client side and server side. Create the socket > bind > listen > connect > accept > send & receive > close. Created a super simple app that just echoes what the client has sent. However, connection terminates after just one line is sent. Want to enhance by being able to send multiple lines.

Tomorrow will continue with the tutorial on handling multiple connections.

### R1D4

It is a challenging concept to grasp, the sockets and selectors are quite foreign. It took a while, but I had a general understanding of the server side, will work on the client side tomorrow. 

### R1D5 

Understood how the client side works, but when I ran the scripts, there was unexpected output. A few print statements later, I still don't quite understand. Especially data.outb, when I try to print it out earlier in the function, it's empty. But it prints out a few lines later - it is not manipulated in between!

### R1D6 (Saturday, 15 August)

Not yet sure why that happens, but I found [a 5-part tutorial series in Youtube](https://www.youtube.com/watch?v=Lbfe3-v7yE0) which makes sockets easier to understand. 

### R1D7

Continued with the tutorial series, this method is more straightforward and easier to understand. He explains well. A new concept to grasp is bytes and encoding/decoding. I am up to the chatroom server bit, significantly more complex than the previous examples.

### R1D8

Re-watched the server portion again, and I understand it more now. Was studying the client portion, but could use more clarity.

### R1D9

Trying to understand how the server and client fit together. Testing the code on my own. Actually, can't focus that much today. Decided to take an off day.

### R1D10 (Wednesday, 19 August)

Actually tested code on my own - and after a bit of debugging, it works! Server is up and running, multiple clients can connect and send messages, which are also seen by the other connected clients. The not-so-good part though is that the client doesn't get messages from the other clients if they themselves do not send a message. I thought it was supposed to update if a client just hits enter. 

### R1D11

Started learning about API's from [FreeCodeCamp's tutorial](https://www.youtube.com/watch?v=GZvSYJDk-us). Started thinking about API's I can play around with - apparently there's [a Harry Potter one](https://www.potterapi.com/)!

### R1D12

Continued with the API tutorial. Implemented COMPLIMENTR's sending an SMS. Flask is not new to me, but I have not mastered it either. It will be good to practice more.

Skipped the Javascript part of the API tutorial, completed the others.

Tinkered with the Harry Potter API, and made a little spells quiz game! Will optimize first before uploading to github.

### R1D13 (Thursday, 27 August)

Had a few days break. I optimized my code a bit more and finished my Harry Potter spell quiz, and uploaded to github! Find it [here](https://github.com/jainnielyn/HP-quiz). 

I am also thinking about creating a web app from this, so it's easier to share with others. I can use Heroku. And I can practice with Jinja/Flask, or something else. 

### R1D14

I realize I was thinking more of a Javascript web app, where the user clicks on an answer, and gets notified if it's right or wrong (versus a Flask/Jinja web app where the the whole page needs to refresh). Looked into JS frameworks, apparently Vue is the easiest to learn despite it not coming with the bells and whistles. However, it's above my skills for now.

Let me try to build it in Flask first. I've only used Flask once ever, so this will be a learning experience.

### R1D15 (Saturday, 29 August)

Following along with FreeCodeCamp's [Flask Tutorial on Youtube](https://www.youtube.com/watch?v=Z1RJmh_OqeA).

Decided to install Ubuntu on my computer for ease of development (and focus!). Spent time on backing up, installing, and setting up the system and software. 

### R1D16

Started on the FCC Flask tutorial. It's to create a simple todo web app, using Flask.

### R1D17 

Completed the tutorial. Uploaded the app as a private repository on github, and also deployed to [heroku](https://flask-todo-app-jc.herokuapp.com/).

It's very simple, but that's what basics are for. Now I have more of a grasp on app routing with Flask, Jinja syntax and some SQL Alchemy. Databases are not new to me, so it wasn't that difficult.

Next project: Turning the Harry Potter spell quiz into a flask web app.

### R1D18 (Tuesday, 1 September)

Ok, I realize the quiz game I want to create should be created using Javascript, which I don't really want to cross at this stage. I want to be more familiar with flask first, and creating flask-based projects. Or really, just projects. I have a few I have not uploaded into github, maybe I can do those. I can optimize and deploy to Heroku as well.

I spent today doing looking up Jr dev portoflios - see what their projects are, how complex... On the portfolio website, each project needs to have a little summary on what it does, hopefully has a live demo site, a link to the github repository, and the live site should have instructions on how to use it.

I also looked up backend project ideas - databases and API's stuck to mind. User authentication, inventory/online shopping website... hey, maybe I can add a login screen to the todo app I did.

### R1D19

Before I go down the rabbit hole of learning XYZ so I can make my ideal project, I'm just going to create something with what I know now. Nevermind it's ugly/basic/not as great as I would like it to be, I can always improve upon it in the future.

I got started with implementing the Spell quiz as a web-based game with flask. Spent an indecent amount of time fiddling with CSS to no avail. For some reason, after I deleted the CSS for the background, it didn't go away and I cannot figure out why.

Started implementing the game proper instead. It's currently just a textbox and button asking for how many questions the user wants to get tested on.

### R1D20

Found out the browser was getting the css from cache (aha!) that's why it wasn't updating. Thank you, internet! So... one option is to clear the cache each time you change your CSS (no way), or hard refresh the page to force it to get the css each time [see wiki] (https://en.wikipedia.org/wiki/Wikipedia:Bypass_your_cache#Google_Chrome).

I also worked on the main page for a bit and got it to how I want it to look like. There's a beautiful wallpaper I found by Jim Kay. The text will be revised further.
![Screenshot of main page](https://github.com/jainnielyn/Progress-log/blob/master/img/day20.PNG?raw=true) 

Accidentally, I uploaded my API key onto github, but there's a handy [tutorial](https://docs.github.com/en/github/authenticating-to-github/removing-sensitive-data-from-a-repository) for it using filter-branch. Not sure if I did it correctly, as my .gitignore now has "config.pyconfig.py"

### R1D21

Worked on the main page so the form looks a bit prettier. The input for number of questions works now.

Was able to connect to the API and retrieve data (the spells). Next is to display them, then check if the answers are correct. Not sure how I want it to display eventually, maybe 3-5 questions per page. I need to make it scrollable, but the background stays put. Then how will I display the results...

### R1D22

### R1D23

### R1D24

### R1D25

### R1D26

### R1D27

### R1D28

### R1D29

### R1D30
