numero1 = float(input("digite o primeiro numero"))
numero2 = float(input("digite o segundo numero"))
numero3 = float(input("digite o terceiro numero"))

maior = max(numero1, numero2, numero3)
menor = min(numero1, numero2, numero3)

print("o maior e o menor numero é", maior, menor)





dias = 60
km = 0.15
diaria = float(input(" digite as diarias"))   
km_percorrido = float(input("digite os km"))
      
preço_final = (dias * diaria) + (km * km_percorrido)
print("preço final é:", preço_final)






class Roupas:
    def __init__(self, marca, cor, modelo, tamanho):
        self.marca=marca
        self.cor=cor
        self.modelo=modelo
        self.tamanho=tamanho
class Estoque:
    def __init__(self):
        self.roupas=[]
    def Adicionar_Roupas(self,roupas):
        self.roupas.append(Roupas)
    def Mostrar_Estoque(self):
        for roupas in self.roupas:
            print(f'{roupas.marca}, {roupas.cor}, {roupas.modelo}, {roupas.tamanho} Adicionado ao estoque')
roupa1=Roupas('nike, rosa, camiseta, g')
roupa2=Roupas('adidas, branco, moletom, p')

Estoque()
Estoque.Adicionar_Roupas(roupa1, roupa2)






valor_casa = float(input("digite o valor da casa: R$"))
salario = float(input("digite o salario: R$ "))
anos = float(input("digite a quantidade de anos a pagar :"))

meses = anos + 12
parcelas_mensal = valor_casa / meses 
limite_parcelas = salario * 0.30
if parcelas_mensal <= limite_parcelas:
    print(f"emprestrimo aprovado ! o valor da parcela mensal sera de R$ {parcelas_mensal}") 
else:
    print(f"emprestimo não aprovado. O valor das parcelas mensal seria de R$ {parcelas_mensal} ")




    eposito_inicial = float(input(" digite o valor do deposito inicial"))
taxa_de_juros = float(input(" digite a taxa de juros da poupança"))

total_juros = calcular_poupanca(deposito_inicial, taxa_de_juros)
print(f"\nTotal ganho com juros em 24 meses: R$ {total_juros}")


distancia = float (input("digite a distancia"))
velocidade = int (input("digite a velocidade"))
tempo = velocidade/distancia
print(tempo)



