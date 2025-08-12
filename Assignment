# MD. Shafiul Alam Tanjir 232-141-016
# Ashraf Uddin 232-141-010
BCC=2
FCC=4
print("Select Type of Crystal.")
print("1. BCC")
print("2. FCC")
while True:
    #Selecting type of Crystal.
    choice=input("Enter choice(1/2):")
    #Cheking if choice is one of the two options.
    if choice in ("1","2"):
        try:
            p=float(input("Enter the value of density(kg/m^3):"))#p=density
            Mat=float(input("Enter the value of atomic mass(kg/mol):"))#Mat= Atomic Mass
            Na=float(input("Enter the value of Avogadro's Number(atoms/mol):"))#Na= Avogradro's Number
        except ValueError:
            print("Invalid input. Please enter a number.")
            continue
        if choice=="1":
            a3=(BCC*Mat)/(p*Na)
            a=a3**(1/3)
            print(f"Latice Parameter(a)={a} m")
            print(f"Atomic Radius(R)={3**0.5/4*a} m")
            print(f"Atomic Concentration={BCC/(a3*10**6)} atoms/cm^3")
        elif choice=="2":
            b3=(FCC*Mat)/(p*Na)
            b=b3**(1/3)
            print(f"Latice Parameter(a)={b} m")
            print(f"Atomic Radius(R)={2**0.5/4*b} m")
            print(f"Atomic Concentration={FCC/(b3*10**6)} atoms/cm^3")
        next_calculation = input("Let's do next calculation? (yes/no): ")
        if next_calculation == "no":
            break
    else:
        print("Invalid Input")
