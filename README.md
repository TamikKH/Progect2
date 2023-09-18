# Progect2
<<<<<<< HEAD
Хетагуров Тамерлан Аланович
Группа пиж-б-о-22-1
Дисциплина: Основы программной инженерии
```
class Otrezok():
    def __init__(self, corx1, corx2, cory1, cory2, ):
        self.corx1 = corx1
        self.corx2 = corx2
        self.cory1 = cory1
        self.cory2 = cory2

    def dlinna(self):
        self.dl = ((max(self.corx1, self.corx2) - min(self.corx1, self.corx2)) ** 2 + (max(self.cory1, self.cory2) - min(self.cory1, self.cory2)) ** 2) ** 0.5
    def rast(self):
        self.rast1 = (self.corx1 ** 2 + self.cory1 ** 2) ** 0.5
        self.rast2 = (self.corx2 ** 2 + self.cory2 ** 2) ** 0.5
Otrezok1 = Otrezok(int(input()),int(input()),int(input()),int(input()))
Otrezok1.dlinna()
Otrezok1.rast()
print(Otrezok1.dl, Otrezok1.rast1, Otrezok1.rast2)
```
