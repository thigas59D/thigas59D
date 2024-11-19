´´´python

class Desenvolvedor:
    pass

class SobreMim(Desenvolvedor):
    def __init__(self):
        self.nome = "Thiago Albuquerque"
        self.area = "Estudante e Editor"
        self.contato = "thiago.a.jesus323@gmail.com"
        self.hobbies = ["Ler livros", "Escutar músicas"]

class Skills(Desenvolvedor):
    def __init__(self):
        self.linguagens = ["Python", "HTML"]

sobre_mim = SobreMim()
skills = Skills()

print(f"Nome: {sobre_mim.nome}")
print(f"Área: {sobre_mim.area}")
print(f"Contato: {sobre_mim.contato}")
print(f"Hobbies: {', '.join(sobre_mim.hobbies)}")
print(f"Linguagens: {', '.join(skills.linguagens)}")
´´´
