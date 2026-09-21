# consumo-agua
Um projeto sobre consumo de água utilizando python
Python 3.14.7 (tags/v3.14.7:823f032, Aug  5 2026, 10:51:32) [MSC v.1944 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> # Script de classificação de consumo de água
...
... # Solicita o tipo de imóvel
... tipo_imovel = input("Informe o tipo de imóvel (comercial, casa ou apartamento): ").strip().lower()
...
... # Solicita o consumo mensal de água
... consumo = float(input("Informe o consumo mensal de água em m³: ").replace(",", "."))
...
... # Classificação de acordo com as regras
... if tipo_imovel == "comercial":
...     print("Tarifa comercial aplicada – consulte o plano corporativo.")
...
... elif tipo_imovel == "apartamento":
...     if consumo < 10:
...         print("Consumo econômico – excelente controle de água!")
...     else:
...         print("Consumo elevado para apartamento – atenção ao uso!")
...
... elif tipo_imovel == "casa":
...     if consumo <= 25:
...         print("Consumo dentro da média residencial.")
...     else:
...         print("Consumo elevado para casa – reveja hábitos de uso!")
...
... else:
...     print("Tipo de imóvel não reconhecido.")
...
Informe o tipo de imóvel (comercial, casa ou apartamento): apartamento
Informe o consumo mensal de água em m³: 4.5
Consumo econômico – excelente controle de água!
>>>
[app.py](https://github.com/user-attachments/files/32470566/app.py)
