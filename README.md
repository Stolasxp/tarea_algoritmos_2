# Ejemplos de estructuras de selección en C++

Este documento muestra cómo se utilizan las estructuras de selección en C++: `if - else` y `switch`.

---

## 🧠 Estructura `if - else`

Se utiliza para tomar decisiones simples:

```cpp
#include <iostream>
using namespace std;

int main() {
    int numero;
    cout << "Ingresa un número: ";
    cin >> numero;

    if (numero > 0) {
        cout << "El número es positivo.";
    } else {
        cout << "El número es cero o negativo.";
    }

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    int opcion;
    cout << "Elige una opción (1-3): ";
    cin >> opcion;

    switch (opcion) {
        case 1:
            cout << "Elegiste la opción 1";
            break;
        case 2:
            cout << "Elegiste la opción 2";
            break;
        case 3:
            cout << "Elegiste la opción 3";
            break;
        default:
            cout << "Opción no válida";
    }

    return 0;
}
