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
ORG 00H	
	MOV R0 , #40H
	MOV A,@R0
	MOV B,A
	MUL AB
	INC R0
	MOV @ R0,A
	INC R0
	MOV @ R0,B
	END
```

## OUTPUT
<img width="707" height="365" alt="image" src="https://github.com/user-attachments/assets/d18e5946-7e61-49a2-a956-0b0db2814a73" />


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
ORG 00H	
    MOV R0, #40H     
    MOV A, @R0       
    MOV B, A
    MUL AB           
    INC R0
    MOV @R0, A       
    INC R0
    MOV @R0, B       
    MOV A, 41H       
    MOV B, 40H       
    MUL AB           
    INC R0
    MOV @R0, A       
    INC R0
    MOV @R0, B       
    END
```


## OUTPUT
<img width="777" height="401" alt="image" src="https://github.com/user-attachments/assets/c415afad-99a4-4cb4-8ba7-7aeb16c74a23" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
