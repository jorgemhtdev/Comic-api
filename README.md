# Comic Info API

Pending update

## Entities Swift


``` swift
struct JApi: Codable {
    let comic: [Comic]
}
``` 

``` swift
struct Comic: Codable {
    var id: Int
    var isbn: String
    var desc: String
    var fechaDeVenta: Date
    // Tapa dura Tapa blanda
    var formato: String
    var numPag: Int
    // 17.8X17.8CM
    var tamano: String
    // True es con color, false es blanco y negro
    var color: Bool
    var precio: Doublex
    var photo: String
    var novedad: Bool
    var agotado: Bool
    var disponibilidad: Bool
    var serie: Serie
    var editorial: Editorial
}
```
## Model Definition 

### http://www.objgen.com/json

```
Comic[0]
  id n = 1
  isbn = 978-84-18475-51-1
  nombre = BATMAN: TRES JOKERS NÚM. 1 DE 3
  nombreOriginal = Batman: Three Jokers Book One USA
  desc = Batman: Tres Jokers reexamina el mito de quién (o qué) es el Joker y qué subyace tras su eterna batalla contra el Caballero Oscuro. ¿Por qué existen tres Jokers? Tras años de especulaciones y grandes expectativas desde su aparición en el especial Universo DC: Renacimiento, ha llegado el momento de dar respuesta a tan inquietante pregunta. Responsable de la exitosa saga Liga de la Justicia: La guerra de Darkseid, el equipo creativo formado por Geoff Johns (El Reloj del Juicio Final, Batman: Tierra uno) y Jason Fabok (Batman/Flash: La chapa, La Cosa del Pantano: Santos con pies de barro) se reúne de nuevo para relatar la historia definitiva del Hombre Murciélago y el Príncipe Payaso del Crimen, a través de una miniserie de tres entregas.
  fechaDeVenta d = 2020-12-30
  formato = Cartoné
  numPag n = 48
  tamano = 
  peso n = 290
  color b = true
  precio n = 10.4
  photo = https://github.com/jorgemhtdev/comic-json/blob/main/img/tres-jokers-01.jpg
  novedad b = true
  agotado b = false
  disponibilidad b = true
  url = https://www.ecccomics.com/comic/batman-tres-jokers-num-01-de-3-9110.aspx
  ```
