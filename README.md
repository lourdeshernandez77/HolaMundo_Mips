# HolaMundo_Mips
#Programa que muestra un "Hola mundo" en mips ensamblador
.data
cadena: .asciiz "Hola Mundo"
.text
.globl main
main:
la $a0 cadena
li $v0 4
syscall
li $v0 10
syscall
#Primera Version

