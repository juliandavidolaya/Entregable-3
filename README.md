# Entregable-3
titulo, y titulos verticales y horizontales
import matplotlib.pyplot as plt
y=[]
x=[]
for i in range(100):
	y.append(i**2)
	x.append(i)

plt.plot(x,y)
plt.title("Ejemplo de cuadricula")
plt.legend() # agregar el legend al plot


plt.grid(True) # poner grid en la grafica
plt.show()
