VARIABLES

INPUT:
numCups: (number of cups of tea required)

SUPPLIES:
doubleChaiTea: Double chai tea bags
blackTea: Black tea bags
kettle: Electric kettle
container: (teapot, cup)
addIns: (milk, sugar, honey)
spoon: teaspoons

PROGRAM: Make strong chai tea

START

INPUT: Enter number of cups of tea required

GET: SUPPLIES
kettle
addIns
numCups doubleChaiTea, blackTea, spoon, cup
IF numCups is >=  2
THEN get container: teapot
ELSE move to next step
ENDIF

Fill kettle with numCups of water
Plug in kettle
Start kettle

Open all tea bags
Tie all tea bags together by strings

IF numCups is = 1
THEN put tea bags into container: cup
ELSE put tea bags into container: teapot
ENDIF

When kettle is done heating

IF numCups is = 1
THEN pour hot water into container: cup
ELSE pour water into container: teapot
ENDIF

Brew for => 5 minutes

IF numCups => 2
THEN pour tea from teapot into numCups cups
ELSE move to next step
ENDIF

ADD addIns to cups as requested.

Stir with spoon

Allow to cool to temp of choosing

Drink and enjoy your strong chai tea

END