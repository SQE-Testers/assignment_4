## Modularity Requirements

- 2.1 Cohesion of 90 percent of modules of an E-Commerce website should be less than LCOM = 10 which will make it highly cohesive.
 
  - 2.2.1 The modules of an E-Commerce store should split into classes if LCOM > 20 (we declared it highly non-cohesive) to make modules cohesive.

- 2.2 The level of coupling of 70 percent of two components of E-Commerce application should be less than 2 which will positively influence the Fenton and Melton metric and ultimately low coupling between the components.


    C(a, b) = i + n / (n + 1)
    
    In this formula, the variable n represents the actual number of direct dependencies that exist between components a and b. The variable i will produce a value that
    indicates the level of coupling that exists between a and b. Developers can determine i by examining each of those components and identifying the 
    tightest dependency relationship, with 0 representing the lowest level of dependency and 5 representing the highest.
    
    ![LCOM](https://i.imgur.com/vUT6CYt.png)
    
       A2 = { V2, V5 }
       A3 = { V3 }
       A4 = { V4 }
       A5 = { V5 }
       A5 ∩ A2 = { V2}
       And all other intersection results in empty sets, meaning that:
       |P| = 9, |Q| = 1
       LCOM = 8

    
 
 - 2.3 90 percent of methods in an E-Commerce application should have less than 50 lines of code.

- 2.4 The classes/methods of an E-Commerce application should have only 1 responsibility(Single Responsibility Principle).

