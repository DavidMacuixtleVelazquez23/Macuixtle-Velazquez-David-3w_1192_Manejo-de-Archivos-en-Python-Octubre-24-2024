#aqui se imprime el nombre
# '\n' sirve para saltar lineas
print("\nMacuixtle Velazquez David\n")
#Esto ayudara a verificar si el archivo existe para eliminarlo
#Em caso de qe no exista mostrara un mensaje
import os
if os.path.exists("demofile.txt"):
  os.remove("demofile.txt")
else:
  print("el archivo no existe")
  print(" ")
  ![image](https://github.com/user-attachments/assets/4c647014-07a2-455f-8a52-e2712d3673c2)
