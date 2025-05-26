# KitchenOps Challenge !

## Prerequisite: We first need to import data, dashboard, and plugins
Follow these steps:

1. Add the data source
    - **You probably already have one if you followed the first exercise. If so then skip to step 2**
    - Click the menu button (☰) at the top left, and then click on *Data sources*.
    - Click on *Add new data source*
    - Search for *TestData* and click on it
2. Import the dashboard
    - Click the menu button (☰) at the top left, and then click on *Dashboards*.
    - On the Dashboards screen, click the *New* button and then click *Import*.
    - On the Import Dashboard screen, in the *Import via grafana.com* field, type in `20605` and then click *Load*.
3. Configure dashboard's data sources:
    - For TestData DB, choose `TestData`.
    - Click on *Import*.

Our dashboard already has useful information but it's difficult to read. **Let's make it better**

## Challenge description
You have been recently hired to run your restaurant's KitchenOps program. The restaurant is so close to its 3rd Michelin star, you can taste it !

One way to attain that 3rd star is to deliver consistently perfect results in meal preparation. This means having complete control over:
* Oven, stovetop, and grill temperature settings
* Shelflife of the freshest ingredients (and the soup!)
* Consistency of food preparation times per meal time
* and more.

Being in the 2-star tier, this restaurant has recently invested in IoT telemetry to track these sorts of things, and the restaurant owner's IT person has already created a set of library panels for these sensors. 

All we have to do is present them in a way that is easy for the kitchen staff to understand and attractive enough - if they were to peek into the kitchen - for an anonymous Michelin inspector to notice !

### Our restaurant needs:
Our kitchen standards:
1. While ground spices are typically replaced at 6 months and other spices should be replaced every 2-4 years, this kitchen tries to keep spices for no more than *4 months* - when they remember.
 
2. The grill needs to kept at *387 degrees*, plus or minus 7 degrees for our signature "Bodacious Burger"

3. We need to track how long each chef cooks our signature, pan-seared "Choice Coho (Salmon)". Since we individually choose each salmon fillet for consistent thickness, freshness and quality, we are still getting inconsistent ratings from our guests. Each side needs to be cooked for *150 seconds* - no more, no less.

4. The refrigerator needs to stay between *35 and 38 degrees*. Some unknown chef has nightmares from a former food safety violation when their previous restaurant's temperature was found to be 41 degress (a food safety violation) and now keeps turning down the temperature, making the eggs freeze on occasion.

5. The lobster mac n' cheese is so popular that one of the ovens is now the dedicated "MacOven". It stays at *375 degrees* for best results but can vary 25 degrees in either direction.

6. Our restaurant's multicolor mood lighting is incredible. Let's make sure 100% of the lights are working.

7. Let's make sure the room temperature is 70 degrees (F) in all 8 zones of our dining rooms. We don't want our guests to suffer the chill below 69 or a heat above 71 degrees Farenheit.

### Examples:
You can import an example by importing the dashboard `20606`. It uses the exact same data but presented differently.

You can send us your best dashboard and we will add it here for the world to see !
