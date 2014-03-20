#!/usr/bin/python
#!ecoding: UTF-8
import modulo

tupla= (10,20,30,40)
#tupla=(10,100,1000,10000,100000,1000000,10000000,10000000,100000000,1000000000)
#tupla=
#tupla=  (1e1,1e2,1e3,1e4,1e5,1e6,1e7,1e8)
lista = []
for i in tupla:
  valor_pi = modulo.calcular_pi (i)
  lista.append (valor_pi)
print lista #primera colunma de la practica 6

pi35 = []
for i in tupla:
  pi35.append (modulo.PI35DT)
dif35 = []
for i in range (len (tupla)):
  dif35.append (abs(pi35[i] - lista[i])) # la lista dif35 es la ultima columna de la practica  6
print "i\tPI35DT\t\tlista i\t\tPI35DT - list a i"
for i in range (len(tupla)):
  print "%d\t%1.10f\t%1.10f\t%1.10f" % (i+1, pi35[i], lista[i], dif35[i])
  
#ESTO ES PARA SABER MAS 
print"Pasando la salida a una matriz...."
print "i\tPI35DT\t\tlista i\t\tPI35DT - lista i" , # 
matriz = []
for i in range (len(tupla)):
  matriz.append ([i+1, pi35[i], lista[i], dif35[i]])
for i in range (len(tupla)):
  print
  print matriz [i][0], #
  for j in rangeee(1,4):
    print "\t%1.10f" % matriz [i][j], #