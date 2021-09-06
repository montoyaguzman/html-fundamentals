# positions
| Tipo                       | Descripción                |
| -------------------------- | -------------------------- |
| -------------------------- | -------------------------- |
| static                     | Por defecto, obedece el flujo normal del documento. |
| relative                   | Se mantiene static pero nos permite usar top, bottom, right y left para moverlo de su posición original (respecto a sí mismo).  |
| absolute                   | Pierde su posicion, queda relativo (o static) a su antecesor pero absoluto al resto. Nos permite usar top, bottom, right y left (para moverlo desde los borde de su contenedor). |
| fixed                      | Pierde espacio físico y see posiciona relativamente a la ventana del navegador. |
| sticky                     | El elemento es colocado en el flujo normal del documento y después se puede posicionar de acuerdo a su ancestro. |
| initial                    | Se setea a su valor por defecto. |
| inherit                    | Hereda el valor de su antecesor. |