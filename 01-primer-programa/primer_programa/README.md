# 01. Primer Programa

Durante esta sección se han aprendido los primeros principales conceptos de Arduino Uno (Elegoo Uno). Para ello se ha realizado un simple programa cuyo objetivo ha sido el de encender y apagar durante un segundo un LED incorporado en la propia placa Elegoo Uno.

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

```arduino
void loop() {
    // codigo que se ejecuta repetidamente
}
```

```arduino
// declara el pin numero 13 como salida
pinMode(13, OUTPUT);
```

```arduino
// escribe un uno (5V) en el pin 13
digitalWrite(13, HIGH);
// escribe un cero (0V) en el pin 13
digitalWrite(13, LOW);
```

```arduino
// espera durante un segundo
delay(1000);
```

2. Compilación y escritura del código en la placa con el IDE de Arduino:

En la parte superior izquierda, pulsando en el tick se compila el código y pulsando en la flecha se copia el código en la placa.
[01-compilacion-ejecucion]
![alt text]
[01-compilacion-ejecucion]: https://raw.githubusercontent.com/MrFork27/curso-arduino/01PrimerPrograma/01-primer-programa/primer_programa/images/01-compilacion-ejecucion.png?token=GHSAT0AAAAAACAGRCL7EJ2CGRPCTBEFSMUCZAVRXXA
