# Steps Taken

Documenting steps taken to develop this app:

- Created the repo on GitHub
- Cloned the repo locally to VS Code
- Installed Python from the [Python website](https://www.python.org/downloads/)
- Installed the VS Code [Python extension](https://code.visualstudio.com/docs/languages/python)
- Select a Python environment (Python 3.7.8 - keeping it simple by using the default)
- Create a virtual environment and install packages:
  - `py -3 -m venv .venv`
  - `python -m pip install pandas`
  - `python -m pip install matplotlib`
  - `python -m pip install --upgrade pip` (if necessary)
-  Start coding
-  If processing Excel files, **and** you want them saved as pipe-delimited files, **and** you're using Windows, [change the default format](https://www.extendoffice.com/documents/excel/4791-excel-save-as-convert-to-pipe-delimited.html):
   -  Open Control Panel
   -  Select `Clock, Language, and Region`
   -  Select `Region`
   -  Select `Additional Settings`
   -  Under the `Numbers` tab, select `List separator:`
   -  Enter the pipe symbol `|`
   -  Don't forget to click `OK`
-  