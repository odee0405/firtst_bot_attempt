# Bits Foods Chatbot
Answers the questions you'd have when ordering a meal from the restaurant

name = input("Hi I'm the Bitsbot . Here to assist you . May I know your name? : ")
order = input("""We have burgers, pizzas and chicken.
Please let me know which option you would like to have 
Please enter a choice """ + name + " :")

if order == "burgers" or order == "burger":
    burger_type = input("chicken or beef? : ")
    if burger_type == "chicken":
        print("Thanks " + name + " your chicken burger will be ¢45")
    elif burger_type == "beef":
        print("Thanks " + name + " your beef burger will be ¢50")
    else:
        print("Invalid! Please restart order")
elif order == "pizza" or order == "pizzas":
    pizza_type = input("chicken or beef? : ")
    if pizza_type == "chicken":
        print("Thanks " + name + " your chicken pizza will be ¢70")
    elif pizza_type == "beef":
        print("Thanks " + name + " your beef burger will be ¢80")
    else:
        print("Invalid! Please restart order")
elif order == "chicken":
    chicken_type = input("grilled or fried? : ")
    if chicken_type == "grilled":
        print("Thanks " + name + " your grilled chicken will be ¢50")
    elif chicken_type == "fried":
        print("Thanks " + name + " your fried chicken will be ¢40")
    else:
        print("Invalid! Please restart order")
else:
    print("Invalid! Please restart order")
taste = input("Would you like to have your meal spicy or mild? : ")
if taste == "spicy":
    print("We'll keep everything spicy for you")
elif taste == "mild":
    print("We'll keep the flavors mild for you")
else:
    print("Invalid! Please choose whether mild or spicy")
payment = input("Mobile money(momo) or cash? : ")
if payment == "Mobile money" or payment == "mobile money" or payment == "momo":
    print("Please make payment to 0559262195")
elif payment == "cash":
    print("Please make cash ready at the time of delivery")
else:
    print("Invalid, please select a payment option")
print("Thanks " + name + "! Good things come in Bits!")

