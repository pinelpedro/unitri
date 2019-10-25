class Fatura():
    def __init__(self, nI = 0 , descricao = 0 , quantidade = 0, preço =0.):

        self.Numeroitem = nI
        self.Descricao = descricao
        self.Quantidade = quantidade
        self.Preço = preço


meu = Fatura()
meu.Quantidade

class respostas():
    def __init__(self,r1,r2,r3,r4):
        self.r1 = input(int("qual o numero do item?"))
        self.r2 = input(str("qual a sua descrição?"))
        self.r3 = input(int("quantos eram?"))
        self.r4 = input(int("qual seu preço tolal"))
    #atribuição
        self.Numeroitem = self.r1
        self.Descricao = self.r2
        self.Quantidade = self.r3
        self.Preço = self.r4

class imprime():
    pass

class get_valor_fatura():
    def __init__(self, total):
        self.total = total
        total = self.Quantidade * self.Preço
        print(total)
