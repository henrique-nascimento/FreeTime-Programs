# FreeTime-Programs
Programs that i made in free time / Programas feitos em tempo livre

"""Programa feito em python, projeto proposto pela codeacademy.com como exercicio""" 
 
 hotel_cost(nights):
    
    return 140 * nights

def plane_ride_cost(city):
    if city == "Charlotte":
        return 183
    
    elif city == "Tampa":
        return 220
    
    elif city == "Pittsburgh":
        return 222
    
    elif city == "Los Angeles":
        return 475

def rental_car_cost(days):
    dayCost = 40 * days
 
    if days >= 7:
        dayCost = dayCost - 50
 
    elif days >= 3:
        dayCost = dayCost - 20
    return dayCost 

def trip_cost(city,days,spending_money):
 
    print trip_cost("Los Angeles", 5, 600)
 
    return plane_ride_cost(city) + rental_car_cost(days) + hotel_cost(days) + spending_money
    
