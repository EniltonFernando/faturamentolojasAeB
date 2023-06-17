# faturamentolojasAeB

faturamento_loja_b = 54000
faturamento_loja_a = 0

for i in range(5):
    valor_compra = float(input("Digite o valor da compra: "))
    faturamento_loja_a += valor_compra

if faturamento_loja_a >= faturamento_loja_b:
    superacao = faturamento_loja_a - faturamento_loja_b
    print("O faturamento da loja A foi superior ao da loja B.")
    print("Superou o faturamento em:", superacao)
else:
    falta = faturamento_loja_b - faturamento_loja_a
    print("O faturamento da loja A não atingiu o da loja B.")
    print("Faltou:", falta)

