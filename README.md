# HolaMundo_Mips
#Programa que muestra un "Hola mundo" en mips ensamblador
.data
cadena: .asciiz "Hola Mundo"
cadena2: .asciiz "Segunda Version de Ensamblador"
.text
.globl main
main:
la $a0 cadena
li $v0 4
syscall
la $a0 cadena2
li $v0 4
syscall
li $v0 10
syscall

#Con esta version finaliza los commits del programa "Hola Mundo"


