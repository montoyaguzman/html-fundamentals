## Como controla el orden CSS
1. Importancia
2. Especificidad
3. Orden de las fuentes

# Importancia
* Estilos del agente(navegador).
* Declaración de TODOS nuestros estilos.
* Uso de estilos !important.

# Especificidad
| Selector            | Especificidad       |
| ------------------- | ------------------- |
| !importan           | 1,0,0,0,0           |
| inline styles       | 1,1,0,0,0           |
| #id                 | 0,0,1,0,0           |
| .class              | 0,0,0,1,0           |
| tag                 | 0,0,0,0,1           | 

# Orden de las fuentes
Como importas los css, las importaciones son en cascada.
Las declaraciones que se aplican son las que esten "hasta abajo".

# Algoritmo
1. Conflicto => !important => inline => especificidad => archivo css => navegador