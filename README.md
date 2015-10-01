# Columbia Python Users Group Meeting #1 9/29/2015

## Installing Anaconda and Jupyter on Windows

* Download: [Anaconda](https://www.continuum.io/downloads)(https://www.continuum.io/downloads)

1. Anaconda will install to `C:\Users\(Your Username)\Anaconda3`

2. Ensure you Check: 
	a. [x] Add Anaconda to my path 
	b. [x] Register Anaconda as my default Python 3.4

3. Python and ipython will be added to your path. If it doesn't work in cmd, make sure to restart cmd.

4. You can enter the ipython interactive shell by typing `ipython` in `cmd`.

4. Install Jupyter from the conda package manager. 
```bash
conda install jupyter
```
5. Create a folder that you would like to store your notebooks for Jupyter and then navigate to it.
```bash
mkdir C:\notebooks && cd C:\notebooks
````

6. Start a local instance of Jupyter. This will create a web server and then open up one of your browsers to the site. If that doesn't happen, open a browser a navigate to `http://localhost:8888`
```bash
jupyter notebook
```

7. From here, you can create your own notebooks to play around with, or download the git repository that we made during the meeting.


## Installing and using Git
* Download: [Git](https://git-scm.com/)(https://git-scm.com/)
* _Optional_: [Github GUI](https://desktop.github.com/)(https://desktop.github.com/)
* _Optional Git training_: [Try Git](https://try.github.io/)(https://try.github.io/)

1. If you don't feel comfortable working with git on the command line, you can download the gui linked above.

2. navigate to the folder we made for your jupyter notebooks.
```bash
cd C:\notebooks
```

3.  clone the repository that was created for our meeting
```bash
git clone http://git@github.com/ColumbiaPythonUsersGroup/sandbox.git
```

4. Now you can look at the sandbox project we were working on. You will also see it show up in jupyter.

5. You can make changes and then push them back to the repository. make sure to use `git status` to check the status of file changes.
```bash
git add .
git commit -m "Changed Stuff"
git push origin master
```




## Python Challenge
Link: [Python Challenge](www.pythonchallenge.com)(www.pythonchallenge.com)
Anthony suggested python challenge as a good way to get acquainted with the language. Great idea! Check it out above. Use Python to solve the problems. If you get stuck, let us know!


