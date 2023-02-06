# Communauto Station Relocation Study
````diff 
+ (communauto-station-relocation)
````
### Quick Summary
***
- **Purpose:** Study the relocation decision of vehicles if Communauto were to change from street-parking-based to parking-lot-based.
- **Dataset Source:**
  - [Communauto Vehicle Location](https://monstyledeville.net/)
  - Self-generated user data
<br><br>

### Detailed Description
***
Using **Gurobi**, a mixed integer model is formulated to derive the optimal solution for a relocation problem.

Communauto is a company providing sharing-car service. One of its option is called _"Round-Trip"_, that is users have to pick up cars from a certain location and return them back to exactly the same place after using. This study focuses on the Round-Trip service and evaluate the best relocation solution if Communauto decided to adopt parking-lot-based policy instead of street-parking-based.

Target areas in this study are Ville-Marie and Plateau Mont-Royal in Montreal. User data were generated based on weekly demands.
<br><br>

### Preview
***
- Current vehicle location
![Current vehicle location](https://user-images.githubusercontent.com/111717563/216881424-4aff4816-394d-4b5e-a810-efb2c4e74e60.png)

- Relocation suggestion with coverage
![Relocation suggestion with coverage](https://user-images.githubusercontent.com/111717563/216881584-b94a5dd1-6238-481e-90b6-00e472ab344b.png)
