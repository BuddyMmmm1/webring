# webring

A web ring of web pages.

This is a git activity to help us get more git practice.

### Before you start

You need to have created a Github account, and installed Github Desktop on your computer.

### Web Rings

A web ring is a collection of web pages by different people, where each page links to the next. It's a really old internet thing.

We're going to make a web ring where each of us have a page.

### Step 0 - look at the web ring so far

So far it's a lonely webring with only one page.

look:
http://codeclubakl.github.io/webring/matthew.html

### Step 1 - FORK this repository.

In your web browser (i.e. Google Chrome) go to https://github.com/codeclubakl/webring

Click 'Fork' (near the top right) (you will need to be signed into your github account)

This makes your own copy of the project, on Github (it's public on the internet, so you can see it and we can see it). You will make changes to this version, then send a Pull Request to tell us to copy the changes to our version (you are not allowd to edit our project directly. Makes sense? someone explain this.)

### Step 2 - CLONE your fork.

Open Github Desktop. (It's a program on your computer).

Click on the plus symbol + at the top left and choose CLONE. Then you should see webring in the list. Select it to clone the repository.

(If you don't see 'webring' in the list, you might need to restart Github Desktop and make sure you're signed in.)

This copies your repository to your computer, so you can edit it using your favourite text editor (i.e. Atom).

Webring should appear in the list on the left of Github Desktop. Right click on it and choose 'Open in Atom' to open in Atom. You will need Atom installed.

### Step 3 - Adding your site.

Make a new html file to be your page. Start with something simple, name it something like _yourname.html_

Add this code somewhere in the head:

```
<link rel="stylesheet" href="shared.css" type="text/css" />
```

Add this code somewhere in the body:

```
 <div class="web-ring-box">
    <div class="web-ring-header">Code Club Web Ring</div>
    Next: <a href="matthew.html">matthew's page</a>
    Previous: <a href="matthew.html">matthew's page</a>
  </div>
```

Commit your change, sync, and then do a pull request to ask us to merge your change into the main version.

Once it's merged, your page will appear at http://codeclubakl.github.io/webring/yourname.html (you will need to get someone to merge, and then it may take up to 5 minutes to go live)

### Step 4 - fixing the links

In Github Desktop, click 'sync' to get everyone else's updates.

Once there are some other pages, fix the 'next' and 'previous' links on your site to link to the next page and the previous page (alphabetically) instead of just linking to my site.

Commit your changes.

One everyone has the right links, you should be able to go around the whole ring by clicking 'next' on each site.

### Step 5 - make your page cooler idk
