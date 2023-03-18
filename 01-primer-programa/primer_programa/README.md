# 01. Primer programa

Durante esta sección se han aprendido los primeros conceptos de Arduino Uno (Elegoo Uno). Para ello se ha realizado un simple programa cuyo objetivo ha sido el de encender y apagar durante un segundo un LED incorporado en la propia placa Elegoo Uno.

## Recursos

Se han necesitado los siguientes recursos:

1. [Placa Elegoo Uno](https://www.elegoo.com/en-es/products/elegoo-uno-r3-board)
2. [Arduino IDE](https://www.arduino.cc/en/software)

## Conceptos aprendidos

Se han aprendido los siguientes conceptos:

1. Código:

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

2. Compilación y escritura del código en la placa con el IDE de Arduino:

En la parte superior izquierda, pulsando en el tick se compila el código y pulsando en la flecha se copia el código en la placa.
![alt text](images/01-compilacion-ejecucion.png)
