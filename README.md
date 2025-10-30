# E-CPU
The Einstien vCPU is a iterpeter for the imagined Einstein CPU, a mainframe computer I was inspiered to create. It runs on python, if some could compile for other systems that would be nice.
The commands and incstuinion set: MOV, LDR, STR, ADD, SUB, MUL, DIV, COND, EQ, NEQ, GT, LT, GTE, LTE, B, BR, and SYS
Command table:
MOV      moves numbers into a register
LDR      loads predefined data into the specifed register
STR      stores data from a register into a varible(WILL OVERIDE PAST DATA)
ADD      adds the data from two registers and puts them into a varible 
SUB      works like ADD but subtracts instead
MUL      works like ADD but multiplies ninstead
DIV      works like ADD but divieds instead
COND     reqires 4 operands register 1, comparitor, register 2, and label to jump to
comparision for use with COND
EQ       is equal to
NEQ      is not equal to
GT       greater than
LT       less than
GTE      greater than or equal to
LTE      less than or equal to
branching:
B        moves program to selected label
BR       retruns to main label after branching
syscall:
SYS      syscalls (syscalls are prefromed by the cpu due to the Einstein cpu has no OS)
