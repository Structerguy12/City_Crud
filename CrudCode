db_user = {
    'jackson' : 'London',
    'jack' : 'Norway',
    '1': '1',
    '5': '5'
}

def removeUserDb():
    name = input("Pls user")

    if name in db_user:
        db_user.pop(name)
        print(db_user)
    else:
        print("User hasnt been found")

def PrintUser():
    for key, value in db_user.items():
        print(f"name: {key} and city {value}")

def addUser():
    name = input("Please person")
    city = input("Please city")
    db_user[name] = city


def Updater():
    name = input("Please User")
    if name in db_user:
        Value = db_user[name]
        ac = input("Please city")
        if ac == Value:
            ad = input("Please enter new city")
            db_user[name] = ad
        else:
            print("City isn't correct")
    else:
        print("User doesnt exist")
def Clear():
    db_user.clear()
def FindCityPersons():
    city = input("city -> ")
    for key, value in db_user.items():
        if value.lower() == city.lower():
            print(f"name: {key}")
def main():

    while True:
        print("1 - removeUserDb\n2 - PrintUser\n0 - exit\n3 - AddUser\n4 - Updater-*5* - Clear - *6* - Findallcityperson")
        check = int(input("---> "))
        if check == 1:
            removeUserDb()
        elif check == 2:
            PrintUser()
        elif check == 3:
            addUser()
        elif check == 4:
            Updater()
        elif check == 5:
            Clear()
        elif check == 6:
            FindCityPersons()
        elif check == 0:
            print("Closing program...")
            break
        else:
            print("You havent putten any of the current working numbers. Try again.")

main()
