# Getting started

**Installation**:
- Installation with pip:
    ```sh
    $ pip install uixml
    ```

- Installation with git:
    ```sh
    $ git clone https://github.com/ALhorm/uixml.git
    $ cd colorer
    $ python setup.py install
    ```

# Quick start
After installation you will have access to the console commands of the library. To create a new project, go to any convenient directory and enter the following command:
```sh
$ uixml-create your_project_name
```
A folder should be created in the directory with the name you entered in the console. In this folder are these files:
```
┌──── core/
├──── design/
├──── styles/
├──── windows/
└──── app.py
```
A quick tour of these files:
- **сore** is the folder that contains the source files of the library itself. You can change something there if you like.
- **design** is a folder that contains the converted *XML files in Python code*.
- **styles** is a folder that contains the style files (*CSS files*).
- **windows** is a folder that contains *XML files* describing the application's interface.
