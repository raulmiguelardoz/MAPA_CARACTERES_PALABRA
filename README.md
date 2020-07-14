# MAPA_CARACTERES_PALABRA
def mapa_caracteres(palabra):
	lista=list(palabra)
	lista_unica=[]
	nueva_lista=[]
	for i in lista:
		if i not in lista_unica:
			lista_unica.append(i)
	for i in lista:
		nueva_lista.append(lista_unica.index(i))
	print(nueva_lista)


mapa_caracteres("abcd")
print("---------------------")
mapa_caracteres("aabbb")
print("---------------------")
mapa_caracteres("zagzdaa")
print("---------------------")
mapa_caracteres("baaacbb")
