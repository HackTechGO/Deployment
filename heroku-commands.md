# Steps to deploy a static Node website to Heroku

1. Create an account on www.heroku.com if you don't have one already.

2. If you on a local machine download and install Heroku Toolbelt from www.toolbelt.heroku.com/. On ide.goorm.io, Heroku CLI is already installed.

3. Open terminal/command line to point to the directory where the file containing your app code is located.

4. Using the terminal, log in to Heroku with: <b>heroku login -i </b>

5. Enter your Heroku email address

6. Enter your Heroku password

7. Create a new Heroku app with: heroku create <myawesomeappname>. If you skip the app name, heroku will create a random name for you.

8. Initialize a local git repository with: <b>git init </b>

9. Add your local application files to git with: <b> git add .</b>

10. Tell git your email address with: <b>git config --global user.email "myemail@hotmail.com" </b>. The email should be in quotes. 

11. Tell git your username (just pick whatever username) with: <b>config --global user.name "whateverusername"</b>. The username should be in quotes.

12. Commit the changes with: <b>git commit -m "first commit"</b>. Make sure "first commit" is inside quotes.

13. Check if you are connected to heroku with: <b>git remote -v</b>

14. Push your files to heroku with: <b>git push heroku master</b>

15. That should do it. Go ahead and open your app with: <b>heroku open</b>


# Useful commands:
- <b>heroku</b> - shows all heroku commands
- <b>heroku info</b> - info about the app
- <b>heroku logs</b> - shows logs
- <b>heroku run <unix command></b> like "ls", "npm install mongoose --save"
- <b>heroku git:remote --app <myawesomeappname></b> - Before pushing the changes to Heroku, that is how to tell heroku the name of the app you want to use with
