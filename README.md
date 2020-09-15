# lab-111
#Pocoaca Argollo Victor kevin  C.I 10065914
#Ejercicio #1
'''Ingrese un tiempo X que estará representado en segundos, luego ingrese el tiempo que tomará 
en realizarse una tarea Z representado en segundos, minutos y horas. Se pide verificar si con el 
tiempo X se puede finalizar la tarea Z'''
h, m, s, x=map(int,input().split())
s2=s+x
if s2 == 60 and m == 59:
	h=h+1
	s2=00
	m=00
	print("Ya finalizo la tarea:", h,m,s2)
else:
	print("Falta para que finalize la tarea:", h,m,s2)
  


#Pocoaca Argollo Victor Kevin C.I 10065914
#Ejercicio #2
''''Utilizando los coeficientes (a, b, c) de una ecuación de segundo grado se pide mostrar la 

naturaleza de sus raíces'''
a, b, c=map(int,input().split())
D = b*2 - 4(a)*(c)
if D>0:
	print("Las raices son reales, diferentes de", D)
else:
	if D==0:
		print("Las raices son reales, iguales de", D)
	else:
		if D<0:
			print("Las raices son Complejas de", D)
      
      
#Pocoaca Argollo Victor Kevin C.I 10065914
#Ejercicio#3
'''Dados 3 valores (horas, minutos y segundos) se pide sumar un segundo.'''
A,b,c=map(int,input().split())

if c==20:

 if b==51:

  if A==16:

   x=A+1

   b=0

   c=0

  else:

   A=0

   b=0

   c=0

 else:

  b=b+1

  c=0

else:

 c=c+1

print(A,b,c)
