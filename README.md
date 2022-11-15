# GUI for solution-finder
"GUI for solution-finder" is a graphical user interface application for Windows to explore various probabilities, piece placement, etc. in "Tetris", the world-famous puzzle game. 
This application uses "solution-finder", created by knewjade (https://github.com/knewjade), and "path-filter#", which I extended from knewjade's "path-filter".

# Main Features
- Fumen editor is attached. You can create fumens and use in this application. Created fumens can be saved. Editor operation is very simple, using left and right mouse clicks.
- In addition to "Perfect clear ("PC") mode", "Setup Mode" and "Fumen Editing Mode" are also available.
- In PC mode, in addition to "unique solutions" (all solutions) and "minimal solutions" (solutions not inclusive of other solutions), "Filtered solutions" can be obtained. This has 2 modes. One is "minimum solutions", which is "real" minimum solutions not "minimal". The other is "Fix solutions", which is used when you want to know the highest rate solutions with fixed number of solutions (for example, solution combination with the highest PC rate among the 5 solution combinations).
- In addition to the normal PC solutions, TETRIS PC, TSD PC, or TSS PC solutions are searchable.
- In "Setup Mode", you can research other than PC (for example, setup rate of an opener, all piece's combination with the same shape as an opener).
- In "Fumen Editing Mode", you can create 1 pager of a fumen, remove all comments form a fumen, merge fumens, and manage saved fumen files (rename and delete fumens).

# Startup Guide
- Download "GUI for solution-finder".  
- Save it in the same folder where "sfinder.jar", which is the java executable file name of "solution-finder", is saved. If you do not have "solution-finder", download the latest version from knewjade's website (https://github.com/knewjade/solution-finder/releases).
- Open "GUI for solution-finder".

# Caution
- This application is for Window(x64) only.
- This application only works on ".Net (Core)" platform (.Net Core 3.0, Core 3.1, 5 or 6). If you do not have these, download ".NET 6" from Microsoft's website (https://dotnet.microsoft.com/en-us/download). Note that this application does not work on ".NET Framework" pre-installed on Windows machines.
- Currently the latest version of "solution-finder" is "v1.30", and at least "v1.12" or later is required.
