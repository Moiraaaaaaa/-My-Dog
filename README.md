class Chien:
    def __init__(self, nom, race):
        self.nom = nom
        self.race = race

    def aboyer(self):
        print(f"{self.nom} le {self.race} dit : Ouaf !")

chien1 = Chien("Snoopi", "tea cup poodle")
chien1.aboyer()


