# cal_trac
Macro tracker with custom food database. 

# insert food items into each meal category to print out sum total of daily caloric intake
    bkfast = sum([]) 
    bkfast.name = 'Breakfast' 
     
    lunch = sum([])
    lunch.name = 'Lunch' 

    dinner = sum([])
    dinner.name = 'Dinner'

    net_total = sum([bkfast,lunch,dinner])
    net_total.name = 'Net Total'

print(bkfast)
print(lunch)
print(dinner)
