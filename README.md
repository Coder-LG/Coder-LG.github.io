# c-l-2oo8.github.io
This is my personal website.
You can visit it but please do NOT fork it.
If you also want a website like this, follow the steps below.

# Steps to create the website

You need Ruby, bundle and Jekyll
Install them, first Ruby:
https://www.ruby-lang.org/en/ ,
 then open Git Bash(recommended):http://git-scm.com/
 or Terminal for Mac OS and Linux.

Install GitHub Desktop, then sign in. 
Create a repository on GitHub and name it as USERNAME.github.io, where USERNAME is your GitHub username., and hit the Desktop button, first line, and accept it's prompt.
Then, you click clone in Github Desktop.
Now, open your terminal and run this command: **gem install jekyll bundle**.
hen go to your clone repository folder and run this command:
**jekyll new**.
Now, wait and when it is done, go to Gemfile and find the first command saying:
gem "jekyll".
Now, add # to the beginning, and it should look like this:
**#gem "jekyll"**.
Now, add this command, right below the hash command:
**gem "github-pages", "~> GITHUB-PAGES-VERSION", group: :jekyll_plugins**,
where GITHUB-PAGES-VERSION is the version number of your GitHub Pages, find it in this URL:
https://pages.github.com/versions/.
Find only github-pages and enter the version number.
Then, save and close the Gemfile.
Then open your terminal of choice and run this command:
**bundle update**.
Now, open GitHub Desktop and see the bottom left corner. Fill it and hit Commit to master.
Then, hit Ctrl+P and wait for a few minutes.
Now, go to USERNAME.github.io, and enter your username intead of USERNAME.
Watch the magic happen!

# More info

Favicon adding:https://medium.com/@xiang_zhou/how-to-add-a-favicon-to-your-jekyll-site-2ac2179cc2ed

How to make the site:https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll
Thanks!
