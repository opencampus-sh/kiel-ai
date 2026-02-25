# Setup Instructions for Jupyter Notebook Support

### Setting up **the IDE**

**Instructions for PyCharm (Version 2025.1 or newer)**

* Make sure you have the [latest, unified Version](https://www.jetbrains.com/pycharm/download/), **not** the Community Edition
* If you are coming from the Community edition you can import all of your settings
  * To get rid of the messages to switch to Pro, you have to cancel the 30-days-trial-subscription (top right corner, scroll all the way down, click _continue with core version_, click _cancel subscription_ and restart PyCharm)
* Open a new project (File > New Project)
* Select _Pure Python_ and Interpreter Type _Project venv_ and adjust the environment location on disk as needed
* From the menu create a new file (File > New) and select Jupyter Notebook
* Run a code cell to see that it works (takes some time on first start in a new project, because it installs some dependencies into the project folder's environment)

**Instructions for VS Code**

* Install [VS Code](https://code.visualstudio.com/Download) and then the extensions _Python_ and _Jupyter_ (both by Microsoft) from the extensions pane
* In the file explorer pane open a folder where you want your project to be stored
* Create a Jupyter Notebook (File > New > Jupyter Notebook)
* Click on Select Kernel > Python enviroments > New environment > python venv > Python (global)
* Run a code cell to see that it works (takes some time on first start in a new project, because it installs some dependencies into the project folder's environment)

### Installation of other libraries <a href="#installation-of-other-libraries" id="installation-of-other-libraries"></a>

* After you have setup Notebook support in VS Code and/or PyCharm you can install new packages into the project folder (local venv environment) by executing a cell like this: `%pip install package_name`

​
