# Steps to deploy a static Node website to Heroku

1. Create an account on www.heroku.com if you don't have one already.

2. If you on a local machine download and install Heroku Toolbelt from www.toolbelt.heroku.com/. On ide.goorm.io, Heroku CLI is already installed.

3. Open terminal/command line to point to the directory where the file containing your app code is located.

4. Using the terminal, log in to Heroku with "heroku login -i"

5. Enter your Heroku email address

6. Enter your Heroku password

7. Create a new Heroku app with: heroku create <myawesomeappname>. If you skip the app name, heroku will create a random name for you.

8. Initialize a local git repository with "git init"

9. Add your local application files to git with "git add ."

10. Tell git your email address with: git config --global user.email "myemail@hotmail.com". The email should be in quotes. 

11. Tell git your username (just pick whatever username) with "config --global user.name "whateverusername"". The username should be in quotes.

12. Commit the changes with: git commit -m "first commit". Make sure "first commit" is inside quotes.

13. Check if you are connected to heroku with: git remote -v

14. Push your files to heroku with: git push heroku master

15. That should do it. Go ahead and open your app with "heroku open".


# Useful commands:
- heroku
- heroku info - info about the app
- heroku logs - shows logs
- heroku run <unix command, like ls, npm install mongoose --save>
- Before pushing the changes to Heroku, tell heroku the name of the app you want to use with "heroku git:remote --app myawesomeappname"
