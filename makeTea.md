# PROGRAM: Make strong chai tea

## VARIABLES

**numCups** - *number of cups of tea required*

### SUPPLIES

1. **doubleChaiTea** - *Double chai tea bags*
2. **blackTea** - *Black tea bags*
3. **kettle** - *Electric kettle*
4. **container**
    * 4a. **teapot**
    * 4b. **cup**
5. **addIns**
    * 5a. **milk**
    * 5b. **sugar**
    * 5c. **honey**
6. **spoon** - *teaspoons*

## START

INPUT: *numCups*
> Enter number of cups of tea required

GET SUPPLIES

* kettle
* doubleChaiTea
* blackTea
* spoon
* addIns
* container  

    IF *numCups* is >= 2  
    THEN get container *teapot* and *numCups* cups
    ELSE get container *cup*  
    ENDIF

PREPARE TEA
>Fill kettle with *numCups* of water  
>Plug in kettle  
>Start kettle  
>Open all tea bags  
>Tie all tea bags together by strings  
>Put tea bags in *container*  

    IF numCups is = 1  
    THEN put tea bags into container: cup  
    ELSE put tea bags into container: teapot  
    ENDIF  
>When kettle is done heating  

    IF numCups is = 1  
    THEN pour water into container: cup  
    ELSE pour water into container: teapot  
    ENDIF  

>Brew for => 5 minutes  
>Remove tea bags if desired  
    
    IF numCups => 2
    THEN pour tea from teapot into numCups cups
    ELSE move to next step
    ENDIF

>Add addIns to cups as requested  
>Stir with spoon  
>Allow to cool to temp of choosing  
>Drink and enjoy your strong chai tea

END
