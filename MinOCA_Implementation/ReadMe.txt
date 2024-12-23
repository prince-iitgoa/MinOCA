######################################## Read Me ########################################
Instructions.
1. Create a folder "Trash" in the same directory as the Python file (Learning.py).
2. The files generated during the learning process will be stored in this folder.
3. Open your terminal and navigate to the directory in which the Python file (Learning.py) is stored.
4. Run the code using the terminal using the command: python Leaning.py <time-out> <display>
	- <time-out> specifies the time allotted for learning a language. Integer specifying the timeout
	- <display> specifies whether the final automaton has to be displayed. Takes a value of 0 or 1. If the value '0' is given, the final automaton won't be displayed by the time taken, and other parameters will be written into a file. If the value '1' is given, then the graphs will be displayed, and the resultant data will be written into a file.
 

###################################### Additional Information ###########################
					  Packages Needed

#The following Python packages are required to run the code
. python-sat - SAT solver in Python
. dfa - Used for converting dfa object to dictionary format and vice-versa
. pydot - Used for generating and viewing the final OCA
. graphviz - Graph visualisation software 

Installation Instructions.
Mac/Windows:
pip install python-sat
pip install dfa
pip install pydot
pip install graphviz


Note: Make sure that the directory in which you have installed the package is added to your systems environment variable PATH.

Alternative:
Mac:
Installation command: brew install graphviz

Windows:
Download the Graphviz installer from https://graphviz.org/download/ and install it.
32-bit: https://gitlab.com/api/v4/projects/4207231/packages/generic/graphviz-releases/2.49.0/stable_windows_10_cmake_Release_Win32_graphviz-install-2.49.0-win32.exe
64-bit: https://gitlab.com/api/v4/projects/4207231/packages/generic/graphviz-releases/2.49.0/stable_windows_10_cmake_Release_x64_graphviz-install-2.49.0-win64.exe


				  Optional Package

					
#The package is needed only if you want to write the Hankel matrix in a file (i.e., if you are using the function PrintTableToFile).
#Not currently needed
. Pandas - open-source data analysis and manipulation tool
Installation Instructions.

Mac/Windows:
pip install pandas

