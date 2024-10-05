g=[];i=int#hace que "g" sea una lista y define i como int
co=int(input("coloca los numeros ganadores "))#hace posible modificar la variable define como int y da una instruccion
for i in range(co):#se repetira hasta que "i" tenga el valor de  "co"
    n=int(input(f"ingresa el numero{i+1}: "))#hace posible modificar la variable define como int da una instruccion la f hace posible realizar operaciones adentro de escrituras
    g.append(n)#añade valor a la lista
g.sort()#ordena alfaveticamente
print("numeros ordenados de mayor a menor ")#imprime si estan ordenados
print(g)#imprime los numeros ordenados
![image](https://github.com/user-attachments/assets/b185f749-e3ea-41bf-b4a6-27382f0b1c1e)
