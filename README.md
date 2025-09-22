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
```asm
ORG 00H
MOV RO, #50H
MOV A. @R0
MOV B, A
MUL AB
INC R0
MOV @R0, A
END
```

## OUTPUT
<img width="1090" height="677" alt="image" src="https://github.com/user-attachments/assets/6b3b878b-65c7-404c-9485-6bb4cc2acea6" />

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
```asm
0RG 00H
MOV RO, #50H
MOV A, @R0
MOV B, A
MUL AB
MOV B, @R0
MUL AB
INC R0
MOV @R0, A
INC R0
MOV @R0, A
END
```


## OUTPUT

<img width="1096" height="684" alt="image" src="https://github.com/user-attachments/assets/bb5cf287-22ed-49ae-b192-c5ef0ede98fc" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
