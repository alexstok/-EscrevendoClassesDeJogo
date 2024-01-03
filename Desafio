# Classe que representa um herói de uma aventura
class Heroi:
    # Construtor da classe
    def __init__(self, nome, idade, tipo):
        self.nome = nome
        self.idade = idade
        self.tipo = tipo

    # Método para realizar o ataque
    def atacar(self):
        # Lógica para determinar o tipo de ataque com base no tipo do herói
        if self.tipo == "mago":
            ataque = "magia"
        elif self.tipo == "guerreiro":
            ataque = "espada"
        elif self.tipo == "monge":
            ataque = "artes marciais"
        elif self.tipo == "ninja":
            ataque = "shuriken"
        else:
            ataque = "ataque desconhecido"

        # Exibe a mensagem do ataque
        print(f"O {self.tipo} atacou usando {ataque}")

# Exemplo de uso da classe
heroi1 = Heroi("Aragorn", 30, "guerreiro")
heroi2 = Heroi("Gandalf", 150, "mago")
heroi3 = Heroi("Bruce Lee", 40, "monge")
heroi4 = Heroi("Hanzo", 28, "ninja")

# Realizando os ataques
heroi1.atacar()
heroi2.atacar()
heroi3.atacar()
heroi4.atacar()
