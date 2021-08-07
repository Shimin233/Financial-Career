## Download and use locally
Following instruction [here](https://github.com/jupyter/notebook/blob/master/README.md), summarise the useful steps: 
(Can see Terminal file in shiminfu/Desktop/CareerPreparation/Install_Use_Jupyter)
Open Terminal, type (then press return/enter, same as below)
```
python3 -m ensurepip --upgrade
```
since I have Python3 (while Python2 is also there) but seems not to have pip, 
I use this to install pip according to [pip document](https://pip.pypa.io/en/stable/installation/)

Then type 
```
pip install notebook
```
to install Jupyter notebook. 

Run Jupyter notebook by typing
```
jupyter notebook
```
Then I am automatically directed to a webpage of Jupyter notebook, with address being `http://localhost:8888/tree`. 

To re-access the notebook, note that there are routes in Terminal running result:
To access the notebook, open this file in a browser:
        file:///Users/shiminfu/Library/Jupyter/runtime/nbserver-26879-open.html
    Or copy and paste one of these URLs:
        http://localhost:8888/?token=9f73284a5798d3ce3f59b0eaeae0c0183da0a1038166e524
     or http://127.0.0.1:8888/?token=9f73284a5798d3ce3f59b0eaeae0c0183da0a1038166e524

If finding that the addresses above do not work ('Safari can't connect to the server' etc.), then open Terminal and type
```
jupyter notebook
```
Then auto-redirection to Jupyter will operate again.

## On Github
See [guideline](https://docs.github.com/en/github/managing-files-in-a-repository/working-with-non-code-files/working-with-jupyter-notebook-files-on-github)
