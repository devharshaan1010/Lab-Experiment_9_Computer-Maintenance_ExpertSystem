# Lab-Experiment_9_Computer-Maintenance_ExpertSystem

### DATE:03-04-2024                                                                            
### REGISTER NUMBER : 212221040035
### AIM: 
Write a Prolog program to build a computer maintenance expert system.
###  Algorithm:
1. Start the program.
2. Write the rules for each fault in computer.
3. If system have printing problem, missing dots and no uniform printing then system fault on printer head.
4. If system have not printing, missing dots and spread inks then system fault on ribbon
5. If system have not printing, paper jam and out of paper then system fault on paper stuck in printer
6. Similarly define rules for all faults.
7. Define facts for system problems.
8. Find the fault of computer by passing query to system.
     
### Program:

```
fault(printer_head) :-
problem(not_printing),
problem(missing_dots),
problem(nonuniform_printing).
fault(ribbon) :-
problem(not_printing),
problem(missing_dots),
problem(spread_ink).
fault(paper) :-
problem(not_printing),
problem(paper_jam),
problem(out_of_paper).
fault(motherboard) :-
problem(long_beep),
problem(short_beep).
fault(hard_disc) :-
problem(two_short_beeps),
problem(blank_display).
problem(not_printing).
problem(missing_dots).
problem(spread_ink).
problem(two_short_beeps).
problem(blank_display).

```





### Output:
![image](https://github.com/VRVijaykumar123/ex1.bfs/assets/133218255/d06ede2a-fdfd-4918-a237-de146dab2d99)



### Result:
Thus the simple omputer maintenance expert system was built sucessfully.
