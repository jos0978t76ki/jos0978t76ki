- 👋 Hi, I’m @jos0978t76ki
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
jos0978t76ki/jos0978t76ki is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def suma(a, b):
    return a + b

def resta(a, b):
    return a - b

def multiplicacion(a, b):
    return a * b

def division(a, b):
    if b != 0:
        return a / b
    else:
        return "Error: No se puede dividir por cero"

def calculadora():
    print("Calculadora Simple")
    print("Operaciones disponibles:")
    print("1. Suma")
    print("2. Resta")
    print("3. Multiplicación")
    print("4. División")
    
    operacion = input("Seleccione la operación (1/2/3/4): ")
    
    num1 = float(input("Ingrese el primer número: "))
    num2 = float(input("Ingrese el segundo número: "))
    
    if operacion == '1':
        print("Resultado:", suma(num1, num2))
    elif operacion == '2':
        print("Resultado:", resta(num1, num2))
    elif operacion == '3':
        print("Resultado:", multiplicacion(num1, num2))
    elif operacion == '4':
        print("Resultado:", division(num1, num2))
    else:
        print("Operación no válida")


