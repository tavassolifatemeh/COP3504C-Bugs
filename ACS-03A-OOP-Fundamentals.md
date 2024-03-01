Slide #2

On the code snippet for proggy.py, the user attempts to change the name of the Monster object pika by using
pika._name = "Chuchu" when the variable is defined as self.name in Monster.

Assuming that a level of privacy is wanted by the class Monster, I would suggest changing the self.name variable
in Monster to self._name to be consistent with the privacy levels of the other variables within the class. Or the
user could change the code in proggy.py to pika.name = "Chuchu" without changing the Monster class code.

Wesley Chen
