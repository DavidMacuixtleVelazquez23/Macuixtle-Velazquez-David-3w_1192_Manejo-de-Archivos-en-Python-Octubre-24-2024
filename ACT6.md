#aqui se imprime el nombre
# '\n' sirve para saltar lineas
print("\nMacuixtle Velazquez David\n")
#Esto ayuda a sobreescribir el contenido
f = open("demofile3.txt", "w")
f.write("el contendo a sido cambiado!!!!!!")
f.close()

#open and read the file after the overwriting:
f = open("demofile3.txt", "r")
print(f.read())
print(" ")
![image](https://github.com/user-attachments/assets/8fd49c79-6a7e-4568-b61a-00ea5161ac71)
