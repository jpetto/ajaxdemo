AJAXDemo
===========

**Fork this repository**

1. Click the "Fork" button near the upper right corner.
2. Follow the prompt and wait for the forking to happen.
3. After you have forked the repo, open up *GitBash* and navigate to your *ewt* folder.
4. Type `git clone git@github.com:yourusername/ajaxdemo.git` to pull the code down to your machine.

You will now have a `ClassRoster` folder inside your EWT folder.

**AJAX-ify The Site**

Instead of loading a whole new page when you click the buttons, write some JavaScript that will:

1. Pull the requested page using an AJAX request (the browser should not refresh).
2. Replace the content that changes (the service name and description).
3. Push your changes up to GitHub.

You may need to read up on the jQuery functions `empty`, `find`, and `append`.

**Get Fancy?**

If you find the above pretty easy, write some JavaScript to make the site perform better.

Right now, we pull down the requested page each time a button is clicked. Wouldn't it be better if we only pulled the page down once?