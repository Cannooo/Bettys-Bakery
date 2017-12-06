# Bettys-Bakery

print("Welcome to Bettys Bakery")

Done = False

while Done == False:
    Ask1 = input("What cupcake do you want to make? Chocolate, Lemon, or Both? ")


    if Ask1 == "Chocolate":
        print("You picked Chocolate")
        ChocoQtyAsk = int(input("How many do you want to make? "))

        print("You need", 12*ChocoQtyAsk, "g of Flour")
        print("You need", 14*ChocoQtyAsk, "g of Sugar")
        print("You need", 0.1*ChocoQtyAsk, "tsp(s) of baking powder")
        print("You need", 4*ChocoQtyAsk, "g of butter")
        print("You need", 5*ChocoQtyAsk, "g of Dark Chocolate")
        print("You need", 0.1*ChocoQtyAsk, "of free ranged eggs")
        print("You need", 12.5*ChocoQtyAsk, "ml of Milk")
        print("You need", 0.1*ChocoQtyAsk, "of Orange Juice")
        


    if Ask1 == "Lemon":
        print("You picked Lemon")
        ChocoQtyAsk = int(input("How many do you want to make? "))

        print("You need", 240*ChocoQtyAsk, "g of Flour")
        print("You need", 300*ChocoQtyAsk, "g of Sugar")
        print("You need", 0.5*ChocoQtyAsk, "tsp(s) of baking powder")
        print("You need", 4.5*ChocoQtyAsk, "of free ranged eggs")
        print("You need", 140*ChocoQtyAsk, "ml of Double Cream")
        print("You need", 3*ChocoQtyAsk, "Lemons")
        print("You need", 1*ChocoQtyAsk, "pinch(es) of Salt")
        print("You need", 80*ChocoQtyAsk, "g of Butter")

    if Ask1 == "Both":
        print("You picked Both")
        BothChocoQty = int(input("How many Chocolate Cupcakes do you want to make? "))
        BothLemonQty = int(input("How many Lemon Cakes do you want to make? "))

        print("You need", (12*BothChocoQty)+(240*BothLemonQty),"g of Flour")
        print("You need", (14*BothChocoQty)+(300*BothLemonQty),"g of Sugar")
        print("You need", (0.1*BothChocoQty)+(0.5*BothLemonQty),"tsp(s) of Baking Powder")
        print("You need", (4*BothChocoQty),"g of Dark Chocolate")
        print("You need", (3*BothLemonQty),"Lemons")
        print("You need", (0.1*BothChocoQty)+(4.5*BothLemonQty),"of Free Ranged Eggs")
        print("You need", (240*BothLemonQty),"ml of Double Cream")
        print("You need", (12.5*BothChocoQty),"ml of Milk")
        print("You need", (0.1*BothChocoQty),"og Orange Juice")
        print("You need", (4*BothChocoQty)+(80*BothLemonQty),"g of Butter")
        print("You need", (1*BothLemonQty),"pinch(es) Of Salt")


    AskFinish = input("Do you want to make any more? Yes or No? ")

    if AskFinish == "Yes":
        Done = False
    elif AskFinish == "No":
        print("Goodbye!")
        Done = True
        exit()
    else:
        print("Sorry unknown Answer")
