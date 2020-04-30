import re
import math
while True:
	
	expresion=r'^([0-9]+|[a-z]+)\s(\+|\-|\*|\/|[a-z]+)\s([0-9]+|[a-z]+)$'
	ex=r'^([a-z]+)\s([0-9]+)$'
	resultado=re.compile(expresion)
	resultados=re.compile(ex)
	prueba=raw_input("Inserte la operacion: ")
	if prueba=="":
		break
	busqueda=re.search(resultado,prueba)
	busquedas=re.search(resultados,prueba)
	if busqueda:
		print busqueda.group(1)
		n1=busqueda.group(1) 
		
		print busqueda.group(2)
		op=busqueda.group(2)
		print busqueda.group(3)
		n2=busqueda.group(3)
		
			
		if n1=="uno":
			n1=1
		if n1=="dos":
			n1=2
		if n1=="tres":
			n1=3
		if n1=="cuatro":
			n1=4
		if n1=="cinco":
			n1=5
		if n1=="seis":
			n1=6
		if n1=="siete":
			n1=7
		if n1=="ocho":
			n1=8
		if n1=="nueve":
			n1=9
		if n1=="cero":
			n1=0
			
		if op=="mas":
			op= "+"		
		if op=="menos":
			op= "-"
		if op=="por":
			op= "*"
		if op=="entre":
			op= "/"
	    	
			
		if n2=="uno":
			n2=1
		if n2=="dos":
			n2=2
		if n2=="tres":
			n2=3
		if n2=="cuatro":
			n2=4
		if n1=="cinco":
			n2=5
		if n2=="seis":
			n2=6
		if n2=="siete":
			n2=7
		if n2=="ocho":
			n2=8
		if n2=="nueve":
			n2=9
		if n2=="cero":
			n2=0
	
	try:	
			n1=int(n1)		
			n2=int(n2)	
						
		
			if op=="+" or "-" or "*" or "/":
				if op=="+" or op=="mas":
					r=n1+n2
				elif op=="-" or op=="menos":
					r=n1-n2
				elif op=="*" or op=="por":
					r=n1*n2
				elif op=="/" or op=="entre":
					r=n1/n2
				
					
				print "La solucion es: ",r	
		
	except:
		print ("qr \nERROR.VUELVE A INTENTARLO")
