# PROYECTO-ICC2
Primera parte  del proyecto final de ICC



    def variables_básico():
        print("¿Qúe es una varible?")
        print("En programación, las variables son espacios reservados en la memoria que, como su nombre indica,\n pueden cambiar de c  contenido a lo largo de la ejecución de un programa")
        confirmacion=input("Entendiste?: ")
        if confirmacion=="si":
            pass
        if confirmacion=="no":
            print("Pongamoslo de una manera sencilla\nUna variable será como una cajita vacia, esta puede tener distintas cosas dentro.\nTu asignas que habrá dentro de la cajita")
        print("Ahora veamos algunos ejemplos")
        seguir=input("Dale Enter para continuar")
        if seguir=="":
            print("Una variable puede ser 'A'. 'A' puede ser lo que quieras, un texto, un número, etc.")
            print("Por ejemplo:\n A=5+3\nAhora A=8, cuando imprimas A (print(A)) te dara como resultado 8")
            s=input("Quieres ver otro ejemplo? :")
            if s=="si":
                print("Por ejemplo:\n Nombre='Carlitos'\n hemos asignado el texto 'Carlitos' a la variable Nombre, cuando imprimas Nombre (print(Nombre)) te dara como resultado 'Carlitos'")
            else:
                pass
        else:
            pass
        print("Creo que ya estás listo para los ejercicios:")
        f=input("Dale Enter para continuar")
        if f=="":
            print("Primera pregunta:\n¿Qué es una variable computacional?")
            print("A.Espacios reservados que pueden ir cambiando a lo largo de la ejecución de cualquier programa")
            print("B.Una parte del programa que varía dependiendo de las igualdades que les presentes.")
            print("C.Un corrector automático, el cual cambia las partes del programa, variando su estructura.")
            print("D.Un valor donde varía la letra que se le asigne para que la mayoría de personas puedan entender.")
            ans=input("Ingresa tu respuesta: ")
            if ans=="A":
                print("MUY BIEN")
            elif ans=="a":
                print("MUY BIEN")
            else:
                print("MUY CERCA. ACERTARÁS A LA PROXIMA")
        else:
            pass
        o=input("Dale enter para pasar al siguiente ejercicio")
        if o=="":
            print("Segunda Pregunta:\nPara el siguiente enunciado,¿cuál o cuáles son las variables?: “Yo tengo 18 años y poseo determinada de camellos (X), cada vez que se me antojan una cantidad de kebabs (H), mi cantidad de camellos se reduce a la mitad.")
            print("A. La cantidad de camellos “X”")
            print("B. Los kebabs “H”")
            print("C. Mi edad “A”")
            print("D. Los kebabs y los camellos “H y X”")
            print("E. Los kebabs y mi edad “H y A”")
            AN=input("Ingresa tu respuesta: ")
            if AN=="D":
                 print("MUY BIEN")
            elif AN=="d":
                 print("MUY BIEN")
            else:
                print("MUY CERCA. ACERTARÁS A LA PROXIMA")
        else:
            pass
        t=input("Dale enter para pasar al siguiente ejercicio")
        if t=="":
            print("Tercera pregunta:\nComo máximo, ¿cuántas variables pueden haber en un programa?")
            print("A. A lo mucho 6 variables")
            print("B. Máximo 10")
            print("C. No hay máximo (infinitas)")
            print("D. Solo 27, porque hay 27 letras en el abecedario")
            print("E. Depende de qué programa se use")
            res=input("Ingresa tu respuesta: ")
            if res=="C":
                print("MUY BIEN")

            elif res=="c":
                print("MUY BIEN")
            else:
                print("MUY CERCA. ACERTARÁS A LA PROXIMA")
        else:
            pass
        return
        
        def definicion_listas():
    print("¿Qué es una lista en Python?")
    print("En Python y en programación una lista es una estructura de datos\nque se usa para almacenar de manera local una serie de datos en un cietro orden)")
    print("Su sintaxis es asi: \nnombre_lista=[]\ndentro de los corchetes se almacenan los datos que uno desee como: \nlista_de_alumnos=[","Juan,","Pedro,","Jose]")
    respuesta=input("Entendiste?: ")
    if respuesta=="Si" or respuesta=="si":
        intermedio_listas_e1()
    else:
        print("Una manera facil de vizualizar el concepto es como una fila en el supermercado o para el autobus")
        print("Cada persona tiene un numero o posicion en la lista")
        respuesta=input("Entendiste?: ")
        if respuesta=="Si" or respuesta=="si":
            intermedio_listas_e1()
        else:
            definicion_listas()
    return

    def intermedio_listas_e1():
        respuesta = 0
        while respuesta != ("A" or "a"):
            print ("pregunta 1")
            print ("respuesta a")
            print ("respuesta b")
            print ("respuesta c")
            print ("respuesta d")
            respuesta = input()
            if respuesta == "A" or "a":
                break
            else:
                pass
        intermedio_listas_e2()
        return

    def intermedio_listas_e2():
        respuesta = 0
        while respuesta != ("A" or "a"):
            print ("pregunta 2")
            print ("respuesta a")
            print ("respuesta b")
            print ("respuesta c")
            print ("respuesta d")
            respuesta = input()
            if respuesta == "A" or "a":
                break
            else:
                pass
        intermedio_listas_e3()
        return

    def intermedio_listas_e3():
        respuesta = 0
        while respuesta != ("A" or "a"):
            print ("pregunta 3")
            print ("respuesta a")
            print ("respuesta b")
            print ("respuesta c")
            print ("respuesta d")
            respuesta = input()
            if respuesta == "A" or "a":
                break
            else:
                pass
        print ("Si deseas continuar con el siguiente tema escribe Next")
        print ("Si deseas escoger otro tema escribe Tema")
        a = input()
        if a =="Next" or "next":
            definicion_funciones()
        elif a == "Tema" or a=="tema":
            MenudeTemas()
        return

    def definicion_funciones():
        print("Que es una funcion?")
        print("Una funcion es un conjunto de instrucciones que\nse puede ejecutar mas de una vez en un mismo programa")
        print("Las funciones se utilizan para evitar repetir el set de instrucciones")
        print("Una funcion puede: \nrecibir o no parametros\nretornar parametros o ningun valor")
        respuesta=input("Entendiste?: ")
        if respuesta=="Si" or respuesta=="si":
            intermedio_funciones_e1()
        else:
            print("Una manera mas sencilla de ver una funcion es como un programa cualquiera\nescrito en Python or cualquier otra lengua de programacion")
            respuesta=input("Entendiste?: ")
            if respuesta=="Si" or respuesta=="si":
                intermedio_listas_e1()
            else:
                definicion_funciones()
        return

    def intermedio_funciones_e1():
        respuesta = 0
        while respuesta != ("A" or "a"):
            print ("pregunta 1f")
            print ("respuesta a")
            print ("respuesta b")
            print ("respuesta c")
            print ("respuesta d")
            respuesta = input()
            if respuesta == "A" or respuesta=="a":
                break
            else:
                pass
        intermedio_funciones_e2()
        return

    def intermedio_funciones_e2():
        respuesta = 0
        while respuesta != ("A" or "a"):
            print ("pregunta 2f")
            print ("respuesta a")
            print ("respuesta b")
            print ("respuesta c")
            print ("respuesta d")
            respuesta = input()
            if respuesta == "A" or respuesta=="a":
                break
            else:
                pass
        intermedio_funciones_e3()
        return

    def intermedio_funciones_e3():
        respuesta = 0
        while respuesta != ("A" or "a"):
            print ("pregunta 3f")
            print ("respuesta a")
            print ("respuesta b")
            print ("respuesta c")
            print ("respuesta d")
            respuesta = input()
            if respuesta == "A" or "a":
                break
            else:
                pass
        print ("Si deseas continuar con el siguiente tema escribe Next")
        print ("Si deseas escoger otro tema escribe Tema")
        a = input()
        if a =="Next" or a=="next":
            intermedio_strings_e1()
        elif a == "Tema" or a=="tema":
            MenudeTemas()
        return

    def intermedio_strings_e1():
        return

    def MenudeTemas():
        return

