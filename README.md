
# Abrimos el archivo en modo lectura ('r')
archivo = open("my_notes.txt", "r")

# Leemos el contenido línea por línea usando readline()
print("Contenido del archivo my_notes.txt:\n")

# readline() lee una línea cada vez; el bucle continúa hasta que no haya más líneas
linea = archivo.readline()
while linea:
    print(linea.strip())  # strip() elimina saltos de línea extras
    linea = archivo.readline()

# Cerramos el archivo después de leer
archivo.close()

# Fin del programa
