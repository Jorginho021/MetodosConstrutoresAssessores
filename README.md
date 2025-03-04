# MetodosConstrutoresAssessores
Trabalho! 2

1)class Carro
    def __init__(self, marca, modelo, ano, preco):
        self.marca = marca
        self.modelo = modelo
        self.ano = ano
        self.preco = preco

    def get_marca(self):
        return self.marca

    def get_modelo(self):
        return self.modelo

    def get_ano(self):
        return self.ano

    def exibir_informacoes(self):
        print(f"Marca: {self.marca}")
        print(f"Modelo: {self.modelo}")
        print(f"Ano: {self.ano}")
        print(f"Preço: R$ {self.preco:.2f}")

2)class Livro:
    def __init__(self, titulo, autor, anoPublicacao, genero):
        self.titulo = titulo
        self.autor = autor
        self.anoPublicacao = anoPublicacao
        self.genero = genero

    def get_titulo(self):
        return self.titulo

    def get_autor(self):
        return self.autor

    def get_anoPublicacao(self):
        return self.anoPublicacao

    def pertence_ao_genero(self, genero):
        return self.genero.lower() == genero.lower()

3)class Produto:
    def __init__(self, nome, preco):
        self.nome = nome
        self.preco = preco
        self.quantidade = 0

    def get_nome(self):
        return self.nome

    def get_preco(self):
        return self.preco

    def get_quantidade(self):
        return self.quantidade

    def aumentar_quantidade(self, quantidade):
        if quantidade > 0:
            self.quantidade += quantidade

    def diminuir_quantidade(self, quantidade):
        if 0 < quantidade <= self.quantidade:
            self.quantidade -= quantidade

4)class Produto:
    def __init__(self, nome, preco):
        self.nome = nome
        self.preco = preco
        self.quantidade = 0

    def get_nome(self):
        return self.nome

    def get_preco(self):
        return self.preco

    def get_quantidade(self):
        return self.quantidade

    def aumentar_quantidade(self, quantidade):
        if quantidade > 0:
            self.quantidade += quantidade

    def diminuir_quantidade(self, quantidade):
        if 0 < quantidade <= self.quantidade:
            self.quantidade -= quantidade

5)class ContaBancaria:
    def __init__(self, numeroConta, nomeTitular):
        self.numeroConta = numeroConta
        self.nomeTitular = nomeTitular
        self.saldo = 0.0

    def get_numeroConta(self):
        return self.numeroConta

    def get_nomeTitular(self):
        return self.nomeTitular

    def get_saldo(self):
        return self.saldo

    def depositar(self, valor):
        if valor > 0:
            self.saldo += valor

    def sacar(self, valor):
        if 0 < valor <= self.saldo:
            self.saldo -= valor

