--Ejercicio 1 Jenkins--

Creo un Pipeline de la UI de Jenkins apuntando a mi Jenkinsfile dentro de Calculator:

![jens01-01](./capturas/jenkins01.png)

![jens01-02](./capturas/jenkins02.png)

Compilado correcto:

![jens01-03](./capturas/jenkins03.png)

--Ejercicio 2 Jenkins--

Creo otro Pipeline desde la UI de Jenkins apuntando a mi nuevo Jenkinsfile: Jenkinsfile.2, misma ubicacion que el anterior:

![jens02-01](./capturas/jenkins05.png)

Compilado Correcto:

![jens02-02](./capturas/jenkins06.png)

--Ejercicio 1 Github--

Creo una branch nueva para el trigger:

![ejercicio01-01](./capturas/ejercicio01-01.png)

Edito el dockerfile:

![ejercicio01-02](./capturas/ejercicio01-02.png)

PR:

![ejercicio01-03](./capturas/ejercicio01-03.png)

PR mergeado:

![ejercicio01-04](./capturas/ejercicio01-04.png)

BUILD:

![ejercicio01-05](./capturas/ejercicio01-05.png)

Test falla pero por el codigo:

![ejercicio01-06](./capturas/ejercicio01-06.png)

--Ejercicio 2 Github--

Creo una variable con mi usuario de GH y un access token que guardo como secret:

![ejercicio02-01](./capturas/ejercicio02-01.png)

Le pongo el tag al run:

![ejercicio02-03](./capturas/ejercicio02-03.png)

Build:

![ejercicio02-02](./capturas/ejercicio02-02.png)

Imagenes buildeadas:

![ejercicio02-04](./capturas/ejercicio02-04.png)

--Ejercicio 3 Github--

Tests e2d:

![ejercicio03-01](./capturas/ejercicio03-01.png)

--RUTAS ARCHIVOS-

LemonCode\LemonCode-BootCamp-DevOps-CICD\.github\workflows
LemonCode\LemonCode-BootCamp-DevOps-CICD\jenkins-resources\calculator --> Jenkinsfile
LemonCode\LemonCode-BootCamp-DevOps-CICD\jenkins-resources\calculator --> Jenkinsfile.2