# World
#Condition of World
def world():
    if water == "good" and air == "fresh" and trees == "afforestation":
        print("The world is in good condition and it will protect you")
    else:
        print("You are destroying the world and the world will destroy you")
water = input("Enter the water condition(polluted or good):")
air = input("Enter the condition of air(fresh or polluted):")
trees = input("Enter the condition of trees(afforestation or deforestation):")
world()
