altura = float(input("digite sua altura:"))
peso = float(input("digite seu peso"))
IMC = peso / (altura**2)
print(f"seu IMC é {IMC:.2f}")
if IMC < 18.5:
    print("abaixo do peso")
elif IMC >= 18.5 and IMC <= 24.9:
    print("peso normal")
elif IMC >= 25 and IMC <= 29.9:
    print("sobrepeso")
elif IMC >= 30:
  print("obesidade")
