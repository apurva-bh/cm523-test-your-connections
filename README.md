# Test Your Connections

In this assignment, you'll learn how to use GitHub, and we'll test your connections.

## Prerequisites
- GitHub Desktop is installed.
- GitHub is connected to GitHub Desktop.

## Requirements to Complete This Assignment
- [ ] You've installed GitHub Desktop, connected it to GitHub, and installed your development dependencies.
- [ ] You've added the words "I did it!" to the `h1` tag inside the HTML file using VSCode (hint: make sure this is _exactly_ what you write inside the `h1` tag)
- [ ] You've pushed your changes to GitHub using GitHub Desktop
- [ ] You've found your changes on GitHub, and learned what feedback will look like!

## First: What is Github?

**GitHub** is a service that makes it easy to use a **version control** system called **Git**. In development, version control helps you track changes to your code, collaborate, and share code with other people. If you've ever worked with the History palette in Photoshop, or made a new copy of a file, GitHub works similarly. It’s used across the software world and beyond to collaborate and maintain the history of projects. 

GitHub is home to some of the most advanced technologies in the world. Whether you're visualizing data or building a new game, there's a whole community and set of tools on GitHub that can get you to the next step. Today, we'll learn how to **clone** a **repository** from GitHub onto your computer, make and save a change, **commit** the change, and then **push** it back to GitHub so I can see your changes and grade them.

### New terms

- **Version control:** A way to track changes to your code.
- **Git:** The version control system that GitHub is built on.
- **GitHub:** An online coding community that makes it easy to use Git.
- **Repository:** A place where your project work happens. Think of it like a project folder on your computer.
- **Clone:** A way to make a copy of what's on GitHub show up on your computer. Think of it as similar to downloading the code, except you'll be able to see when there are differences between the code that you have on your computer, and the code that is on GitHub.
- **Commit:** A piece of work you or someone else has done. Think of it like saving your work. 
- **Push:** A way to sync commits from your local repository to the GitHub repository. Think of it like hitting a sync button.

## Instructions

Let's see how GitHub will work in our class, and make sure we have everything set up correctly. If you run into a problem, don't worry! We'll troubleshoot it together in our first class.

Here's what you'll be doing, step by step:
- [Clone this repository and find it on your computer](#clone-this-repository-and-find-it-on-your-computer)
- [Open the folder in VSCode, and make a change to the HTML](#open-the-folder-in-vscode-and-make-a-change-to-the-html)
- [Preview your changes](#preview-your-changes)
- [Commit and push your changes to GitHub](#commit-and-push-your-changes-to-github)
- [Find your changes on GitHub](#find-your-changes-on-github)
- [Turn in this assignment in on Blackboard](#turn-in-this-assignment-in-on-blackboard)

### Clone this repository and find it on your computer

| Step | Screenshot |
| --- | --- |
| Use the "Open with Github Desktop" button to open this repository in GitHub Desktop. | <img width="1904" alt="Screen Shot 2021-08-23 at 6 22 10 PM" src="https://user-images.githubusercontent.com/1828613/130527013-54c1c211-0bb8-4d56-aba7-38711b3138e0.png"> |
| GitHub Desktop should open, and your assignment will be in the top dropdown under "Current Repository". | <img width="592" alt="Screen Shot 2021-08-23 at 6 25 26 PM" src="https://github.com/ProfessorKolodziej/cm523-test-your-connections/assets/1828613/b8339c27-90e2-487d-ad06-96d1a70aa235"> |
| On the screen that appears, right click Current Repository, then select **Reveal in Finder** to show the location of the folder on your computer. | <img width="1185" alt="Screen Shot 2021-08-23 at 6 32 22 PM" src="https://github.com/ProfessorKolodziej/cm523-test-your-connections/assets/1828613/dd444a41-93f2-4a8e-8c11-45e9f9b8541c"> |

### Open the folder in VSCode, and make a change to the HTML

| Step | Screenshot |
| --- | --- |
| Drag and drop the folder from the window that appears into VSCode. | <img width="1118" alt="Screen Shot 2021-08-23 at 6 36 48 PM" src="https://github.com/ProfessorKolodziej/cm523-test-your-connections/assets/1828613/f4fd3e35-9549-40ab-a475-f505a182b3ce"> |
| When VSCode opens, you will see your folder as well as the welcome screen. Take a moment to familiarize yourself with the folder. You can also close the welcome screen by hitting the "x" next to Welcome in Open Editors. | <img width="2160" alt="Screen Shot 2021-08-28 at 6 57 02 PM" src="https://user-images.githubusercontent.com/1828613/131233047-e444d4c2-c301-4605-90dc-48e6217f63b3.png"> |
| Navigate to the HTML file by clicking `src`, then `index.html`. This is where you will work on all projects. <br/><br/> Change the text inside the `<h1>` tag to say "I did it!", and then save the file. | <img width="2160" alt="Screen Shot 2021-08-28 at 7 11 21 PM" src="https://user-images.githubusercontent.com/1828613/131233231-69a492d5-cd16-4d9b-9029-301e5abcd8ae.png"> |

### Preview your changes

The most basic way to preview an HTML file is to open it in a web browser. We'll learn an easier way to do this in class soon, but for right now, let's stick with the basics.

| Step | Screenshot |
| --- | --- |
| Start by finding the file on your computer. The easiet way to do this in VSCode is to right click (or command click) a file, and then select "Reveal in Finder". | <img width="2046" alt="Screen Shot 2021-08-28 at 7 19 50 PM" src="https://user-images.githubusercontent.com/1828613/131233409-2ec59970-2051-47a3-8096-c324fcd310c5.png"> |
| This will bring up a window with the file highlighted. Double click it to open it in your default browser. I prefer Firefox, and will be teaching using that. You can also use Chrome if you like. **Do not use Safari** because the debugging tools are harder to find and use. | <img width="882" alt="Screen Shot 2021-08-28 at 7 23 48 PM" src="https://user-images.githubusercontent.com/1828613/131233380-92ed7b9d-0efe-4fbe-8166-f77069879224.png"> |
| If all goes well, you should see your changes! Make sure that you see the words "I did it!" when you open this file. If you do, keep going. If not, check that you saved your work in VSCode. | <img width="2160" alt="Screen Shot 2021-08-28 at 7 26 33 PM" src="https://user-images.githubusercontent.com/1828613/131233451-bc3aa197-1dba-4447-94e7-f2c9e4bceb58.png"> |

### Commit and push your changes to GitHub

| Step | Screenshot |
| --- | --- |
| Open GitHub Desktop, and notice how the file you changed is now showing in the Changes tab, with a checkmark by it. You can also see a preview of the changes that were made in the right. Red means deleted, while green means added. When they are together, it means something has been edited. | ![image9](https://github.com/ProfessorKolodziej/cm523-test-your-connections/assets/1828613/07ed9b2c-eda5-4148-a678-836257076e04) | 
| We track versions of files together by creating a **commit**. Add a **commit message** for your commit in the first field - something that will help you remember what these changes were. For example, later on, you might put something in this field like "Style the homepage". Once you are done, click "Commit to main". You do not need a description for commits in this class. | ![image9](https://github.com/ProfessorKolodziej/cm523-test-your-connections/assets/1828613/8d14b44b-855d-4fb7-b33a-e5d921393d26) | 
| Your changes will "disappear". Don't panic - they're still there! You can see they are because now there will be a small arrow with a number. You can also go to the History tab and see the commit you just made. | ![image6](https://github.com/ProfessorKolodziej/cm523-test-your-connections/assets/1828613/cfbacaf2-28b5-4bfc-9d91-47abb004a2ee) | 
| Now is a good time to practice editing and undoing. Navigate to the History tab and find your change. Try right clicking on it and selecting Undo Commit. You will see your working copy again, and a change to change the commit (and the code in the file) if you like. You can do this at any time. Since we don't actually need any code changes, you can edit your commit message if you like, and hit "Commit to main" one more time. | ![image6](https://github.com/ProfessorKolodziej/cm523-test-your-connections/assets/1828613/a3100e54-0e46-4e5e-8e34-ac6e527d0583) | 
| Finally, click "Push Origin". <br><br>The small arrow and number will disappear. This is how you know the changes made it up to GitHub. There are no new changes to send! | <img width="1527" alt="Screen Shot 2021-08-28 at 7 40 44 PM" src="https://github.com/ProfessorKolodziej/cm523-test-your-connections/assets/1828613/6cbbcec0-0c37-4544-90ea-e38574ab2159"> | 

### Find your changes on GitHub

| Step | Screenshot |
| --- | --- |
| Now that the changes are on GitHub, let's go back and see them. Refresh this page and check out the top of the page. Your commit will now be at the top of the code tab! | <img width="1703" alt="Screen Shot 2021-08-28 at 7 45 17 PM" src="https://user-images.githubusercontent.com/1828613/131233702-67b9d488-3422-4e9b-83a8-dc1868ad5145.png"> | 
| There are other tabs in GitHub too. The one we'll use the most is the Pull Requests tab. This is where you'll find feedback on your code. Click "Pull Requests" to see an example pull request. | <img width="1700" alt="Screen Shot 2021-08-28 at 7 48 22 PM" src="https://user-images.githubusercontent.com/1828613/131233729-6565c0cc-508f-4922-bc9a-18891e6d123d.png"> | 
| To start, GitHub will create a pull request for you. Eventually, you'll learn to do this too! For now, just click on "Feedback". | <img width="1714" alt="Screen Shot 2021-08-28 at 7 50 39 PM" src="https://user-images.githubusercontent.com/1828613/131233770-834ae079-5ec5-4374-a60d-100cb0e112a0.png"> | 
| On the feedback screen, click on "Files changed". This is where you'll eventually see feedback from me next to your code changes! For now, you won't see anything. **Copy the link to this pull request page from your browser for the next step.** | <img width="1701" alt="Screen Shot 2021-08-28 at 7 55 38 PM" src="https://user-images.githubusercontent.com/1828613/131233849-8ddc64a9-7ce5-4138-b156-ca2fbbbecf93.png"> | 

### Turn in this assignment in on Blackboard

Now that you've found your pull request, send me a link to it on Blackboard (the same way you started this assignment!) to get it in my grading pile and complete the assignment. 

**Congratulations - you've made your first steps in modern web development!** 🎉 This may feel like a lot now, but this process will become second nature in no time and you'll have lots of opportunities to practice these steps in this class. Be patient and keep at it, and take notes as you go to help you remember the steps. With each assignment, I'll condense steps you've already been through a little more so you have a chance to rely on your memory, and can really focus on the new pieces you're learning. By the time we get to the midterm, you'll be a pro at this - and you'll be ready to start collaborating with your classmates on code for the final project!
