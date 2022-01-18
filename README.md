# quiz1
let's see where we are!

1. Download `git`: [link](https://git-scm.com/downloads)
2. Clone this repo
  
        git clone git@github.com:CHEM-PHYS-X684/quiz1.git
      
3. Go into that directory

        cd quiz1
        
4. Start up a new `jupyterlab` window, then double click on the quiz notebook

         jupyter-lab
         
5. Save your notebook 
6. See that `git` noticed your changes

        git status
        
7. Start a new branch. For this case, you might choose to use your name

        git checkout -b mayhall
        
8. Commit your changes

        git commit -am "finished answering the questions"

9. Push your changes to github

        git push
        
   > You will get an error that you have not yet told it how to push. The prompt will then give you a command to run to set this. Mine is:
  
        git push --set-upstream origin mayhall
        
        
 
