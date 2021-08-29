# Test Your Connections

In this assignment, you'll learn how to use Github, and we'll test your connections.

## Prerequisites
- Tower is installed.
- GitHub is connected to Tower.

## Requirements to Complete This Assignment
- [ ] You've installed Tower, connected it to GitHub, and installed your development dependencies.
- [ ] You've added the words "I did it!" to the `h1` tag inside the HTML file using VSCode (hint: make sure this is _exactly_ what you write inside the `h1` tag)
- [ ] You've pushed your changes to GitHub using Tower
- [ ] You've found your changes on GitHub, and learned what feedback will look like!

## First: What is Github?

GitHub is a service that makes it easy to use a **version control** system called **Git**. In development, version control helps you track changes to your code, collaborate, and share code with other people. If you've ever worked with the History palette in Photoshop, or made a new copy of a file, GitHub works similarly. It’s used across the software world and beyond to collaborate and maintain the history of projects. 

GitHub is home to some of the most advanced technologies in the world. Whether you're visualizing data or building a new game, there's a whole community and set of tools on GitHub that can get you to the next step. Today, we'll learn how to **clone** a **repository** from GitHub onto your computer, make and save a change, **commit** the change, and then **push** it back to GitHub so I can see your changes and grade them.

### New terms

- **Version control:** A way to track changes to your code.
- **Git:** The version control system that GitHub is built on.
- **GitHub:** An online coding community that makes it easy to use Git.
- **Repository:** A place where your project work happens. Think of it like a project folder on your computer.
- **Clone:** A way to make a copy of what's on GitHub show up on your computer. Think of it as similar to downloading the code, except you'll see a 
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
| Use the "Open with Github Desktop" button to open this repository in Tower. | <img width="1904" alt="Screen Shot 2021-08-23 at 6 22 10 PM" src="https://user-images.githubusercontent.com/1828613/130527013-54c1c211-0bb8-4d56-aba7-38711b3138e0.png"> |
| This is what the window will look like. Hit **Clone**. | <img width="592" alt="Screen Shot 2021-08-23 at 6 25 26 PM" src="https://user-images.githubusercontent.com/1828613/130527312-6a07dcd0-afc6-4910-b43c-49b49bb7f256.png"> |
| In Tower, click Repositories, then select your repository, then click "Open". | <img width="1293" alt="Screen Shot 2021-08-23 at 6 29 57 PM" src="https://user-images.githubusercontent.com/1828613/130527732-09a74cc6-cd83-4a04-9758-99273dc3334c.png"> |
| On the screen that appears, right click Working Copy, then select **Reveal in Finder** to show the location of the folder on your computer. | <img width="1185" alt="Screen Shot 2021-08-23 at 6 32 22 PM" src="https://user-images.githubusercontent.com/1828613/130527956-551ec249-23f4-45d1-9613-a2cf446410e7.png"> |

### Open the folder in VSCode, and make a change to the HTML

| Step | Screenshot |
| --- | --- |
| Drag and drop the folder from the window that appears into VSCode. | <img width="1118" alt="Screen Shot 2021-08-23 at 6 36 48 PM" src="https://user-images.githubusercontent.com/1828613/130528628-d195d32e-68fe-4909-9c68-2c0489859d6a.png"> |
| When VSCode opens, you will see your folder as well as the welcome screen. Take a moment to familiarize yourself with the folder. You can also close the welcome screen by hitting the "x" next to Welcome in Open Editors. | <img width="2160" alt="Screen Shot 2021-08-28 at 6 57 02 PM" src="https://user-images.githubusercontent.com/1828613/131233047-e444d4c2-c301-4605-90dc-48e6217f63b3.png"> |
| Navigate to the HTML file by clicking `src`, then `index.html`. This is where you will work on all projects. <br/><br/> Change the text inside the `<h1>` tag to say "I did it!", and then save the file. | <img width="2160" alt="Screen Shot 2021-08-28 at 7 11 21 PM" src="https://user-images.githubusercontent.com/1828613/131233231-69a492d5-cd16-4d9b-9029-301e5abcd8ae.png"> |

### Preview your changes

The most basic way to preview an HTML file is to open it in a web browser. We'll learn an easier way to do this in class soon, but for right now, let's stick with the basics.

| Step | Screenshot |
| --- | --- |
| Start by finding the file on your computer. The easiet way to do this in VSCode is to right click (or command click) a file, and then select "Reveal in Finder". | <img width="2046" alt="Screen Shot 2021-08-28 at 7 19 50 PM" src="https://user-images.githubusercontent.com/1828613/131233409-2ec59970-2051-47a3-8096-c324fcd310c5.png"> |
| This will bring up a window with the file highlighted. Double click it to open it in your default browser. I prefer Firefox, and will be teaching using that. You can also use Chrome if you like. I don't recommend Safari because the debugging tools are harder to find and use. | <img width="882" alt="Screen Shot 2021-08-28 at 7 23 48 PM" src="https://user-images.githubusercontent.com/1828613/131233380-92ed7b9d-0efe-4fbe-8166-f77069879224.png"> |
| If all goes well, you should see your changes! Make sure that you see the words "I did it!" when you open this file. If you do, keep going. If not, check that you saved your work in VSCode. | <img width="2160" alt="Screen Shot 2021-08-28 at 7 26 33 PM" src="https://user-images.githubusercontent.com/1828613/131233451-bc3aa197-1dba-4447-94e7-f2c9e4bceb58.png"> |

### Commit and push your changes to GitHub

| Step | Screenshot |
| --- | --- |
| Open Tower, and make sure you are in your Repository view, and that you've clicked "Working Copy". <ol><li>Click “Stage All”</li><li>Write a commit message in the Commit Subject area. Keep it short and descriptive of the changes you made.</li><li>Hit “Commit”. This creates a **commit**, and your changes will “disappear”.</li></ol> | ![image9](https://user-images.githubusercontent.com/1828613/130551912-d3ffbeca-089d-4311-a2de-d82258eb9676.png) | 
| This is what that "disappearing" will look like. Don't panic, your changes are still there! You can see they are because now there will be a small arrow with a number. This is how many changes you will be pushing. It's time to **push** your changes. Click the small up arrow to push your changes to GitHub. | ![image6](https://user-images.githubusercontent.com/1828613/130552156-9fd93037-8f3d-479f-a314-40e1d18ee5f8.png) | 
| Tower will ask you to confirm some settings. Leave them at the default and click "Push HEAD". <br><br>The small arrow and number will disappear. This is how you know the changes made it up to GitHub. There are no new changes to send! | <img width="1527" alt="Screen Shot 2021-08-28 at 7 40 44 PM" src="https://user-images.githubusercontent.com/1828613/131233610-2619d900-50f0-4b0f-899a-741d8fb088a6.png"> | 

### Find your changes on GitHub

| Step | Screenshot |
| --- | --- |
| Now that the changes are on GitHub, let's go back and see them. Refresh this page and check out the top of the page. Your commit will now be at the top of the code tab! | <img width="1703" alt="Screen Shot 2021-08-28 at 7 45 17 PM" src="https://user-images.githubusercontent.com/1828613/131233702-67b9d488-3422-4e9b-83a8-dc1868ad5145.png"> | 
| There are other tabs in GitHub too. The one we'll use the most is the Pull Requests tab. This is where you'll find feedback on your code. Click "Pull Requests" to see an example pull request. | <img width="1700" alt="Screen Shot 2021-08-28 at 7 48 22 PM" src="https://user-images.githubusercontent.com/1828613/131233729-6565c0cc-508f-4922-bc9a-18891e6d123d.png"> | 
| To start, GitHub will create a pull request for you. Eventually, you'll learn to do this too! For now, just click on "Feedback". | <img width="1714" alt="Screen Shot 2021-08-28 at 7 50 39 PM" src="https://user-images.githubusercontent.com/1828613/131233770-834ae079-5ec5-4374-a60d-100cb0e112a0.png"> | 
| On the feedback screen, click on "Files changed". This is where you'll eventually see feedback from me next to your code changes! For now, you won't see anything. | <img width="1701" alt="Screen Shot 2021-08-28 at 7 55 38 PM" src="https://user-images.githubusercontent.com/1828613/131233849-8ddc64a9-7ce5-4138-b156-ca2fbbbecf93.png"> | 

### Turn in this assignment in on Blackboard

Now that you've found your pull request, send me a link to it on Blackboard (the same way you started this assignment!) to get it in my grading pile and complete the assignment. 

**Congratulations - you've made your first steps in modern web development!** 🎉 This may feel like a lot now, but this process will become second nature in no time and you'll have lots of opportunities to practice these steps in this class. Be patient and keep at it, and take notes as you go to help you remember the steps. With each assignment, I'll condense steps you've already been through a little more so you have a chance to rely on your memory, and can really focus on the new pieces you're learning. By the time we get to the midterm, you'll be a pro at this - and you'll be ready to start collaborating with your classmates on code for the final project!
