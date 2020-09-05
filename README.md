# Automate boring stuff with Python programs with a GUI

[![Run on Repl.it](https://q37.info/s/kpm7xhfm.png)](https://q37.info/s/kk9xhnnf)

This project is inspired by https://automatetheboringstuff.com/, a book by Al Sweigart, more precisely from its [chapter 13](https://automatetheboringstuff.com/2e/chapter13/), but with the addition of a graphical user interface with the help of the Python version of the [*Atlas* toolkit](https://atlastk.org).

The first example  (in the `Excel-1` folder) displays an Excel spreadsheet of data from the 2010 US Census in a more conveniently way. By selecting a state in the left bottom frame, you have access to a summary of its counties in the right bottom frame, and by selecting one of this county frame, you have access to the tracts in the top frame as they are stored in the Excel spreadsheet.

The second example (in the `Excel-3`folder) is very loosely based on the example of the book. It simulates a hand-written Excel spreadsheet containing produce sales, where error were made on the produce name. The spreadsheet does not contain such errors, which are added by the `scramble()` function once the spreadsheet is loaded. The displayed table is split in two part, based on how often the produce name does appear in the spreadsheet, the first containing the produce names with an error, the second the right produce names. You select one or more instance of the same product in the first part, by checking the corresponding checkbox, and the right produce name by checking the corresponding radio button. By clicking the `Coll./Exp.` button you switch between displaying only the selected produces, or all the produces. The `Apply` button corrects the selected produce names, and the `Jump` button allows to jump to the part of the table containing the right produce name.

To be complete, both examples lack of the save button, but you can easily implement it, as an exercise, by following the indications in the book.

To launch a demonstration, first install the needed modules with `pip install --user -r requirements.txt` and then simply launch `python Excel-1/main.py` or `python Excel-3/main.py` from the root folder of the repository.

For the [online demonstration](https://q37.info/s/kk9xhnnf), once in *Repli.it*, click the `run` button, and then select the demonstration you want to launch. If the QR code is not displayed properly, hit the refresh button top left of the corresponding frame.
