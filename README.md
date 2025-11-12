# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
MOV A,P0 
MOV R0,A 
MOV B,R0 
MUL AB 
MOV P2,A 
END

```

## OUTPUT
<img width="536" height="324" alt="image" src="https://github.com/user-attachments/assets/c1f4e731-5fdf-4903-a06d-5472910408be" />
<img width="760" height="578" alt="image" src="https://github.com/user-attachments/assets/8fed1d0c-9bb9-430d-8c2c-82481211981d" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END

```


## OUTPUT
<img width="439" height="320" alt="image" src="https://github.com/user-attachments/assets/9e836103-7775-4f2b-8e09-ce197c97eb75" />
<img width="300" height="500" alt="image" src="https://github.com/user-attachments/assets/ebdc9487-4b5d-4868-81c2-c17820c8db47" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
