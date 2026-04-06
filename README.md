## Actividad 2: Viajes turísticos con DTD interno

Crea un documento XML que incluya un **DTD interno** para que el XML siguiente sea **válido**.

Debes añadir en el propio documento, justo después de la declaración XML, las reglas necesarias para definir la estructura de los elementos, sus relaciones y el número de repeticiones que corresponda en cada caso. 

El objetivo es que el documento no solo esté **bien formado**, sino que además sea **válido** respecto al DTD que hayas definido. La validación de un XML con DTD consiste precisamente en comprobar que, además de tener una sintaxis XML correcta, cumple las reglas declaradas en su DTD.

Utiliza este XML como punto de partida:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<viajes_turisticos>
    <viaje>
        <clientes>
            <cliente>
                <nombre></nombre>
                <apellidos></apellidos>
            </cliente>
            <cliente>
                <nombre></nombre>
                <apellidos></apellidos>
            </cliente>
        </clientes>
        <fecha_inicio></fecha_inicio>
        <fecha_fin></fecha_fin>
        <origen></origen>
        <posibles_destinos>
            <destino>
                <ciudad></ciudad>
                <hotel></hotel>
                <noches></noches>
            </destino>
            <destino>
                <ciudad></ciudad>
                <hotel></hotel>
                <noches></noches>
            </destino>
            <destino>
                <ciudad></ciudad>
                <hotel></hotel>
                <noches></noches>
            </destino>
        </posibles_destinos>
        <precio></precio>
    </viaje>
</viajes_turisticos>
```

Para comprobar si tu documento es válido, puedes usar un validador online que soporte validación XML con **DTD**, como el de Truugo, que indica expresamente que permite validar XML tanto por sintaxis como mediante esquemas **XSD + DTD**. ([truugo.com][1])

[1]: https://www.truugo.com/xml_validator/?utm_source=chatgpt.com "XML Validator"
