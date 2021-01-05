# whodir
This is my first repoesitory, It contains the ITS muddle function: WHO, DIR, and  TYPFIL

<DEFINE WHO()  ;"PRINTS ON YOUR TTY WHO IS LOGGED ON TO THE SYSTEM.             
                 READES THE PSYDO-FILE "TTY:.FILE. (DIR)" AND COPYIES 
                 IT TO .OUTCHAN, NORMALLY YOUR TTY"                                   
       ......>
  
  <DEFINE DIR ("OPTIONAL" DIR0 "AUX" (D <SNAME>))                                 
        ;"TYPES A DIRECTORY LISTING ON YOUR TTY. IT TAKES AN OPTIONAL           
          ATOM WHO'S PNAME IS THE DIRECTORY TO LIST. IT DEFAULTS TO             
          YOUR LOGIN DIRECTORY."                                                
        ......>
  
  <DEFINE TYPFIL (FILENAM "AUX" TMP)                                 
        ;"TYPES A FILE ON YOUR TTY.
          FILENAM IS THE FILE NAME STRING THAT YOU WOULD
          TYPE TO :PRINT OR ^R "                                                
        .......>
        
