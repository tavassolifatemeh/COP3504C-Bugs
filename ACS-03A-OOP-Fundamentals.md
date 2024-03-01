Slide #2

On the code snippet for proggy.py, the user attempts to change the name of the Monster object pika by using
pika._name = "Chuchu" when the variable is defined as self.name in Monster.

Assuming that a level of privacy is wanted by the class Monster, I would suggest changing the self.name variable
in Monster to self._name to be consistent with the privacy levels of the other variables within the class. Or the
user could change the code in proggy.py to pika.name = "Chuchu" without changing the Monster class code.

Wesley Chen

Slide #3

On the code snippet for proggy.py, the user attempts to create a new Player object named Ashley using
Ashley Player().

To actually create the object and assign it to a variable named Ashley, I would suggest that the code
be changed to Ashley = Player().

Wesley Chen

Slide #15

On the code snippet for monster.py, the user attempts to access the enemy character's level using 
enemy.level) -- which does not compile.

To correctly access the enemy character's level, I would suggest removing the ) at the end in order
for the code to compile and access the enemy's level. 

Wesley Chen
