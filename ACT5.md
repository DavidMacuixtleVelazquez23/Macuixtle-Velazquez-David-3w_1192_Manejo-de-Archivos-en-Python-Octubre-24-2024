#aqui se imprime el nombre
# '\n' sirve para saltar lineas
print("\nMacuixtle Velazquez David\n")
#esto sirve para anexar y si en caso no existe contenido lo crea
f = open("demofile2.txt", "a")
f.write("nuevo contenido creado")
f.close()

#abre el contenido del archivo
f = open("demofile2.txt", "r")
print(f.read())
print(" ")
![image](https://github.com/user-attachments/assets/d2837409-1734-44a3-aff0-a51ef8087d95)
