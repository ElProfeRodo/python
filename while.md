---
title: python
---

<link rel="stylesheet" href="/python/assets/css/style.css">

# 🐍 Python

# Ciclo While

Aquí revisaremos cómo iterar mientras una condición sea verdadera.

### Presentación de la Clase
*(Puedes navegar usando las flechas o el mouse)*

<div style="position: relative; width: 100%; height: 0; padding-top: 56.25%; padding-bottom: 48px; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden; border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https://docs.google.com/presentation/d/e/2PACX-1vS6x4FwdGa8S0oC14KSDMlRZEag98dEeJ8aWBKOci_LmFpHoAMvpvhTWMq3irSUVROJYwiNAypPsldQ/embed?start=false&loop=false&delayms=3000" 
    allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true">
  </iframe>
</div>
<br>

## Ejercicios

### 1. Número positivo

Solicitar un número desde el teclado y validar que sea positivo. En caso de no serlo, volver a pedir el número hasta que supere la validación
<details markdown="1">
<summary> Ver Solución Propuesta</summary>

```python
numero = int(input("Numero: "))

# Se valida que el numero sea positivo
while numero < 0:
    print("El numero debe ser positivo")
    numero = int(input("Numero: "))
```

```python
while True:
    numero = int(input("Numero: "))
    # Si el numer es positivo, salimos del while
    if numero > 0:
        break
    else:
        print("El numero debe ser positivo")
```

</details>

---
<br>

[⬅️ Volver](/python)

<br>
<br>

<div align="center">
  <small>
    © 2025 Rodolfo Fernández-Santibáñez. <br>
    Esta obra está bajo una licencia <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons BY-NC-SA 4.0</a>.
  </small>
</div>
