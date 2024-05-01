1. Code will return 3 because var does not care about scope and in for loop it will be assigned to 3.
2. Code returns 150 cause its var and accessed outside of scope.
3. I think the variable will "inherit" the var property due to assignment and will return 150
4. It should return 50,100,150 , there is no code block issues because discounted is var.
5. It should throw null or error (I guess depending on the compiler?) because the let declaration basically means the variable does not exists outside of for loop
6. error -- not defined outside of scope
7. 150 -- let defined the variable in the same scope so we can access it.
8. Should work fine and return 50,100,150 cause we populate the let defind variables into another let. I dont really see any issue.
9. returns null.
10. Scope is same, value was not tried to be changed -- just returns 3.
11. Returns 50,100,150. I guess constant array declaration in this case means that the discounted cannot be changed to some other array, but we can modify the original array it points too. So I guess it cannot change the memory adrress it points to, but its fine to populate the next after first bytes of memory address whetever this array is stored. 

12:
A) student.name 
B) student["Grad Year"]
C) student.greeting()
D) student['Favorite Teacher'].name
E) student.courseLoad[0]

 13:
 A) '32' string + number = string connatinating for + rule 
 B) '1' because for - convers string to number 
 C) 3 because null treated as 0 in the case of numeric operation
D) '3null' same concept as A 
E) 4 because true is numerical 1 in pretty much most of languages due to computer logic 
F) 0 cause both false and null treated as 0 in numeric operations
G) '3undefined' cause string concatenation for + rule 
H) NaN cause cannot convert undefined to number (and who would even do that?)

14: 
A)
B)
C)
D)
E)
F)
G)
