# ++HOW TO DEPLOY PYTHON PROJECT ON HEROKU++

1. create a new app on heroku <br>
2. on the seeting tab of the project add a python bulid pack
3. install heroku commandline and gitbash
4. <br>
5. run this commands
  <br> install pipreqs python library by running <br>
   **pip install pipreqs**    <br>
   after installing
   run command in the commandline
   **pipreqs "file_path_to_your_project"**
   
   create a **Procfile file **without any suffix like “.txt”
   then insert the following text in your Procfile
   
     web: python YOURSCRIPTNAME.py
     worker: python YOURSCRIPTNAME.py  <br>



6.  **heroku login <br> git init**
7. ** git add .**
8.  **git commit -m "commit message"**
9.  **heroku git:remote -a  heroku_app_name**
9.  **git push heroku master**