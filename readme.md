**Getting Started:**

`prerequisite:`

1. Install firefox.
2. Install geckodriver for Firefox. [Download here](https://github.com/mozilla/geckodriver/releases)
3. Install Git in your System.

Now, let's start using this Bot in your system as well.

**Clone the repository**

 Firstly, Change the path according to your path of geckodriver(it should be executable):
 Here executable means the ending path should be in .exe
 **How to change path**

 1. click on start button and searvch for environment variable.
 2. A pop-up window come click on Environmental variable
 3. In system variable click on paths
 4. Copy the path of your geckodriver and paste it there
    **how to check geckodriver installed successfully**
    1. Open CMD
    2. Type Geckodriver --Version
    3. Here you will see the all the information regarding the Geckodriver version
 
> In line 15 replace the path with your path
If you are getting error mentioning like (Unicode error) just change in the path with //.

**Next Step**

 You need to start an virtual enviornment in your system

python -m venv navenv
venv\\Scripts\\activate.bat 
**Next Step**

 **Installing  Dependencies:**
  
  Activate your virtual environment and install the required packages listed in `requirements.txt`:

Run this command in the terminal
pip install -r requirements.txt


 **Run the Application:**
 Start the bot by running:


python main.py
