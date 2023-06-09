# 01. Primer programa

Durante esta sección se han aprendido los primeros conceptos de Arduino Uno (Elegoo Uno). Para ello se ha realizado un simple programa cuyo objetivo ha sido el de encender y apagar durante un segundo un LED incorporado en la propia placa Elegoo Uno.

### Tabla de contenidos

-   [Recursos](#recursos)
-   [Conceptos aprendidos](#conceptos-aprendidos)

## <a id="recursos"> Recursos

Se han necesitado los siguientes recursos:

1. [Placa Elegoo Uno](https://www.elegoo.com/en-es/products/elegoo-uno-r3-board)
2. [Arduino IDE](https://www.arduino.cc/en/software)
3. [Vídeo explicativo por Bitwise Ar](https://www.youtube.com/watch?v=GUuWgk3dXd0&list=PLkjnQ3NFTPnY1eNyLDGi547gkVui1vyn2&index=2)

## <a id="conceptos-aprendidos"> Conceptos aprendidos

Se han aprendido los siguientes conceptos:

-   **Código:**

```C++
void setUp() {
    // codigo de inicializacion, se ejecuta una sola vez al principio
}
```

```C++
void loop() {
    // codigo que se ejecuta repetidamente
}
```

```C++
// Declara el pin numero 13 como salida
pinMode(13, OUTPUT);
```

```C++
// Escribe un uno (5V) en el pin 13
digitalWrite(13, HIGH);
// Escribe un cero (0V) en el pin 13
digitalWrite(13, LOW);
```

```C++
// Espera durante un segundo
delay(1000);
```

-   **Compilación y escritura del código en la placa con el IDE de Arduino:**

En la parte superior izquierda, pulsando en el tick se compila el código y pulsando en la flecha se copia el código en la placa.

![Compilación y ejecución](images/01-compilacion-ejecucion.png)

_Aitor Melero 18/03/2023_
