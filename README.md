
class Fatura():
    def __init__(self, nI = 0 , descricao = 0 , quantidade = 0, preço =0.):

        self.Numeroitem = nI
        self.Descricao = descricao
        self.Quantidade = quantidade
        self.Preço = preço



resp = Fatura()
print(" - " * 20)
resp.Numeroitem = int(input("digite o numero do produto:"))
resp.Descricao = str(input("Adicione uma descrição:"))
resp.Quantidade = int(input("Quantos são:"))
resp.Preço = int(input("Qual seu preço:"))
print(" - " * 20)
print(" O numero do item é :{} \n a descrição é      :{}\n e tem :{}\n no preço de :{}\n e o seu total é {}".format(resp.Numeroitem, resp.Descricao, resp.Quantidade, resp.Preço,resp.Quantidade * resp.Preço))

class get_valor_fatura(Fatura):
    def __init__(self, total):
        self.total = total
        self.total = resp.Preço * resp.Quantidade
        print("o total é {}".format(self.total))
