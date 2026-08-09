1.lemonadeChange
I had used two variables to check the amount of ten and five notes i had (twenty would never be used for change).when five was the input one would be added to the counter, when 10 was given one was added to ten and one was subtracted from five.
when twenty was recieved if at least one ten was present one was removed from ten and one from five or if ten was not present 3 was removed from five. if five ever become lesser than zero false was returned and if not true wa returned

2.greedyCookie
since maximum children must be fed first both lists were sorted. This allowed it so that the child with the lowest greed factor recieved the cookie with the lowest value.when a child with a greed factor lesser than that of the childs value the child recieves the cookie and the next cookie and child are taken.
If this condition is not satisfied then the next cookie is taken for the same child.The process ends when it runs out of either children to feed or cookies to distribute.