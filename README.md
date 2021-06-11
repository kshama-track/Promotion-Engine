# Promotion-Engine
Promotion Engine :- Sample application to create multiple promotions and apply it against single character SKU.


# Promotion-Engine Steps 
- Get Shopping cart as an input
- Build Pipeline
  -  Initialize SKU Pricing
  -  Read all rules from repository with best rule on top.
  -  Default rule to set price
- Execute Pipeline  
  -  Execute first rule which will set default pricing for shopping cart item.
  -  Execute all configured rules and based on mathcing criteria apply promotion of respective rule.
  -  Execute last default rule for items which are not applicable for any promotion.
  -  Return total shopping cart amount.