# faturamentolojasAeB

faturamento_loja_a = 0

# Pedir os valores de cada compra na loja A
for i in range(5):
    valor_compra = float(input("Digite o valor da compra na loja A: "))
    faturamento_loja_a += valor_compra

# Verificar se o faturamento foi superior ao da loja B
if faturamento_loja_a > 54000:
    excedente = faturamento_loja_a - 54000
    print("O faturamento da loja A foi superior ao da loja B.")
    print(f"O faturamento foi excedido em R${excedente:.2f}.")
else:
    faltante = 54000 - faturamento_loja_a
    print("O faturamento da loja A foi inferior ao da loja B.")
    print(f"Faltaram R${faltante:.2f} para atingir o faturamento.")
