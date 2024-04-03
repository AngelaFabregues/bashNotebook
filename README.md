# bashNotebook
Example of Jupyter Notebook with Bash kernel use.

## Setup
* Install Jupyter Notebook: `pip3 install notebook`
* Install Bash kernel:
    * `pip3 install bash_kernel`
    * `python3 -m bash_kernel.install`

## Run

Jupyter Notebook works as a web server that you can launch with `jupyter notebook`.

A local web page is automatically open, otherwise check the logs for its url and use a browser.

You can browse the files and open the one you are interested in.

A good way to start is:
* Open `bash-example.ipynb`
* Select the Bash kernel if it is not selected already.
* Execute (play) cells to see Markdown text rendered and bash commands executed
* Add a new cell (+) and select between Markdown or Code.
* Ctrl + Enter executes the cell
* Remember to save if you want to persist the changes in the file system
* Commands are executed right in the system folder where the .ipynb is, unless you use cd to change dir.