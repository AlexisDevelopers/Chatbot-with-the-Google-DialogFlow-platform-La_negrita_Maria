# Chatbot-with-the-Google-DialogFlow-platform-La_negrita_Maria

The purpose of this chatbot is to advise tourists who visit the Punta Cana area in the Dominican Republic, among its features are:

Recommend Hotels, Recommend Restaurants, Recommend Bars/Discotheques, Recommend Drinks/Drinks from the Region, Recommend Monuments, Recommend Museums, Recommend Means of Transportation, Ask for a Taxi/Uber, Rent a Vehicle, Ask for a Drink/Drink, and Ask for Food.

# Intentions:
It is composed of 19 intentions:
endconversation
SearchBarDrink
SearchFood
SearchEvents
SearchHotel
SearchMonuments
SearchMuseums
SearchBeaches
SearchRestaurant
SearchStores
SearchTransportation
LocateTransportation
ShowDrinks
ShowHealthyDrink
ShowFunctions
showburger
ShowPizza
OrderDrinks
OrderDrink
Presentation
Recommend Drink
Greetings


## Entities:
It is made up of 8 entities:
 tipoBebida: entity that defines the types of drinks that the user can request, including Beer, Rum, Whiskey, Typical Drink, Banana Mama, Coco Loco, and Mamajuana.
 saludosDelDia: entity that defines the greeting according to the time of day the user greets, for example, good morning, good afternoon, good night.
 tipoBebidaComida: entity that defines the type of non-alcoholic beverage.
 tipoComidaGeneral: entity that defines the general type of food: pizza, hamburger, healthy, drink.
 typeHealthyFood: entity that defines healthy meals: salad, oatmeal, protein bars, etc.
 hamburgertype: entity that defines the type of hamburger: chicken, cheeseburger, big mac, vegetable, double cheese.
 tipoPizza: entity that defines the type of pizza: Hawaiian, Mexican, four seasons, chicken, etc.
 tipoTransporte: entity that defines the types of transportation that the user can request Taxi, Rented Vehicle, Uber and Minibus.


## Contexts:
It is composed of 7 contexts:
 Transportation context: it is used to first contextualize the conversation about the types of transportation available in the place so that the user can then choose one and request a taxi, uber, minibus, or rent a vehicle.
 OrderDrink context: it is used to first contextualize the conversation about the types of drinks available for home delivery and then the user can choose the type of drink.
 showFood: context for when the user orders food or drinks, show the types of food. Example: "What do you want to eat: Pizza, Hamburger, Healthy Food and Drinks: Grape, Raspberry, Meringue, Water, Yogurt."
AskHealthyFood: used to contextualize the types of healthy foods, after starting the conversation to buy food.
Ask for Burger: used to contextualize the types of healthy burgers, after starting the conversation to buy food.
 OrderPizza: used to contextualize the types of pizzas, after starting the conversation to buy food.
Ask for Drinks: used to contextualize the types of drinks, after starting the conversation to buy food.
