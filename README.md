# Ansible-samples

This repository contains sample files I used to learn Ansible. Its purpose is to document my learning process.

## YAML explained:
Within Ansible, YAML file is used to represent data, in this case, configuration data.
### Key value Pair
```
Fruit: Apple
Vegetable: Carrot
Liquid: Water
Meat: Chicken
```
### Array/List
```
Fruits:
- Orange
- Apple
- Banana

Vegetables:
- Carrot
- Cauliflower
- Tomato
```
### Dictionary/Map
```
Banana:
    Calories: 105
    Fat: 0.4 g
    Carbs: 27 g

Grapes:
    Calories: 62
    Fat: 0.3 g
    Carbs: 16 g
```
### Key Value/Dictionary/Lists
```
Fruits:
    - Banana:
        Calories: 105
        Fat: 0.4 g
        Carbs: 27 g
    - Grape:
        Calories: 62
        Fat: 0.3 g
        Carbs: 16 g