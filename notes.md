## Some helpful notes for easy reference:

### Always remember to use some type of virtual environment!  
#### a few commands for using virtualenv:

create a virtual environment with name "venv" (you could name the environment anything, CatMemesEnv will totally work).

fire up the virtual environment ->  $ source venv/bin/activate

there should now be "(venv)" prepended to the terminal prompt, for eg mine went from this:
    upcbro@areupc:~/DevOps/projects/cicd-buzz/buzz$
to firing up the virtual environment gives me this:
    (venv) upcbro@areupc:~/DevOps/projects/cicd-buzz/buzz$
    
in order to leave a virtual environment, use this command -> $ deactivate
you should now be back to your "regular" terminal prompt, with no "(venv)" prepended

#### Travis is pretty cool, easy to use.
#### In the Travis file, make sure and stick with python, not python3.

#### Better Code Hub, pretty cool tool as well!

make sure to stop the Flask server running local on :5000 before attempting to get the Docker container running on the same port.


