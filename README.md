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
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```

## OUTPUT
<img width="609" height="578" alt="Screenshot 2025-09-24 212920" src="https://github.com/user-attachments/assets/be55ecf1-97e0-422c-8319-729d9b5f1516" />
<img width="829" height="573" alt="Screenshot 2025-09-24 212933" src="https://github.com/user-attachments/assets/2630f5dc-5164-4725-b644-3fd3bff8b4af" />


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
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOV B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```


## OUTPUT
<img width="319" height="540" alt="Screenshot 2025-09-24 214426" src="https://github.com/user-attachments/assets/df25e159-be8d-417f-8b09-b70eae80f82b" />
<img width="821" height="588" alt="Screenshot 2025-09-24 214437" src="https://github.com/user-attachments/assets/69be1afa-c8c9-4aae-b128-92987786260c" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
