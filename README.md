<div style="border-radius:10px; border:#808080 solid; padding: 15px; background-color:##F0E68C ; font-size:100%; text-align:left">

## 📊 Dataset Overview: NFL Draft Prediction

### Dataset Summary
- **Number of rows**: 2781 Player.
- **Number of columns**: 15 features + 1 Target variable.
- **Target Variable**: Drafted (0,1).


### 🔍 Objective

the Goal of this project is to predict whether a player was Drafted or not using multiple models.

### ✅ Dataset characteristics

- **No duplicates**.
- **Missing values**: Missing values exist in **Age** , **sprint_40yd** , **Vertical_Jump** , **Bench_Press_Reps** , **Broad_Jump**, **Agility_3cone** , **Shuttle**.
- Mix of **categorical** and **numerical** data types.
- Variables represent Player: **athletic ability** , **college performance**, **playing position** and More.

### 🧾 Feature List

| Column Name        | Description                        |
|--------------------|------------------------------------|
| `Year`             | The year the record corresponds to |
| `Age`              | Player age                         |
| `School`           | Player School                      |
| `Height`           | Player Height in `cm's`            |
| `Weight`           | Player Weight in `Kg's`            |
| `Sprint_40yd`      | 40-yard dash time                  |
| `Vertical_Jump`    |Vertical jump reach                 |
| `Bench_Press_Reps` |Number of bench press repetitions   |
| `Broad_Jump`       |Broad jump distance                 |
| `Agility_3cone`    |3-cone drill time                   |
| `Shuttle`          |20-yard shuttle time                |
| `Player_Type`      |Broad role category (offense, defense, special teams)              |
| `Position_Type`    |Position type                       |
| `Position`         |Specific position                   |
| `Drafted`          |Whether the player was drafted      |
