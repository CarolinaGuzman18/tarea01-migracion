# Acceso a la salud de las personas migrantes 
#### En este proyecto se llevará a cabo un análisis de accesibilidad a servicios de salud públicos y privados de las personas en tránsito a través de Costa Rica
## Antecedentes
Las movilizaciones humanas entre países tienen una larga trayectoria histórica. Existe una gran variedad de dinámicas migratorias, incluyendo migraciones estacionales, permanentes, semi permanentes, en tránsito o de refugio (Cortés et al. 2020). Un _migrante en tránsito_ es una persona que se encuentra temporalmente en un país con el objetivo de llegar a un destino definitivo. En todo el mundo, la situación de los migrantes en tránsito en materia de derechos humanos es precaria, incluso peligrosa. Aun cuando los avances tecnológicos hayan hecho que los viajes sean más rápidos y más seguros, para muchos migrantes su recorrido puede tardar semanas, meses e incluso años [ONU, 2021](https://www.ohchr.org/sites/default/files/2021-12/INT_CMW_INF_7940_S.pdf). 
<p align = "center">
    <img src = "https://www.elpais.cr/wp-content/uploads/2023/12/Migrantes-en-el-Darien-Panama-en-ruta-hacia-EEUU.-PL.jpeg">
</p>
<p align = "center"> Fuente:
    <a href="https://www.elpais.cr/2023/12/20/flujo-de-migrantes-por-costa-rica-crecio-en-121-por-ciento-en-2023/">El País</a>
</p>
Por su posición geográfica estratégica, Costa Rica ha funcionado como receptor para muchas personas migrantes. Además de recibir grupos de personas inmigrantes que se asientan permanentemente en el territorio, Costa Rica experimenta casos de movilidad temporal [ACNUR, 2008](https://www.acnur.org/fileadmin/Documentos/Publicaciones/2008/6307.pdf). Las personas migrantes en tránsito suelen carecer de la posibilidad de trabajar, alquilar una vivienda o acceder a servicios básicos como la educación y la atención de la salud. Los migrantes suelen emprender su viaje con buena salud. Sin embargo, la complejidad del recorrido migratorio, las condiciones de viaje y la falta de servicios de atención de la salud, o la insuficiencia de esos servicios, pueden llevar a que muchos migrantes se vean aquejados por dolencias físicas y mentales (ONU, 2021).

Según la Organización de las Naciones Unidas (2021), todos los migrantes, independientemente de su estatus, tienen el derecho legítimo de recibir plena protección en cuanto a su derecho a la salud. El Pacto Internacional de Derechos Económicos, Sociales y Culturales reconoce el derecho de toda persona a disfrutar del más alto nivel posible de salud física y mental. Además, el Comité de Derechos Económicos, Sociales y Culturales enfatiza que los Estados deben garantizar que todos los migrantes, sin importar su situación legal o documentación, tengan acceso igualitario a los servicios de salud preventivos, curativos y paliativos.

De acuerdo a el código 41 del Código de la Niñez y la Adolescencia: "las personas menores de edad gozarán de atención médica directa y gratuita por parte del Estado". Por lo que toda persona menor de edad que se encuentre en tránsito por Costa Rica tiene la posibilidad de acudir a cualquier centro de salud u hospital y ser atendido/a de manera gratuita en las mismas condiciones que las personas nacionales costarricenses (OIM, s.f. ). Por otra parte, las personas adultas pueden acceder a los servicios de emergencia de forma gratuita. En el caso de necesitar atención médica, deben pagar el seguro voluntario de La Caja Costarricense de Seguro Social (OIM, s.f. ).
<p align = "center">
    <img src = "https://www.ucr.ac.cr/medios/fotos/2015/foto-1-salud-ccss-aya-ucr56269650a4edd.jpg ">
</p>
<p align = "center"> Fuente:
    <a href="https://www.ucr.ac.cr/noticias/2015/10/21/sostenibilidad-de-ccss-y-aya-son-vitales-para-la-salud-en-costa-rica.html">Universidad de Costa Rica</a>
</p>

## Problema
En teoría, las personas que se encuentran en tránsito por Costa Rica tienen la posibilidad de acceder a los servicios de salud en el caso que lo requieran. El problema radica en que las personas en tránsito por el país, en su mayoría, siguen la ruta migratoria principal, lo que puede implicar que la ubicación de los centros de salud no sea fácilmente accesible para ellas.

Por esta razón, los objetivos de este proyecto son:
1.	Evaluar la distribución de los centros de salud cercanos a la ruta migratoria (públicos y privados). 
2.	Determinar la accesibilidad a los centros de salud desde la ruta migratoria (por distancia). 
3.	Identificar zonas críticas de la ruta donde no hay acceso cercano a centros de salud. 
### Datos
-	**Distribución de centros de salud**: capa vectorial de puntos con la ubicación de los centros de salud de Costa Rica. Variables: provincia, cantón, distrito, nombre, tipo de centro (clínica, hospital, EBAIS, doctor) y operador (privado o público). 
-	**Ruta migratoria**: capa vectorial de líneas. 
-	**Distritos**: capa vectorial de polígonos. Variables: provincia, cantón, distrito, región y ruta migratoria (la ruta migratoria pasa o no por el distrito)

Al cumplir con estos objetivos, se espera obtener un entendimiento claro y detallado de la verdadera accesibilidad que tienen las personas migrantes en tránsito por la ruta migratoria a los servicios de salud en Costa Rica. Esto permitirá identificar las áreas donde los migrantes enfrentan mayores dificultades para acceder a atención médica, ya sea por la falta de centros de salud cercanos o por la inadecuada distribución de los mismos, tanto públicos como privados.

Con esta información, se podrán tomar decisiones informadas y estratégicas, que permitan a instituciones como la Organización Internacional para las Migraciones (OIM) colaborar estrechamente con la Caja Costarricense de Seguro Social (CCSS) para reforzar y mejorar la accesibilidad a los centros de salud. 

Esto podría incluir la implementación de nuevas políticas, la creación de centros de salud adicionales en zonas críticas, o la optimización de los recursos existentes para garantizar que todos los migrantes tengan acceso a la atención médica que necesitan a lo largo de su ruta.

## Referencias bibliográficas
1.	Alto Comisionado de las Naciones Unidas para los Refugiados. (2008). _Refugio en Costa Rica: Un manual sobre aspectos migratorios, de refugio y apatridia_. [https://www.acnur.org/](https://www.acnur.org/fileadmin/Documentos/Publicaciones/2008/6307.pdf)
2.	Cortés Ramos, A., & Fernández, A. (2020). ¿Cobertura universal? Las barreras en el acceso a la salud para la población refugiada nicaragüense en Costa Rica. _Anuario Centro de Investigación y Estudios Políticos_, 11, 255–287. [https://doi.org/10.15517/aciep.v0i11.43533 ](https://doi.org/10.15517/aciep.v0i11.43533)

3.	Organización Internacional para las Migraciones. (s.f.). _Costa Rica: Acceso a los servicios de salud para las personas migrantes en situación irregular_. Migrantinfo. Recuperado de [https://migrantinfo.iom](https://migrantinfo.iom.int/es/node/119#:~:text=Las%20personas%20migrantes%20en%20situaci%C3%B3n,Caja%20Costarricense%20de%20Seguro%20Social.)
4.	Oficina del Alto Comisionado de las Naciones Unidas para los Derechos Humanos. (2021). _Informe de la Oficina del Alto Comisionado de las Naciones Unidas para los Derechos Humanos_. [https://www.ohchr.org](https://www.ohchr.org/sites/default/files/2021-12/INT_CMW_INF_7940_S.pdf)

##### Elaborado por Carolina Guzmán Herrera en el marco del curso Programación en SIG de la Escuela de Geografía de la Universidad de Costa Rica.