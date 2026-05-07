# Tutorial: Uso de condicionales IF

## Paso 1: Condicional simple
En este paso aprenderás a usar un bloque `if`.  
Este bloque ejecuta una acción **solo si** la condición es verdadera.

```blocks
if (player.isOnGround()) {
    player.say("Estoy en el suelo")
}
```

## Paso 2: Condicional con comparación
Ahora vamos a usar un `if` que compara un número.  
Si el número de bloques colocados es mayor que 5, mostramos un mensaje.

```blocks
if (blocksPlaced > 5) {
    player.say("Has colocado más de 5 bloques")
}
```