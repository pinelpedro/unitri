
class Fatura():
    def __init__(self, nI = 0 , descricao = 0 , quantidade = 0, preço =0. , get_valor_fatura):

        self.Numeroitem = nI
        self.Descricao = descricao
        self.Quantidade = quantidade
        self.Preço = preço
        self.gvf = get_valor_fatura



resp = Fatura()
print(" - " * 20)
resp.Numeroitem = int(input("digite o numero do produto:"))
resp.Descricao = str(input("Adicione uma descrição:"))
resp.Quantidade = int(input("Quantos são:")) 
resp.Preço = int(input("Qual seu preço:"))
resp.gvf = resp.Quantidade * resp.Preço

print(" - " * 20)
print(" O numero do item é :{} \n a descrição é      :{}\n e tem :{}\n no preço de :{}\n e o seu total é {}".format(resp.Numeroitem, resp.Descricao, resp.Quantidade, resp.Preço,resp.gvf))


