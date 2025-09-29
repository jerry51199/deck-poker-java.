# Simulación de una Baraja de Póker en Java

## 📌 Descripción
Este proyecto implementa una baraja de póker en Java utilizando **Programación Orientada a Objetos (POO)** y estructuras del **Collection Framework**.  
Se modelan las cartas (Card) y el deck (Deck), con métodos para mezclar, mostrar y repartir cartas.

## 🃏 Reglas de la baraja de póker
- La baraja estándar contiene **52 cartas**.
- Palos:
  - ♣ Tréboles → Negro  
  - ♠ Picas → Negro  
  - ♥ Corazones → Rojo  
  - ♦ Diamantes → Rojo  
- Cada palo tiene 13 valores: **2, 3, 4, 5, 6, 7, 8, 9, 10, J, Q, K, A**.

## 🚀 Clases implementadas
### 🔹 `Card`
Representa una carta de la baraja.
- `palo` (Tréboles, Corazones, Picas, Diamantes)  
- `color` (Rojo o Negro)  
- `valor` (2–10, J, Q, K, A)  

### 🔹 `Deck`
Representa el conjunto de cartas.
- Contiene todas las **52 cartas** en una lista (`ArrayList`).  
- Métodos principales:  
  - `shuffle()` → Mezcla el deck.  
  - `head()` → Muestra y elimina la primera carta.  
  - `pick()` → Selecciona y elimina una carta al azar.  
  - `hand()` → Devuelve 5 cartas y las elimina del deck.  

### 🔹 `Main`
Clase principal que ejecuta el programa y prueba las funciones.

## ⚙️ Ejemplo de ejecución
