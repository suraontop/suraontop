def addition(a, b):
    return a + b

def soustraction(a, b):
    return a - b

def multiplication(a, b):
    return a * b

def division(a, b):
    if b == 0:
        return "Division par zéro impossible"
    return a / b

while True:
    print("Options:")
    print("Sélectionnez 'add' pour additionner deux nombres")
    print("Sélectionnez 'sub' pour soustraire deux nombres")
    print("Sélectionnez 'mul' pour multiplier deux nombres")
    print("Sélectionnez 'div' pour diviser deux nombres")
    print("Sélectionnez 'quit' pour quitter le programme")
    user_input = input(": ")

    if user_input == "quit":
        break
    elif user_input == "add":
        num1 = float(input("Entrez le premier nombre: "))
        num2 = float(input("Entrez le deuxième nombre: "))
        print("Résultat: " + str(addition(num1, num2)))
    elif user_input == "sub":
        num1 = float(input("Entrez le premier nombre: "))
        num2 = float(input("Entrez le deuxième nombre: "))
        print("Résultat: " + str(soustraction(num1, num2)))
    elif user_input == "mul":
        num1 = float(input("Entrez le premier nombre: "))
        num2 = float(input("Entrez le deuxième nombre: "))
        print("Résultat: " + str(multiplication(num1, num2)))
    elif user_input == "div":
        num1 = float(input("Entrez le premier nombre: "))
        num2 = float(input("Entrez le deuxième nombre: "))
        print("Résultat: " + str(division(num1, num2)))
    else:
        print("Option invalide")

  
