#Team Grapefruit
#CS 3307 Team Project Version 1.0 10/26/2015

-------------------------------------------

##CONTENTS:

 - AgentTaskSpreadsheet.pdf: Detailed table outlining completed and planned tasks, and who contributed to them

 - CaseDiagram.pdf: Graphic representation of how the user interacts with the program

 - ClassDiagram.pdf: Complete list of all of the functions, which class they belong to, and how they interact with one another

 - Timeline.pdf: Table that highlights all of the tasks and their completion date or expected completion date

 - SourceCode folder: Contains all source and header files necessary for program to function

 - Executable folder: Contains executable to run application

-------------------------------------------

##EXECUTABLE:
Build Instructions:
  Simply unzip the folder and open the 'Executable' folder. Double click the executable 'Grapefuit_exe' and the program will begin running. 
  
Notes:
 - Built on a Windows 10 Machine
 - Note, the graphs are currently hardcoded to display for "Strangelove, Dr.". A text entry box will be introduced in time for the V2 submission.
 - Negative dollar values are currently displayed becuase of a datatype overflow. The team is currently working to resolve this issue.
 - It currently uses a modified .csv file for grants because the original grants .csv file contained "LF" characters which added large spaces in the file content and made using the getline() C++ function unusable. This "LF" character was not found in the other .csv files and was not discovered in the original grants .csv file until late. This problem will be resolved for v2 submission.

