# Opening A Lab

There's a little bit of work you have to do to get a lab from Learn intro Nitrous so we can start working!

For this walk-through, we'll be using the `HTML Playground` Lab. These steps will work for whatever lab or lesson you're trying to work on.

###Step 1:

In Learn, select the lab and then select `Open in Nitrous`:

<img src="https://s3.amazonaws.com/after-school-assets/open-in-nitrous.png">


### Step 2:

That will automatically open Nitrous for you. You will have the lab saved in Nitrous, and will place you in Terminal in that lab directory.

You can find the lab in the file navigator `nitrous < code < labs < html-playground`.

To open the files to edit them, you can use the file navigator, by double clicking on a file and it will open in the text editor.

### Step 3:

If you're working in HTML and/or CSS you'll want to have your HTML and CSS files open in the text editor, as well as the HTML files open in the browser. When you're writing HTML for a website, you don't expect your user to actually open a text editor and look at the code that makes up the website. They want to actually view the website in the browser. In fact, most people probably don't even want to think about the code that makes up the website. In order to view our HTML file, which is the text of your website, in the browser, you have to start a server. A server is basically a computer that continually runs the code you wrote so that people can view our site. Because our sites are still a work in progress, this server won't permanently host our site. It won't give us a URL to send to our friends, but it will let us view the fruits of our labor like it is a real site. To view your code in the browser, in terminal in Nitrous, enter:

```
python -m SimpleHTTPServer 3000
```

This command starts up a server automatically for you so you can view the website. Once you have the server running, select `preview` and then `port 3000`, just like in the image below.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-preview.png" alt="nitrous preview">

### Step 4

This little server we just started is just a test server so that you can write HTML and see what it looks like in the browser. It hasn't permanently hosted your site so that other people can visit it.

It's important to note that this server is just for testing purposes, which means when you're done testing you should stop the server. If you don't, you won't be able to use your terminal. (Try entering some terminal commands you're familiar with in the terminal while your server is running. You'll notice that you can type in the terminal, but nothing happens.)

To stop your server once you're done testing, you can just hit `control` and `c`. This will work on both Mac's and PC's. 

If in the event that you finish a lesson or lab and don't stop your server, you won't be able start a server in another lab. Just close the original Nitrous window in the browser and you'll be good to go.

If you would like to start your server back up again, you just simply enter:

```
python -m SimpleHTTPServer 3000

``` 

### Step 5
Once you're done with your work, in Nitrous, in terminal, in the main directory of your lab, you'll want to enter: `learn submit`. This command will push your code up to your GitHub account, and is a great way to build your developer portfolio. You can go to your GitHub profile and check out your repositories. You should see the lab there!

This command will also mark a lab as complete in learn. You should see the `PULL REQUEST` light turn green in the right hand column!
