# My Contacts
## A mobile-first application for storing contact information and notes.

### What is this?
This is a web application designed to run on your phone.  With this app, you may add new contacts to a contact list, then call them from the application itself by selecting the name of the contact in the list.  [Try it for yourself](https://slothwerks-studio.github.io/contact-list/)!

### Why did you build this?
This public repository was built to teach the basic fundamentals of using HTML, CSS, and JavaScript to create an interactive web application.

### How do I check out the code?

#### File download
The easiest method is to simply download the files to your computer.

- Click on the code download button on this repo and select Download ZIP.
- Save the ZIP package to the desktop of your computer.
- Once downloaded, [extract the files](https://www.sweetwater.com/sweetcare/articles/how-to-zip-and-unzip-files/) to your desktop.  This should create a new folder called `contact-list-main`, but you can rename it to whatever you like.

#### Forking the repository
It's lovely to play with the code on your own machine.  But let's say you'd like to share your code updates.  What then?

[Forking a repository](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) creates a copy of the repo within your personal GitHub account.  This allows you to take advantage of revision history, code collaboration, and the many other benefits of using [git](https://git-scm.com/).  You may also make a request to the original repo owner to add updates from your copy of the repo.

So...

- If you have not already done so, [create an account on GitHub](https://github.com/join).  It's free!
- After creating an account, come back to this repo and click the "Fork" button at the top-right corner (just beneath the navigation bar).
- GitHub will make a copy of the repo, then re-direct you to your fork of `contact-list`.
- Next, [clone the code](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) in order to access it on your local machine.

When working with git, you'll want to get comfortable using a terminal program such as [zsh for Mac](https://www.howtogeek.com/682770/how-to-open-the-terminal-on-a-mac/) or [PowerShell for Windows](https://www.howtogeek.com/662611/9-ways-to-open-powershell-in-windows-10/).  This will allow you to run the commands necessary to complete the above steps.

Git itself is a software that you'll need to [download and install](https://git-scm.com/downloads) in order to perform git commands within the terminal.  Once git is installed, you will also want to [set up authentication for GitHub](https://docs.github.com/en/github/getting-started-with-github/set-up-git) in order to interact with your GitHub account from the terminal.

(Looking for help with this?  Sloth led us through an intoduction to git in a previous workshop; [the video of his presentation is available on Facebook](https://www.facebook.com/182139175163955/videos/852495475371824).)

### How do I play with the code on my own computer?
Well, you'll want to install a nifty programming application such as [Visual Studio Code](https://code.visualstudio.com/).

- [Download VS Code](https://code.visualstudio.com/download).
- Once installed, open the software.  Go to View > Extensions.
- In the extensions search bar, type "Live Server".  Select the Live Server extension by Ritwick Day in the results (it should be the top result).
- Click on the Install button.  Once installed, close VS Code and open it again.
- Go to File > Open Folder (Windows) or File > Open (Mac) and select the folder containing the project files.
- Once loaded, at the very bottom-right of the VS Code window you should see an option that says "Go Live".  Click on this; a new tab should appear in your browser with the application running.
- If you make changes to any of the project files, select File > Save.  The application should automatically reload within the browser, allowing you to access your changes immediately.

### Why isn't this an app that uses, say, Angular, Vue, or React?
Oh, but it IS!  The "reactified" version of the app is in a [separate branch](https://github.com/slothwerks-studio/contact-list/tree/react-app) and you can fire it up locally on your machine.  But this requires several additional steps.

#### 1. Install the necessary software
The [React](https://reactjs.org/) version of the app was building using [Create React App](https://github.com/facebook/create-react-app).  You'll need to install [Node.js](https://nodejs.org/en/) and then add [Yarn](https://yarnpkg.com/) as a package manager.  Yarn makes this easy with its [step-by-step installation instructions](https://yarnpkg.com/getting-started/install).

#### 2. Install the necessary packages
Yarn makes this super-easy.  Just execute `yarn` from the command line in the root of this repo.  (It's the folder that contains `package.json`).  Yarn will install the necessary packages for the project and create a `node_modules` folder.

#### 3. Fire up the local development server
Once you've installed the packages from the root directory, execute `yarn start` from the command line.  Once the server is up and running, you can access a live preview at [http://localhost:3000](http://localhost:3000).  Similar to Live Server in Visual Studio Code, anytime you make changes to the project, the server will reload and reflect those changes.

#### 4. Build a production version of the app
You can execute `yarn build` to create a version of the app that can be viewed in the browser without the use of the live server.  Just open the `index.html` file within the resulting `build` folder once the building process is complete.

### I know a little HTML and CSS, but I don't know anything about JavaScript.  Help!
We got your back!  Sloth discussed the basic concepts of JavaScript and walked through the initial code at [GRWebDev](https://www.meetup.com/grwebdev/) in March of 2021.  You can check out the [video of his presentation](https://www.facebook.com/182139175163955/videos/455547239117005) on Facebook.  We will continue to work on the code throughout a number of events sponsored by GRWebDev and [SlothWerks](https://slothwerks.com/).

### This application seems kinda lame.
Well, you should work with us to make updates to it!  Join Sloth and fellow creatives in West Michigan as we work together to add features and improve the application.  You can check out the latest "Code with Sloth" workshops on [GRWebDev's Meetup page](https://www.meetup.com/grwebdev/).  A [public Trello board](https://trello.com/b/0TmiXJ08/contact-list-app) is available with future topics and planned updates to the app; you can also check out the existing [version history](https://github.com/slothwerks-studio/contact-list/wiki/Version-History) in the repo [wiki](https://github.com/slothwerks-studio/contact-list/wiki).  Join us on the [SlothWerks Slack workgroup](https://join.slack.com/t/slothwerks-studio/shared_invite/zt-6l4946k3-EnOTGy0NAGC664dV7LGynA) for community discussions in the #contact-list-dev channel!

### Our development team...
| Name | GitHub | LinkedIn |
| ---- | ------ | -------- |
| Sloth I | [slothwerks-studio](https://github.com/slothwerks-studio) | [www.linkedin.com/in/slothwerks/](https://www.linkedin.com/in/slothwerks/) |
| Mark Haines | [hainesma](https://github.com/hainesma) | [www.linkedin.com/in/hainesma/](https://www.linkedin.com/in/hainesma/) |
| Kate Datema | [KateDatema](https://github.com/KateDatema) | [www.linkedin.com/in/kate-katelyn-datema-04583772/](https://www.linkedin.com/in/kate-katelyn-datema-04583772/) |

### Hold up.  How did you build that cool-looking table?
It's called `markdown`, y'all.  Check out [Adam Pritchard's markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet); it's awesome!
