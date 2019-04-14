# Github Python Importer

This module will help to import github python packages as python module.

## Getting Started

PyPi Repository [Link](https://pypi.org/project/gitpyport/)

<img src="2.png" width="350px">

### Prerequisties

Python 3.6 (Tested Platform Python Version)

### Installation and Usage

**Installing via PyPI**

`pip install gitpyport`

<img src="3.png" width="350px">

**Here in the example the pydub module is installed without using pip**

1. Open Python Terminal in the path where your github downloaded package placed.
2. Go to the path in cmd

<img src="1.png" width="350px">

3. Type python to enter into python terminal

<img src="4.png" width="350px">

4. Now type `import gitpyport as g`
If the module is correctly installed then it will return a message

<img src="5.png" width="350px">

`g.about()` will return what the package is.

<img src="6.png" width="350px">

To import the github package as python module type the following command

`g.pyport("file_path")`
Here the file_path = "pydub-master.zip"

<img src="7.png" width="350px">

Now after pressing enter the package will be installed as a module without any need of user interaction. 

<img src="8.png" width="350px">

To use the module firstly exit from the present python terminal by entering the following command

`exit()`

Then again enter into python terminal and import the new python module. The module should be imported without need of any other dependency.

<img src="9.png" width="350px">

*Example Snippet*

```python
import gitpyport as g
g.about()
g.pyport("file_path")
exit()
```
