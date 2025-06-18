# programa-que-suma-y-resta-
primer programa def sumar(a, b):
    return a + b

def restar(a, b):
    return a - b

# Ejemplo de uso
num1 = float(input("Ingrese el primer número: "))
num2 = float(input("Ingrese el segundo número: "))

print("La suma es:", sumar(num1, num2))
print("La resta es:", restar(num1, num2))
def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "Error: No se puede dividir por cero."
    return a / b

def main():
    print("Programa que multiplica y divide dos números.")
    num1 = float(input("Introduce el primer número: "))
    num2 = float(input("Introduce el segundo número: "))

    resultado_multiplicacion = multiplicar(num1, num2)
    resultado_division = dividir(num1, num2)

    print(f"Multiplicación: {num1} * {num2} = {resultado_multiplicacion}")
    print(f"División: {num1} / {num2} = {resultado_division}")

if __name__ == "__main__":
    main()
