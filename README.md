# Opening A Lab

There's a little bit of work you have to do to get a lab from Learn.co intro Nitrous so we can start working!

###Step 1:

In Learn.co, view the lab you would like to be working on. All labs are noted with `Lab` before their name. If you're going through the Week One material, the lab would `HTML Playground`. In other weeks, the labs might be different. Click on `View On Github` in the top left corner:

<img src="https://s3.amazonaws.com/after-school-assets/view-on-github.png">


###Step 2:

This will load the lab on Flatiron School's Github. Next, you need this lab to be on your own Github account. Click the `Fork` button in the top right corner:

<img src="https://s3.amazonaws.com/after-school-assets/lab-on-github.png">

The fork button makes a photocopy of the original copy of the lab (Flatiron School's copy). It's just like when you're teacher photocopies a handout for you to work on. She doesn't give you her original copy, because then that would have the answers! 

### Step 3:

Next you will be prompted for where you want to fork this lab. You'll want to select your own account. This is like the teacher handing you a photocopy of an assignment.

<img src="https://s3.amazonaws.com/after-school-assets/fork-to-account.png" alt="select your own account">


### Step 4:

This will photocopy the lab to your own Github account. You should see  your Github username in the top left corner in front of the lab name:

<img src="https://s3.amazonaws.com/after-school-assets/forked.png">

### Step 5:

Just because the lab is located on your own Github account, doesn't mean you can start coding yet. You still need to bring this lab from your Github account down to your Nitrous account. 

First, you need to copy the HTTPS URL. You can find that in the right side bar on Github. 

<img src="https://s3.amazonaws.com/after-school-assets/https-clone.png">

You'll want to click on the blue `HTTPS` button, and then copy the URL in the text box.


### Step 6:

Now, you can use this URL to bring the lab from Github to Nitrous.

Next, we need to use our terminal in Nitrous. Terminal is an application that let's us interact with our computer without using Finder. It's basically a way for us to type commands to make new files, directories (more commonly known as folders) and run our code. Don't worry too much about what these commands all mean, we'll get into that later!

For now, in terminal in Nitrous, you'll want to move into your code directory, by entering in terminal `cd code`.

Once you clone the lab, you'll want to enter `git clone PASTE-THE-HTTPS-URL-YOU-COPIED-FROM-GITHUB-HERE-INSTEAD-OF-THIS-TEXT`. Take a look at the image below for an example of how to clone the `Lab: Album Cover`:

<img src="https://s3.amazonaws.com/after-school-assets/git-clone.png">

You will be prompted to enter your Github username, and Github password. When you type your password, you won't see the text show up. Hit enter when you finish. Terminal should spit out a bunch of text, which is the lab being "cloned" or downloaded to Nitrous.

Next, in terminal enter `ls`, which will list all the directories inside the code directory. You want to be inside of the `html-album-cover` directory. 

In terminal, type `cd` and then the full name of the directory and hit enter.

### Step 7

To open the files to edit them, you can use the file navigator on the left side. Double click on a file and it will open in the text editor.

### Step 8

If you're working in HTML and/or CSS you'll want to have your HTML and CSS files open in the text editor, as well as the HTML files open in the browser. When you're writing HTML for a website, you don't expect your user to actually open a text editor and look at the code that makes up the website. They want to actually view the website in the browser. In fact, most people probably don't even want to think about the code that makes up the website. In order to view our HTML file, which is the text of your website, in the browser, you have to start a server. A server is basically a computer that continually runs the code you wrote so that people can view our site. Because our sites are still a work in progress, this server won't permanently host our site. It won't give us a URL to send to our friends, but it will let us view the fruits of our labor like it is a real site. To view your code in the browser, in terminal in Nitrous, enter:

```
python -m SimpleHTTPServer 3000
```

This command starts up a server automatically for you so you can view the website. Once you have the server running, select `preview` and then `port 3000`, just like in the image below.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-preview.png" alt="nitrous preview">

### Step 9

This little server we just started is just a test server so that you can write HTML and see what it looks like in the browser. It hasn't permanently hosted your site so that other people can visit it. To stop your server once you're done testing, you can just hit `control` and `c` at the same time. This will work on both Mac's and PC's. 

If you would like to start your server back up again, you just simply enter:

```
python -m SimpleHTTPServer 3000
``` 
