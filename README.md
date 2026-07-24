# Calculadora-basica
Calculadora básica en Python diseñada para realizar operaciones aritméticas fundamentales como suma, resta, multiplicación, resto y división de forma rápida y sencilla.
```python
a = int(input('Insertar tu primer número: '))
b = int(input('Insertar tu segundo número: '))
c = input('Insertar la operación que deseas realizar (+, -, *, /, %): ')

if c == '+':
    print('El resultado es: ', a + b)
elif c == '-':
    print('El resultado es: ', a - b)
elif c == '*':
    print('El resultado es: ', a * b)
elif c == '/':
    if b != 0:
        print('El resultado es: ', a / b)
    else:
        print('Error: Divisiones para cero no están permitidas.')
elif c == '%':
    if b != 0:
        print('El resultado es: ', a % b)
    else:
        print('Error: Divisiones para cero no están permitidas.')
else:
    print('Error: Operación inválida. Por favor, usa una de las siguientes: +, -, *, /, %.')
print('Gracias por usar la calculadora!')
```
