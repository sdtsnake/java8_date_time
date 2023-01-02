# Date Time
Ejercicios manejo Date Time

Esta es una api que recoje todo le mejor de otras librerias de manejo de unidades de tiempo <br>
hay que tenes en cuenta que para esta librea el inicio de la semna y del mes no es cero ya <br>
que esto se prestaba para confusiones 

# Respresentaciones de tiempo

**Instant ->** Respresenta un punto en el tiempo. <br>
**LocalDate ->** Esta es la representacion de la fecha la cual sus parametros son año, mes y dia. <br> 
**LocalDateTime ->** Tiene las mismas caracteristicas de LocalDate pero este incluye la hora. <br>
**OffsetDateTime ->** Tiene todas las carecteristicas de LocalDateTime pero con ajuste a una zona horaria. <br>
**LocalTime ->** Este contiene la hora con presicion hasta los nanos segundos. **Nota: no contine la fehca**. <br>
**ZonedDateTime ->** Tiene las caracteristicas OffsetDateTime pero agrega un id para la zona horaria. <br>
**OffsetLocalTime ->** Contiene la hora pero ajustada a la zona horaria. <br>
**MonthDay ->** Contine el mes y dia, sin año ni hora. <br>
**YearMonth ->** Contiene el mes y año, sin dia ni hora. <br>
**Duration ->** Cantidad de tiempo en segundo minutos y horas. <br>
**Period ->** Cantidad de tiempo en dias meses y años. <br>
**DateTimeFormatter ->** Encargado de dar formato a las unidade tiempo de hora y fecha. <br>


