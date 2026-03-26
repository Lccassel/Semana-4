pontos = 0

resposta = input("Você esteve no local do crime? (sim/não): ").lower()
if resposta == "sim":
    pontos = pontos + 1
else:
    pontos = pontos + 0

resposta = input("Você conhece a vítima? (sim/não): ").lower()
if resposta == "sim":
    pontos = pontos + 1
else:
    pontos = pontos + 0

resposta = input("Você já teve algum desentendimento com a vítima? (sim/não): ").lower()
if resposta == "sim":
    pontos = pontos + 1
else:
    pontos = pontos + 0

resposta = input("Você estava próximo ao local na hora do ocorrido? (sim/não): ").lower()
if resposta == "sim":
    pontos = pontos + 1
else:
    pontos = pontos + 0

resposta = input("Você tem algo que comprove sua inocência? (sim/não): ").lower()
if resposta == "não" or resposta == "nao":
    pontos = pontos + 1
else:
    pontos = pontos + 0

if pontos >= 3:
    print("Pessoa suspeita.")
else:
    print("Pessoa não considerada suspeita.")
