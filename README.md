# Calculating IMC with Python

# Enter the values

Peso = float(input('Qual o seu peso?: '))
Altura = float(input('Qual sua altura? (em metros, utilize "." como separador): '))

# Calculate the result

IMC = int(Peso / (Altura**2))

# Showing the results

print('Seu IMC é: ', IMC)
if IMC <= 18.5:
  print('Baixo peso')
elif IMC > 18.5 and IMC < 25:
  print('Peso normal')
elif IMC >= 25 and IMC < 30:
  print('Sobrepeso')
elif IMC >= 30 and IMC < 35:
  print('Obesidade Grau I')
elif IMC >= 35 and IMC < 40:
  print('Obesidade Grau II')
elif IMC >= 40:
  print('Obesidade Grau III')
