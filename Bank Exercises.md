**Exercice 1**

| Class | LOC | NOM |
| :---- | :---- | :---- |
| Bank | 392 | 14 |
| BankAccount | 403 | 18 |
| Person | 294 | 21 |
| BankAccountApp | 447 | 2 |

**Exercice 2**

Méthode withdrawMoney  
CC \= 5

On peut faire la vérification du montant à retirer dans une autre méthode à la place de faire toute la vérification dans la méthode et on évite ainsi les opérateurs If et else  
nom: isAmountWithdralawValid

CC \= 2 après modification

**Exercice 3**

| Class | WMC | CBO | LCOM |
| :---- | :---- | :---- | :---- |
| Bank | 14 | 4 | 0.8333333333333334 |
| BankAccount | 21 | 3 | 0.69375 |
| Person | 23 | 1 | 0.7626262626262627 |

**Exercice 4:**

1 

- Boolean expressions should not be gratuitous Person.java:150  
- Person.java:150  
- This can cause logical errors and if this boolean is unnecessary, it can be removed from the code.

2

- String literals should not be duplicated  
- BankAccountApp:139 BankAccountApp:92 BankAccountApp:101 BankAccountApp:96  
- It makes refactoring more complex and error-prone

3

- Sections of code should not be commented out  
- BankAccount.java:62 BankAccount.java:75 BankAccount.java:222 BankAccount.java:28  
- Commented-out code distracts the focus from the actual executed code. It creates a noise that increases maintenance code. And because it is never executed, it quickly becomes out of date and invalid.

4  
With this example, we can’t say if these indicators really make SolarLint issues increase or not but we can notice that logical tests such as boolean tests could increase the SolarLint issues.