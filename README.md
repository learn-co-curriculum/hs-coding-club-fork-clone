# Opening A Lab

There's a little bit of work we have to do to get a lab from Learn.co intro Nitrous so we can start working!

###Step 1:

In Learn.co, view the lab. Click on `View On Github` in the top left corner:

<img src="https://s3.amazonaws.com/after-school-assets/view-on-github.png">


###Step 2:

This will load the lab on Flatiron School's Github. Next, you need this lab to be on your own Github account. Click the `Fork` button in the top right corner:

<img src="https://s3.amazonaws.com/after-school-assets/lab-on-github.png">


### Step 3:

Next you will be prompted for where you want to fork this lab. You'll want to select your own account:

<img src="https://s3.amazonaws.com/after-school-assets/fork-to-account.png" alt="select your own account">


### Step 4:

This will load the lab on your Github account. You should see in the top left corner your Github username in front of the lab name:

<img src="https://s3.amazonaws.com/after-school-assets/forked.png">

### Step 5:

We need to bring this lab from your Github profile down to your Nitrous account. 

First, we need to copy the HTTPS URL. You can find that in the right side bar on Github. 

<img src="https://s3.amazonaws.com/after-school-assets/https-clone.png">

You'll want to click on the blue `HTTPS` button, and then copy the URL in the text box.


### Step 6:

Now, we can use this url to bring the lab from Github to Nitrous. In terminal in Nitrous, you'll want to move into your code directory, and then clone the lab.

<img src="https://s3.amazonaws.com/after-school-assets/https-clone.png">

You will be prompted to enter your Github username, and Github password. When you type your password, you won't see the text show up. This will bring the lab down. 

Next, in terminal enter `ls`, which will list all the directories inside the code directory. We want to be inside of the `html-album-cover` directory. 

In terminal, type `cd` and then the full name of the directory and hit enter.

### Step 7

To open the files to edit them, you can use the file navigator on the left side. Double click on a file and it will open in the text editor.

### Step 8

If you're working in HTML and/or CSS you'll want to have your HTML and CSS files open in the text editor, as well as the HTML files open in the browser. To view them in the browser, in terminal in Nitrous, enter:

```
python -m SimpleHTTPServer 3000
```

Once you have the server running, select `preview` and then `port 3000`.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-preview.png" alt="nitrous preview">
