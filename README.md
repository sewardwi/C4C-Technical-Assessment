# C4C-Technical-Assessment
My name is William Seward, and this is for the C4C Application Technical Assessment Spring 2024.

**Here are the instructions for running the message board program:**

1. First, go to https://nodejs.org/en and download the version of Node.js that is the best for your computer. This will help in running the server. 

2. Second, create a new directory in your file system for the project. Make sure that the directory is in a place that is easily accessible because we will come back to it for two things: 1. to add the files from this repository to run the server, 2. to start the server from the Terminal (Linux/Mac) or Windows PowerShell (Windows).
  
3. Third, add the files from this GitHub repository to the newly-made project directory in your file system. This can be through downloading the files into your "Downloads" folder/directory in your computer. Another way is to make the two blank files in your system and copy the code over; if you do this way make sure to name the files "index.html" and "server.js" respectively and copy the correct code into each of them. 

4. Fourth, access the directory through the command line in the following steps:
      - Open either the Terminal application on Linux/Mac or through the Windows PowerShell on Windows. If you are on Windows, make sure to click "Run as Administrator" to open the Windows PowerShell application so it can makes changes to your file system.
      - Navigate to the project directory using commands such as "cd" with the specified path to your directory.

5. Fifth, initialize the npm and create the "package.json" files. Once you are in your project directory from the Terminal/PowerShell, run the following command from the Terminal/PowerShell: ```npm init -y```. Now you should see some new files in the project directory such as "package.json" and "package-lock.json".

6. Sixth, use npm to install Socket.io for your project. Still from inside the project directory from the Terminal/PowerShell, run the following command from the Terminal/PowerShell: ```npm install socket.io```. This installs Socket.io which will make the server run.

7. Seventh, use npm to install Express. Also from inside the project directory from the Terminal/PowerShell, run the following command from the Terminal/PowerShell: ```npm install express```. Express is the framework for Node.js, which is running the server on your computer.

8. Eighth, start the server from the command line. This is the last command to run from the Terminal/PowerShell! Still from inside your project directory from the Terminal/PowerShell, run the following command from the Terminal/PowerShell: ```node server.js```. This will call upon the "server.js" file that you downloaded from this GitHub repository and start running the server from your computer! In the Terminal/PowerShell, you should see the message "Server Running on Port 3000". This will indicate that the server is successfully running.

9. Ninth and finally, access the server from your browser. Copy and paste the following url into your browser window: **http://localhost:3000**. This should bring you to the webpage where you can access the message board and type in what you want!


Thank you for taking the time to consider me for a developer role at Code4Community! I really look forward to the possibility of joining such an impactful group here at Northeastern and apply my technical skills outside of the classroom to help real people! Have a nice day!


**Debugging/Errors:**
If there are any errors in running the program, here are a few websites I found to be helpful:

- Error: after copy-pasting the link into your browser you just see "Cannot GET/": https://stackoverflow.com/questions/21317981/cannot-get-nodejs-error
- Error: cannot find module "Express": https://stackoverflow.com/questions/14949118/node-js-error-cannot-find-module-express

**Design Process:**
I also want talk a little bit about the design process/what I found particularly challenging and interesting. I come into this with very little experience in HTML/CSS/JS. The practice I do have is through the NER Software Team, but that was very little and largely just focused on completing the assigned tickets. Thus, this is the first time where I have had to make a project fully in HTML/CSS/JS from scratch, and I thoroughly enjoyed it. The hardest parts were getting started initially and learning the syntax and the way the languages flow and intertwine with one another, and figuring out how to make local server, as it was the first time I have done that. I definitely learned a lot from this experience and I definitely had some fun along the way!

