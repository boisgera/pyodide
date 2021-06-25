Pyodide
================================================================================

🐍 Pyodide is a Python runtime in the browser, powered by WebAssembly.

Getting Started
--------------------------------------------------------------------------------

🖥 [Start the REPL](https://pyodide.org/en/stable/console.html) 

![](images/REPL.png)

⚠ Using the REPL means downloading the WebAssembly version of Python.
Around 6 MB of data have to be downloaded first; starting the REPL will
also take some time. Expect typically between 1 and 10 seconds 
to get started.

Data transfer are not over once the REPL is started: import NumPy and Pillow
for example (which works out of the box! 🎉) will require another 6 MB download.