# reform-the-Windows-Grep-
enlarger [ Folder select window ] of WINGERP by editing a resource data.

- Whta is this?
 Windows Grep is simple but great tool to search a string is spread on many files.
 Just, I guess 'the Folder selecting window' is too small.
 Probably, there are some peoples have same inconvenience like me.
 So, I share the my experience of changing it on this repository.

- How to do?
 An exe file have 'Resource DATA' for making a [ Window ].
 The 'Resource DATA' stores all values of object on windows like a Button size and position.
 So, size of 'the Folder selecting window' is variable by editing this values.
 The 'Resource DATA' editer is 'Resource Hacker V5.1.1'.

- Where is the Resource of 'the Folder selecting window'
 Open grep32.exe with 'Resource Hacker' -> RCData -> TSEARCHWIZARDDLG

- reformed Resource file
 TSEARCHWIZARDDLG.dfm
 * replace resource(RCData -> TSEARCHWIZARDDLG) with 'Resource Hacker'. 



 
