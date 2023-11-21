# Explanation :
Can see the course here : [Link to course](https://eduservices-my.sharepoint.com/:w:/g/personal/elliot_louveau_eduservices_org/ERng3u67HqpMgvY_fjiHRFYBri0ky72mv0jzRf4Rs6Vvtg?e=47xq9Q&isSPOFile=1)

Can see the exercises here : [Link to exercise](https://eduservices-my.sharepoint.com/:w:/g/personal/elliot_louveau_eduservices_org/EewT5IZpPspKuOGd8_Oa_HwBb01_1YrOX8l8s5efe0sTng?e=xgTq2z&wdOrigin=TEAMS-WEB.teams.chiclet&wdExp=TEAMS-CONTROL&wdhostclicktime=1698336596927&web=1)


# Exercises of Proposition et connecteurs logiques:

Exercise from 3.4 to 3.23.

## Index :

Ᵽ = P barre\
Ꝙ = Q barre\
⋂ = Porte "Et"\
U = porte "Ou"

## Exo 3.4 :
```
A - P ⋂ Ꝙ

B - Ᵽ ⋂ Ꝙ

C - P U (Q ⋂ Ᵽ)

D - (Q ⋂ P) U (Q ⋂ Ᵽ)
```

## Exo 3.5 :
```
A-  F
B-  T
C-  T
D-  T
E-  T
F-  F
```

## Exo 3.6 :
```
A-  F
B-  T
C-  F
D-  T
E-  F
F-  T
```

## Exo 3.16 :
```a-
    A- 1+1+0 = 1+0 = 1
    B- (0*0) + 1 = 1
    C- (0+1) * 0 = 0
b-
    A- 
    B-
    C-
c-
    A-
    B-
    C-
```

## Exo 3.19 :
```
A-
    0+0+1*1 = 1
    0+1+1*0 = 1
    1+0+0*1 = 1
    1+1+1*1 = 1
B-
    (0+0)*1*1 = 0
    (0+1)*0*1 = 0
    (1+0)*1*0 = 0
    (1+1)*0*0 = 0
```

## Exo 3.22 :
```
[WIP]
```

## Exo 3.23 :
```
[WIP]
```


# Exercises Tableau de Karnaugh:

## Index :
Ā̅ = not(A)

B̅ = not(B)

C̅ = not(C)

## Exo 3.24 :

### A) :

Equation : A + $\overline{A}$*B = A + B

For A + $\overline{A}$*B :

Since the equation start by A then you put everything to 1 in the column A:

|            | A            | $\overline{A}$|
|------------|------------  | ------------  |
| **B**      |      1       | X             |
| $\overline{B}$ | 1        | X             |

Then the equation have $\overline{A}$ * B so you put the value 1 where $\overline{A}$ and B are matching

|            | A            | $\overline{A}$|
|------------|------------  | ------------  |
| **B**      |      1       | 1             |
| $\overline{B}$ | 1        | 0             |

For A + B :

Put the value 1 to all value in the column A and in the row B :
|            | A            | $\overline{A}$|
|------------|------------  | ------------  |
| **B**      |      1       | 1             |
| $\overline{B}$ | 1        | 0             |

We have the same result so we proove by using a Kernaugh Table that's work.

### B) :

Equation : A + B + $\overline{A}$*$\overline{B}$ = 1

For A + B :

|            | A            | $\overline{A}$|
|------------|------------  | ------------  |
| **B**      |      1       | 1             |
| $\overline{B}$ | 1        | 0             |

Then $\overline{A}$*$\overline{B}$ :

|            | A            | $\overline{A}$|
|------------|------------  | ------------  |
| **B**      |      1       | 1             |
| $\overline{B}$ | 1        | 1             |

The result mean for any value the result will be True (1).

## Exo 3.25 :
### A) :
#### Expression A :

|               | AB | A $\overline{B}$ | $\overline{A}$ B  | $\overline{A}$ $\overline{B}$ |
| --            | - | - | - | - |
| **C**         | 1 | 0 | 0 | 0 |
| $\overline{C}$| 1 | 1 | 1 | 1 |

#### Expression B :

|               | AB | A $\overline{B}$ | $\overline{A}$ B  | $\overline{A}$ $\overline{B}$ |
| --            | - | - | - | - |
| **C**         | 1 | 0 | 1 | 1 |
| $\overline{C}$| 0 | 0 | 1 | 1 |


### B) :

The Expression $\overline{A}$ should be write like this :
C*$\overline{A}$ + C*$\overline{B}$

The Expression $\overline{B}$ should be write like this :
*A*$\overline{B}$ + A*B*$\overline{C}$

## Exo 3.26 :

### A) :
#### Expression A :

|               | AB | A $\overline{B}$ | $\overline{A}$ B  | $\overline{A}$ $\overline{B}$ |
| --            | - | - | - | - |
| **C**         | 1 | 1 | 0 | 1 |
| $\overline{C}$| 1 | 1 | 0 | 0 |

#### Expression B :

|               | AB | A $\overline{B}$ | $\overline{A}$ B  | $\overline{A}$ $\overline{B}$ |
| --            | - | - | - | - |
| **C**         | 0 | 1 | 1 | 1 |
| $\overline{C}$| 1 | 0 | 1 | 0 |

### B) :

The Expression $\overline{A}$ should be write like this :
$\overline{A}$*B* + $\overline{A}$*$\overline{B}$*$\overline{C}$

The Expression $\overline{B}$ should be write like this :
ABC + *A*$\overline{B}$*$\overline{C}$* + $\overline{A}$*$\overline{B}$*$\overline{C}$

## Exo 3.27 :
## Exo 3.29 :
### A) :
En logique cette loi est l'inverse de l'équivalence
### B) :
### C) :
## Exo 3.32 :

|               | AB | A $\overline{B}$ | $\overline{A}$ B  | $\overline{A}$ $\overline{B}$ |
| --            | - | - | - | - |
| **C**         | 0 | 1 | 0 | 1 |
| $\overline{C}$| 0 | 1 | 0 | 1 |

The Expression $\overline{A}$ can be writen like this : $\overline{B}$
## 3.36 :
