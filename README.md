# Reto6

1. Dado la figura de la imagen, desarrolle:

Una función matemática para calcular el volumen y el área superficial.
Cree dos funciones en python para calcular los valores antes establecidos, al ingresar por teclado r1, r2 y h.
Revise como utilizar el valor de pi usando import math y math.pi

- Desarrollo
  ```
  n = float(input("Ingrese el radio1: "))
  y = float(input("Ingrese el radio2: "))
  z = float(input("Ingrese altura h: "))
  import math 
  x = math.pi

  def area_superficial_y_volumen(n, x, z, y): 
      d= (2*x*n**2)+(x*z*n)
      e= (((4*x)/3)*n**3)+((1/3)*y**2*z*x)
    return d, e
  print("El area superficial y volumen son: ", area_superficial_y_volumen(n, x, z, y), "unidades cubicas y unidades cuadradas respectivamente")
  ```
  
 2.  Dado la figura de la imagen, desarrolle:

Una función matemática para calcular el área y el perimetro.
Cree dos funciones en python para calcular los valores antes establecidos, al ingresar por teclado r, a y b.
Revise como utilizar el valor de pi usando import math y math.pi

```
r = (float(input("Ingrese el radio de la circunferencia: "))) 
a = (float(input("Ingrese el largo del rectangulo: ")))
b = (float(input("Ingrese el ancho de la circunferencia: ")))
import math
area_ = ((2*math.pi*r**2)+(b*a))
perimetro_ = ((2*math.pi*2*r)+(2*b+2*a))
def area_y_perimetro(r, a, b):
    area_
    perimetro_ 
    return area_, perimetro_
print("El area y perimtrop de la figura son: ",area_y_perimetro(r, a, b))
```
3. Diseñe una función que calcule la cantidad de carne de aves en kilos si se tienen N gallinas, M gallos y K pollitos cada uno pesando 6 kilos, 7 kilos y 1 kilo respectivamente.
   ```
   N = float(input("Ingrese numero de gallinas: "))
   M = float(input("Ingrese numero de gallos: "))
   K = float(input("Ingrese numero de pollitos: "))

   carne_de_aves = (6*N+7*M+K)
   def cant_carne_aves(N, M, K):
       return carne_de_aves
   print("La cantidad de carne de aves en kilos es: ",cant_carne_aves(N, M, K))
   
   ```
 4.  Mi mamá me manda a comprar P panes a 300 cada uno, M bolsas de leche a 3300 cada una y H huevos a 350 cada uno. Hacer un programa que me diga las vueltas (o lo que quedo debiendo) cuando me da un billete de B pesos.
```
P = float(input("Ingrese numero de panes: "))
M =float(input("Ingrese numero de bolsas de leche: "))
H = float(input("Ingrese numero de huevos: "))
B = float(input("¿De cuanto es el billete recibido?: "))

vueltas_ = (B-(P*300+M*3300+H*350))
def vueltas_sobrante(P,H,M,B):
    return vueltas_ 
print("El excedente es: ",vueltas_sobrante(P,H,M,B))    
   ```

 5. Haga un programa que utilice una función para calcular el valor de un préstamo C usando interés compuesto del i por n meses.
  ```
c = float(input("Ingrese el monto del préstamo: "))
i = float(input("Ingrese la tasa de interés(unicamente el valor): "))
n = float(input("Ingrese numero de meses: "))

def valor_final_prestamo(c, i, n):
    a = c*(1+i)**n
    return a
print ("El valor final a pagar por el prestamo es: ", valor_final_prestamo(c, i, n))
```
    
 6. El número de contagiados de Covid-19 en el país de NuncaLandia se duplica cada día. Hacer un programa que diga el número total de personas que se han contagiado cuando pasen D días a partir de hoy, si el número de contagiados actuales es C.
   ```
D =float(input("Ingrese un numero de días: "))
N = float(input("Ingrese un numero de contagiados: "))

def numero_contagiados(N, D):
    a= N*(2**(D-1))
    return a
print("El numero de contagiados es: ",numero_contagiados(N, D) )
```

 7. Escriba un programa que pida 5 números reales y calcule las siguientes operaciones usando una función para cada una:


El promedio
La mediana
El promedio multiplicativo (multilplica todos y luego calcula la raíz de la cantidad de operandos)
Ordenar los números de forma ascendente
Ordenar los números de forma descendente
La potencia del mayor número elevado al menor número
La raíz cúbica del menor número
```
a = float(input("Ingrese un unmero real: "))
b = float(input("Ingrese un numero real: "))
c = float(input("Ingrese un numero real: "))
d = float(input("Ingrese un numero real: "))
e = float(input("Ingrese un numero real: "))
def promedio(a, b, c, d, e):
    n = (a+b+c+d+e)/5
    return n 

lista = [a,b,c,d,e]

lista_ordenada = sorted(lista)
def mediana(lista):
    lista_ordenada =sorted(lista)
    return lista_ordenada[2]
print("La mediana es: ",mediana(lista))

    


def promedio_multiplicativo(a,b,c,d,e):
    x= (a*b*c*d*e)**(0.5)
    return x

def potencia(lista):
    lista_ordenada 
    mayor = max(lista_ordenada)
    menor = min(lista_ordenada)
    y= mayor**menor

def lista_descendente(lista):
    lista.sort(reverse=True)   
    return lista
```

8. Consultar qué es y como funciona pyp en Python
   
- Pip es una herramienta en Python que se utiliza para instalar y administrar paquetes de software. Los paquetes son conjuntos de código que se pueden reutilizar en múltiples proyectos de Python para realizar tareas específicas, como manipulación de datos, creación de interfaces de usuario, acceso a bases de datos, y mucho más. Pip es la abreviatura de "Pip Installs Packages" (Pip Instala Paquetes) y es la forma más común de instalar paquetes de terceros en Python.

9.  Hacer un listado de módulos populares para python que se puedan instalar com pip y consultar cómo instalarlos

-
1. NumPy
2. Pandas
3. Matplotlib
4.Sicikit-learn
5.Requests
6. Flask
7. Django
8. TensorFlow
9.PyTorch
10. SQLAlchemy
    Estas se instalan usando "pip install" y posteriormentel nombre del modulo
