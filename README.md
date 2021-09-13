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
