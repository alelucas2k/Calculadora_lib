# AlessandroCalcLib

AlessandroCalcLib é uma biblioteca simples de calculadora que fornece operações matemáticas básicas: soma, subtração, multiplicação e divisão. Esta biblioteca foi desenvolvida em Python e pode ser usada em projetos que necessitem de operações aritméticas simples.


## Funcionalidades

A classe AlessandroCalc inclui os seguintes métodos:

    somar(a, b): Retorna a soma de a e b.
    subtrair(a, b): Retorna a subtração de b de a.
    multiplicar(a, b): Retorna a multiplicação de a por b.
    dividir(a, b): Retorna a divisão de a por b. Caso b seja zero, retorna uma mensagem de erro.


## Uso

Após a instalação, você pode importar e utilizar a biblioteca no seu código Python da seguinte maneira:

    from AlessandroCalculadora import AlessandroCalc

Criação de uma instância da classe AlessandroCalc

    calc = AlessandroCalc()

# Operações básicas(Exemplos)
    print(calc.somar(5, 3))        # Saída: 8
    print(calc.subtrair(10, 4))    # Saída: 6
    print(calc.multiplicar(2, 3))  # Saída: 6
    print(calc.dividir(8, 2))      # Saída: 4
