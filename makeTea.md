# HOW TO MAKE A STRONG CHAI TEA

## ABOUT

I love chai tea but I like mine very strong so I add an extra black tea bag and it comes out perfect!  
Follow these steps to make a strong chai tea to enjoy.  

## DIRECTIONS

INPUT  

- Enter number of cups of tea required  

GET INGREDIENTS

- Gather enough ingredients for each cup of tea required  

GET EQUIPMENT

- If more than one cup is required get teapot and number of cups required

PREPARE TEA

- Fill kettle with number of required cups of water  
- Plug in and turn on kettle  
- Open tea bags  
- Tie together with strings  
- Pull off paper tab  
- Put paper into trash  
- Add tea bags to brew container  
- When the water is done heating, pour into brew container  
- Allow to brew at least 5 mins, longer if preferred  
- Remove tea bags with spoon and squeeze over brew container  
- Put tea bags in trash  
- If you used the teapot pour tea into individual cups  
- Add desired add ins into cups  
- Stir with spoon to mix/cool tea  
- Drink and enjoy  

## INIT

1. **INGREDIENTS** - consumable items  
    - *water* - filtered water
    - *teaBags*  
        - *doubleChaiTea* - Stash Double Chai Spice Tea Bags  
        - *blackTea* - Stash English Breakfast Tea Bags  
    - *addIns* - additional optional ingredients  
        - *milk*  
        - *sugar*
        - *honey*  

2. **EQUIPMENT** - non-consumable items  

    - *kettle* - electric kettle to heat water
    - *container* - a place to brew the tea  
        - *teapot*
        - *cup*
    - *spoon* - teaspoons
    - *trashCan* - vessel to dispose of waste  

3. **OTHER ELEMENTS**

    - *teaChef* - person making the tea  
    - *numCups* - number of cups being made  

## START

input: numCups  
getIngredients x numCups  
getEquipment  
    IF numCups is >= 2  
    THEN get teapot and numCups x cups  
    ELSE get cup  
    ENDIF  
fillKettle with numCups of water  
plugInKettle  
startKettle  
open teaBags  
tie teaBags  
put teaBags in container  
    IF numCups is = 1  
    THEN put tea bags into cup  
    ELSE put tea bags into teapot  
    ENDIF  
whenHot pour water into container  
    IF numCups is = 1  
    THEN pour water into cup  
    ELSE pour water into teapot  
    ENDIF  
brew for => 5 minutes  
remove teaBags from container  
put teaBags in trash  
    IF numCups => 2  
    THEN pour tea from teapot into numCups cups  
    ELSE move to next step  
    ENDIF  
add addIns to cups as requested  
stir with spoon  
cool
drink

## END
