# Atom Highlighting for Dynare

Dynare is one of the most used tools by economist who work with macroeconomics. This project attempts to create a syntax highlighting for Dynare in Atom.  

So far, I have implemented the following:

* Parameters, var, varexo, varobs are already highlighted
* stoch_simul, check and steady are already highlighted
* Multi line comments and one line comments are in light gray
* Blocks for initval, endval, model and shocks
* Stochastic and deterministic commands have different colors: deterministic commands are in blue
* Greek letters are highlighted, so one can easy find parameters in an usual model
* Red background when you forget to end the line with ; - although it will highlight even when you don't want the ; (eg.: multiline equations)
* Some macro commands are already implemented and should be highlighted in cyan

## If you are completely new to atom

Atom is an editor that is really easy to use and supports multiple programming languages - and best of all, it's free. You can download it at http://atom.io

While this package is not avaible at the packages section of atom, you can download it and put the language-dynare folder in the /your-username/.atom/packages. It should work without any problem.    
