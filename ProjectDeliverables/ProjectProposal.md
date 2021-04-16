A Coffee roaster is looking to craft their next coffee roast and they want to figure out which features have the largest effect on reviews when roasting new coffees! 

For this project, we will be web-scrapping Coffee Review’s website to gather information about reviewed coffee and that coffee’s key characteristics. Once the data is gathered, we will store it into a database (database pending) and model a regress to see if we can predict the product’s rating based on certain characteristics gathered.

https://www.coffeereview.com/review/ (6000 records):

Y Features that will be Scarpped:  
 1) {Overall Review Score (1/100)}


X Features that will be Scarpped:

1) {Roaster Location} - Categorical.   
2) {Coffee Origin} - Categorical.  
3) {Roast Level} - Categorical.  
4) {Agtron} - Categorical.  
5) {Price} - Numeric. 
6) {Aroma Rating} - Numeric.  
7) {Acidity Rating} - Numeric.  
8) {Body Rating} - Numeric.  
9) {Flavor Rating} - Numeric.  
10) {Aftertaste Rating} - Numeric.  

6 Numeric (although most are set ratings)  
5 Categorical  


MVP:

A baseline regression model with some insight into top effective features.
