# Poetry Tkinter Template

This is a boilerplate project that got me set up with customtkinter's button demo

## Usage

Enter the virtual environment shell:
```shell
poetry shell
```
*if you don't have poetry shell add it with this command*
```shell
poetry self add poetry-plugin-shell
```
Run the project:
```shell
python src/poetry_tkinter/main.py
```

## Issues
I ran into an issue where the version of python I installed with Homebrew did not come with tkinter. 
I had to add tkinter with homebrew for the version of python that I was using. 
```shell
brew install python-tk@3.VV
```
*where .VV is the python version number*

If you need to change which version of python poetry is using then you can use this command:
```shell
poetry env use 3.VV
```
*where .VV is the version number*