import matplotlib.pyplot as plt
# Coordenadas de la letra D
x = [0, 0, 0, 0, 1, 2, 2.5, 2.4, 1, 0]  # puntos en X
y = [0, 1, 2.4, 3, 3.2, 3, 2, 1, 0, 0]  # puntos en Y

 #Dibujar la D
plt.plot(x, y, linewidth=4)
plt.axis('equal')     # Proporción 1:1
plt.grid(True)
plt.title("Letra D en gráfica")
plt.show()