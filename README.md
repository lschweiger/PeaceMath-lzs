# PeaceMath
Experimental branch; I am  writing all changes to violetclass and violet,
all data files should be placed into a folder nameed using the numerical value under data_files i.e data_files\111. 
as a fallback script will look in its root folder for files

**A GUI for the ordinary differential equation model of the Sustainable Peace Map**

coded in Python 3.4.1 with Tkinter (I am experimenting in Python 3.6.5)
**Publication of Research**
https://doi.org/10.1088/1367-2630/ab2a96

**MATHEMATICAL MODEL**
Liebovitch, LS, Coleman PT, Futran D, Lee D, Lichter T, Burgess N, Maksumov D, and Ripla C. (in press). Modeling the dynamics of sustainable peace. In U. Strawinska-Zanko and L. S. Liebovitch (Eds.), Mathematical Modeling of Social Relationships, New York, NY, Springer.

**VIDEO OF PROGRAM USE**
https://drive.google.com/drive/u/0/folders/0B3t7HoVL1Ct7dGtqX3JkSDE2T00

#
### HOW TO RUN THESE PROGRAMS


Run Python Scripts:

	1. teal.py or violet for experimental version

The data files should be in their respective folders of the programs:
  - b8.txt, btextbxy8.txt, c8.txt, ic8.txt, m8.txt
  - b105.txt, btextbxy105.txt, c105.txt, ic105.txt, m105.txt
  - 111.txt, btextbxy111.txt, c111.txt, ic111.txt, m111.txt

When asked for "ONLY NUMBER n and I will find cn.txt, etc. (#/a, Def=a)"

	type either:
	-8 (return)
	-105 (return
	-111 (return)

When asked for "Want to CHANGE parameters (y/n), def=n"
	
	type: (return)


NOTE: for OS10.9.5 or Linux the programs should run, but for WINDOWS you may need to change the comment in orangeclass APP: 

        # self.mainloop() TO THE EXECUTABLE STATEMENT self.root.mainloop()
	
	
TO CHANGE INITIAL CONDITIONS: use the left hand entry widgets and ENTER

In terminal:
	to change the fix j values
		pass_data.jvalue=#
	to change which variable is held
		pass_data.jfix=# (0-23)


TO CHANGE THE CONNECTION MATRIX: click on a textbox, use the left hand entry widget, and ENTER (this will also show only the links into and out of that textbox, use ALL Cij to show all the links)

TO RUN THE CALCULATION: use CALCULATE

TO SWITCH FROM THE LINKS TO THE INITIAL CONDITIONS use IC on the links input

TO RESTORE THE ORIGINAL INITIAL CONDITIONS use ORIGINAL on the initial conditions input
	
