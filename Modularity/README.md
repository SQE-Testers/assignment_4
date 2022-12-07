## Modularity Requirements

- 2.0 Cohesion of 90 percent of modules of an E-Commerce website should be less than LCOM = 10 which will make it highly cohesive.
 
  - 2.0.1 The modules of an E-Commerce store should split into classes if LCOM > 20 (we declared it highly non-cohesive) to make modules cohesive.

- 2.1 The level of coupling of 70 percent of two components of E-Commerce application should be less than 2 which will positively influence the Fenton and Melton metric and ultimately low coupling between the components.


    C(a, b) = i + n / (n + 1)
    
    In this formula, the variable n represents the actual number of direct dependencies that exist between components a and b. The variable i will produce a value that
    indicates the level of coupling that exists between a and b. Developers can determine i by examining each of those components and identifying the 
    tightest dependency relationship, with 0 representing the lowest level of dependency and 5 representing the highest.
    
    ![LCOM](https://i.imgur.com/vUT6CYt.png)
    
    
   

