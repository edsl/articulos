---
layout: post
title: "Libertad en la nube, Libertad del Software, Privacidad y Seguridad para la Web 2.0 y Computación en la Nube"
author: "Eben Moglen"
cover: "images/cover_endefensadelsl_nr0.png"
old-slug: freedom_in_the_cloud.html
license: https://creativecommons.org/licenses/by-sa/3.0/us/
---

Libertad en la nube, Libertad del Software, Privacidad y Seguridad para la Web 2.0 y Computación en la Nube
===========================================================================================================

> Discurso de [Eben Moglen][0] en una reunión de la rama neoyorquina de
> la [Internet Society][1] el 5 de Febrero de 2010. La grabación del
> evento se encuentra disponible en [http://ur1.ca/lch5][2].
> 
> Esta es una traducción de su transcripción por Nicolás Reynolds,
> revisada y corregida por Leonardo G. De Luca, septiembre, 2010.
> Original disponible en [http://ur1.ca/uups][3].
> 
> El original y esta traducción se distribuyen bajo licencia [Creative
> Commons Atribución-CompartirIgual 3.0 de Estados Unidos][4].
> Originalmente, la desgrabación se licenció bajo CC-BY-NC-ND 2.0.

Es un placer estar aquí. Me encantaría pensar que la razón por la que
estamos aquí en un viernes a la noche es porque mis charlas son muy
buenas. En realidad no tengo idea de por qué estamos aquí en una noche
de viernes pero estoy muy agradecido por la invitación. Soy la persona
que no tenía cita esta noche así que fue bastante conveniente que me
invitaran.

Así que, por supuesto, no tenía una cita esta noche. Todo el mundo lo
sabe. Mi agenda está en la web.

El problema es ese problema. Nuestra agenda está en la web. Nuestra
ubicación está en la web. Tenés un teléfono celular y un proveedor de
telefonía celular y si tu proveedor es Sprint entonces podemos decir que
varios millones de veces durante el año pasado, alguien con una
identificación legal en su bolsillo fue al sitio web de Sprint y pidió
la ubicación en tiempo real de alguien con un número de teléfono y ésta
le fue dada. Varios millones de veces. Así nada más.  Sabemos esto
porque Sprint admite que tiene un sitio web donde cualquiera con una
identificación puede ir y encontrar la ubicación en tiempo real de
cualquiera que tenga un teléfono de Sprint. No sabemos eso de AT\&T y
Verizon porque no nos contaron.

Pero esa es la única razón por la que no sabemos, porque no nos
contaron. Ese es un servicio que pensarían como un servicio tradicional,
la telefonía. Pero el trato que obtenés con el servicio tradicional
llamado telefonía contiene una cosa que no conocías, como el espionaje.
No es un servicio para vos pero es un servicio y lo obtenés
gratuitamente con tu contrato de servicio telefónico.  Obtenés
gratuitamente el servicio de publicidad con tu GMail lo que significa
que hay otro servicio detrás que no ha sido tocado por manos humanas, el
análisis semántico de tu correo. Todavía no entiendo por qué alguien
querría eso. Todavía no entiendo por qué alguien lo usa pero la gente lo
hace, incluyendo la muy sofisticada y pensativa gente de esta sala.

Y obtenés servicio de correo electrónico gratuitamente y algo de
almacenamiento que vale exactamente una moneda y media al precio actual
de almacenamiento y obtenés espionaje permanente.

Y gratis también.

Y tu agenda está en la web y todos pueden ver si tenés una cita el
viernes a la noche y tenés un estado ("buscando") y obtenés un servicio
gratis, de publicidad ("soltero: buscando"). Espionaje gratis incluido.
Y todo esto apareció así en un parpadeo y aquí estamos. ¿Qué tiene que
ver con el Código Abierto? Bueno, de hecho no tiene nada que ver con el
código abierto pero si un montón que ver con el software libre. Otra
razón por la que Stallman estaba en lo cierto. ¿Es la libertad, no?

Entonces tenemos que volver un poco y pensar en qué punto estamos y cómo
llegamos aquí y probablemente algo más importante, si podemos salir y si
podemos, ¿cómo? Y no es una linda historia, para nada. David tiene
razón. Apenas puedo empezar diciendo que ganamos dado que el espionaje
viene gratis con todo ahora. Pero no perdimos. Nos metimos en un lío
nosotros mismos y vamos a tener que desliarnos realmente rápido o vamos
a meter a otra gente inocente que no sabía que estábamos regalando su
privacidad para siempre.

Empieza por supuesto con la Internet, por eso es bueno estar aquí
hablando a la Internet Society, una sociedad dedicada a la salud,
expansión y elaboración teórica de una red de par-a-par llamada
"Internet" diseñada como una red de pares sin ninguna necesidad
intrínseca de control jerarquizado o estructurado y asumiendo que cada
punto de la Red es una entidad independiente y libre cuya voluntad es
equivalente a la voluntad de los seres humanos que la quieren controlar.

Ese es el diseño de la Red, que, aunque estén pensando que está pegada
con IPv4 o esa mejora maravillosa que es IPv6 que aparentemente nunca
vamos a usar, todavía asume comunicaciones entre pares.

Por supuesto, nunca trabajó realmente de esa manera. No había nada en el
diseño técnico para prevenirlo. En ningún punto en el diseño técnico de
interconexión de los nodos y su comunicación. Fue un problema de
software. Es un simple problema de software y tiene un simple nombre de
tres sílabas. El nombre es Microsoft. Conceptualmente, había una red que
estaba diseñada como un sistema de nodos pares pero el SO que usaba la
red cada vez más - voy a usar la palabra, la usan con nosotros, ¿por qué
no puedo usarla contra ellos? - viralmente durante una década y media.
El software que empezó a ocupar la red estaba construido sobre una idea
muy clara que no tenía nada que ver con pares. Se llamó "arquitectura
cliente-servidor".

La idea de que la red era una red de pares fue díficil de percibir
después de un tiempo, particularmente si eras, digamos, un ser humano
ordinario. Esto es, no un ingeniero informático, científico o
investigador. No un hacker, no un geek.  Si eras un ser humano ordinario
era difícil percibir que la arquitectura que sostiene a la Red estaba
pensada para trabajar entre pares porque el SO con el que interactuabas
ejemplificaba fuertemente la idea de la arquitectura cliente-servidor.

De hecho, si lo piensan, fue peor que eso. La cosa llamada "Windows" era
una versión degenerada de una llamada "X Windows". Esta también pensó el
mundo como una arquitectura cliente-servidor, pero lo que ahora diríamos
al revés de como la conocemos. El servidor era la cosa del lado del ser
humano. Esa era la concepción básica del mundo de X Windows. Servía
comunicaciones con seres humanos en los puntos finales de la red a
procesos ubicados en lugares arbitrarios cerca del centro, en la mitad,
o en los bordes de la Red. Fue la gran idea de Windows en una forma
extraña crear un arquetipo político en la red que redujo el ser humano
al cliente y produjo una gran y centralizada computadora que podríamos
llamar un servidor, que ahora proveía cosas al ser humano en términos de
tómalo-o-déjalo.

Eran términos, por supuesto, bastante tómalo-o-déjalo y
desafortunadamente, todos lo tomaron porque no sabían dejarlo una vez
que entraron. Ahora la red estaba hecha de servidores en el centro y
clientes en el borde. Los clientes tenían bastante poco poder y los
servidores tenían mucho. Mientras el almacenamiento se abarata, mientras
el procesamiento se abarata, y mientras los servicios complejos que sólo
escalan en formas en que es díficil usar computadoras pequeñas -o en
cualquier caso, estas colecciones agregadas de computadoras- para ello,
siendo el más importante de todos la búsqueda. Mientras los servicios
empezaban a poblar la red, la naturaleza jerárquica de la red empezó a
verse como pensada para que así fuera. La red estaba hecha de servidores
y clientes y los clientes eran los tipos en el borde representando
humanos y los servidores eran las cosas en el medio con montones de
poder y montones de datos.

Ahora, una cosa más ocurrió alrededor de ese momento. No ocurrió en las
computadoras de Microsoft Windows aunque sí ocurrió en los servidores de
Microsoft Windows y también en SOs más sensibles como Unix y BSD entre
otros. Es decir, los servidores mantenían registros[^2]. Es una cosa muy
buena de hacer. Las computadoras deben mantener registros. Fue una
decisión muy sabia la de mantener registros, cuando se crea software
para sistemas operativos. Ayuda en la inspección, hace realizables los
rendimientos, hace posible estudiar las operaciones de las computadoras
en el mundo real. Es una muy buena idea.

Pero si tenés un sistema que centraliza servidores y los servidores
centralizan los registros, entonces estás creando vastos repositorios de
datos jerárquicamente organizados sobre gente en los bordes de la red,
sobre el que estos no tienen control y, a menos que tengan experiencia
en la operación de servidores, no comprenderán su extensión, su
significado, no entenderán su agregabilidad.

Entonces construimos una red de una arquitectura de comunicaciones
diseñada para trabajar entre pares a la que definimos en un estilo
cliente-servidor, al que entonces definimos como el desempoderado
cliente en el borde y el servidor en el medio. Agregamos cada vez más
procesamiento y almacenamiento en el medio y nos quedamos los registros
-esto es, información acerca del flujo de información en la red- en
lugares centralizados lejos de los seres humanos que controlaban o
pensaban que controlaban, la operación de las computadoras que
dominaban, cada vez más, sus vidas. Esto fue una receta para el
desastre.

Esto fue una receta para el desastre. Ahora, todavía no mencioné la
palabra "nube" que me fue puesta sobre la mesa cuando recibí la noticia
de que estaría aquí esta noche hablando de privacidad y la nube.

No mencioné la palabra "nube" porque la palabra "nube" en realidad no
significa nada. En otras palabras, el desastre que estamos teniendo no
es la catástrofe de la nube. El desastre que estamos teniendo es la
catástrofe de la forma en que malentendimos la red bajo la asistencia
del software no-libre que nos ayudó a entenderla. Lo que "nube"
significa es que los servidores dejaron de estar hechos de metal. "Nube"
significa que ha ocurrido la virtualización de los servidores.

Así que, acá afuera en los polvorientos bordes de la galaxia donde
vivimos en clientelismo desempoderado, nada cambió mucho. Mientras nos
acercamos al centro de la galaxia, todo se vuelve más borroso de lo que
era antes. Ahora vemos halos donde hubo estrellas. Servidores con
perillas y botones que se pueden apretar y así. En su lugar, lo que pasó
es que el metal ya no representa a un único servidor. El metal es
solamente un lugar donde el servidor podría estar.  Entonces "nube"
significa que los servidores han ganado libertad, libertad de moverse,
libertad de danzar, libertad de combinarse y separarse y volverse a
agregar y hacer toda clase de trucos. Los servidores ganaron libertad.
Los clientes no ganaron nada. Bienvenidos a la nube.

Es una modificación menor de la receta para el desastre. Mejora la
operabilidad de los sistemas que controlan clientes que estaban pensados
para ser pares en una red hecha de cosas iguales.

Entonces esta es la arquitectura de la catástrofe. Si lo piensan, cada
paso en esa revolución arquitectónica: de una red hecha de pares a
servidores que sirven comunicaciones con humanos, a clientes que son
programas corriendo sobre metal macizo, a clientes que son computadoras
que la gente usa en un estado bastante desempoderado y servidores con
una alta concentración de poder en la Red, a servidores como procesos
virtuales corriendo en nubes de metal en el centro de una galaxia cada
vez más caliente con clientes que están por ahí en los brazos de espiral
polvorientos.

Todas esas decisiones arquitecturales fueron hechas sin ninguna
discusión sobre sus consecuencias sociales a largo plazo, parte de
nuestra dificultad general para hablar de las consecuencias sociales de
la tecnología durante el gran período de invención de Internet hecho por
científicos informáticos que no estaban terriblemente interesados en
sociología, psicología social o, con algunas excepciones brillantes, la
libertad. Entonces obtuvimos una arquitectura que estaba bastante sujeta
al abuso. Estaba pidiendo que la abusen y ahora estamos teniendo el
abuso que creamos. Porque alivianamos los clientes más y más y más. En
efecto, los hicimos móviles. Los pusimos en nuestros bolsillos y
empezamos a pasear con ellos.

Hay muchas razones para hacer clientes desempoderados y hay todavía más
razones para desempoderar a la gente que posee los clientes y que
curiosamente podría pensarse que eran quienes los controlaban. Si
piensan por un momento cuánta gente está interesada en desempoderar a
los clientes que son los teléfonos móviles verán a qué me refiero. Hay
muchos potentadores de derechos, como piensan de sí mismos,
yuxtapuestos, cada uno de los cuales tiene interés en desempoderar al
cliente en el borde de la red para prevenir la movilidad de un hardware
particular de un punto de la red a otro. Para prevenir hardware en
particular tocar música que no fue comprada en el gran monopolio de
música en el cielo. Para deshabilitar servicios de entrega de video que
hagan competencia en nuevos chips que encontré que no corren estándares
de video populares, sean buenos o malos. Hay un montón de modelos de
negocio que se basan en fastidiar el control sobre el hardware y
software cliente del borde para privar al humano que curiosamente
pensaba que lo había comprado para ocupar el lugar que el capitalismo
dice que ocupan los dueños, esto es, el de tener control total sobre
ellos.

De hecho, lo que tenemos, como dije un par de años atrás entre otras
apariciones aquí en otra instalación de la NYU. De hecho, lo que tenemos
son cosas que llamamos plataformas. La palabra "plataforma" como la
palabra "nube" no tiene un significado inherente. Se tira mucho en
lenguaje de negocios. Pero, básicamente, lo que significa plataforma es
lugar que no podés dejar. Cosas a las que estás clavado. Cosas que no te
dejan. Esas son plataformas. Y la Red, una vez que se convirtió en una
zona arquitecturada jerárquicamente con servidores en el centro y
clientes cada vez más desempoderados en el borde, se convierte en la
zona de plataformas y fabricar plataformas se convierte en la orden del
día.

Algunos años atrás un muy perspicaz abogado que trabaja en la industria
me dijo "Microsoft nunca fue una compañía de software. Microsoft fue un
compañía de gestión de plataformas". Y pensé "Sí, directo al corazón".

Entonces tenemos un montón de gestores de plataformas en una red
organizada jerárquicamente y empezamos a desarrollar servicios.
"Servicios" es una palabra complicada. No carece para nada de sentido
pero es engañoso describirla. La usamos para un montón de cosas
distintas. Necesitamos desesperadamente una taxonomía analítica de
"servicios" como señaló mi amigo y colega Phillippe Aigrain en París
hace 2 o 3 años. Las taxonomías de los "servicios" incluyen preguntas
acerca de simplicidad, complejidad, escala y control.

Para dar un ejemplo, podríamos definir una dicotomía entre servicios
complejos y simples en los cuales los servicios simples son cosas que
cualquier computadora podría realizar y los servicios complejos son
cosas que no se pueden hacer con una computadora. Hay que hacerlas en
clústers o estructuras de cierta complejidad informática o
administrativa. BUSCAR es un servicio complejo. En efecto, buscar es el
servicio complejo arquetípico. Dada la naturaleza unidireccional de los
vínculos en la Web y otros elementos en la arquitectura de datos en la
que vivimos (esa es otra charla, en otro momento) buscar no es una cosa
que podamos distribuir fácilmente. El poder en el mercado de nuestros
amigos en Google depende enteramente del hecho de que la búsqueda no se
distribuye fácilmente. Es un servicio complejo que debe ser organizado
centralizadamente y entregado centralizadamente. Debe recorrer la Web
unidireccionalmente, vínculo por vínculo, resolviendo el orden de todo
para ayudarte a encontrarlo cuando lo necesites. Para hacer eso, por lo
menos hasta ahora, no desarrollamos buenas estructuras algorítmicas y de
entrega en forma decentralizada. Entonces, buscar se convierte en el
arquetipo de servicio complejo creándose a su alrededor un modelo de
negocio para su monetización.

Hacer publicidad en el siglo XX era una actividad azarosa. Tirabas cosas
y esperabas que funcionen. Hacer publicidad en el siglo XXI es una
actividad exquisitamente precisa. Esperás a que un tipo quiera algo y le
mandás publicidades de lo que quiere y ¡bingo!, funciona como magia. Por
supuesto por debajo de un servicio complejo llamado búsqueda hay un
servicio teóricamente simple llamada publicidad que, cuando se unifica
con un servicio complejo, incrementa su eficiencia en órdenes de
magnitud y el incremento de eficiencia del servicio simple al combinarse
con el complejo produce una enorme flujo de plus ganancia que puede ser
usado para fortalecer la búsqueda todavía más.

Pero esa es la parte inocente de la historia y no nos quedamos en la
parte inocente de la historia por una variedad de temas. No voy a ser
tedioso un viernes a la noche y decir que es porque la burguesía está
envuelta en constante reinvención y mejora destructiva de sus propias
actividades, y no voy a ser moralista un viernes a la noche, no podría
hacer eso, y decir que es porque el pecado es inerradicable y los seres
humanos son criaturas caídas y que la codicia es uno de los pecados que
no podemos evitar cometer. Sólo voy a decir que como una especie de
proceso social ordinario no paramos en lo inocente.  Seguimos, lo cual
es seguramente lo que deberían decir un viernes a la noche. Y entonces
seguimos.

Ahora, donde llegamos es a descubrir que todo esto hubiera sido mejor si
tuvieran los registros de todo porque una vez que tenés los registros de
todo entonces cualquier servicio se convierte en una mina de oro
esperando y la jodimos porque la arquitectura de la Red puso los
registros en el lugar equivocado. Pusieron los registros donde la
inocencia se tentaría. Pusieron los registros donde el estado fallido de
los seres humanos implicaba malos problemas y los obtuvimos.

La nube significa que ya ni siquiera podemos apuntar en la dirección del
servidor y porque no podemos apuntar en la dirección del servidor no
tenemos ningún medio extra técnico o no técnico confiable para controlar
este desastre en cámara lenta. Pueden hacer una regla sobre los
registros o flujos de datos o preservación o control o acceso o
publicación pero sus leyes son humanas y ocupan un territorio particular
y el servidor está en la nube y eso significa que el servidor siempre
está un paso adelante de cualquier regla que hagas o dos o tres o seis o
¡puf! Me acabo de dar cuenta que estoy sujeto a regulación, creo que me
voy a Oceanía.

Lo que significa es que en efecto, perdimos la habilidad para usar
regulación legal o cualquier otra cosa sobre la arquitectura física de
la red para interferir en el proceso de caída de la inocencia que era
ahora inevitable en la etapa de la que hablo, que podríamos llamar
Google tardío etapa 1.

Aquí es donde, por supuesto, entra el Sr. Zuckerberg.

La raza humana es susceptible al daño pero el Sr. Zuckerberg ha
alcanzado un récord envidiable: ha hecho más daño a la raza humana que
cualquier otro de su edad.

Porque ha aprovechado el viernes a la noche. Esto es, todos necesitan
acostarse con alguien y él convirtió esto en una estructura para
degenerar la integridad de la personalidad humana y hasta una extensión
remarcable tuvo éxito con un trato bastante pobre. Es decir, "te voy a
dar alojamiento web gratis y algunos pendorchos PHP y también obtenés
espionaje gratis todo el tiempo". Y funciona.

Esa es la parte triste, funciona.

¿Cómo pudo pasar esto?

No había una razón arquitectural, en verdad. No había una razón
arquitectural.  Facebook es la Web con "Me voy a quedar todos los
registros, ¿cómo te sentís sobre eso?" Es un terrario de cómo se siente
vivir en un panóptico construido de partes web.

Y no debería permitirse. Se reduce a eso. No debería permitirse. Es una
manera muy pobre de entregar esos servicios. Están groseramente
sobrevaluados para "espionaje todo el tiempo". No son técnicamente
innovadores. Dependen de una arquitectura sujeta al abuso y el modelo de
negocio que lo sostiene es abuso. No hay ningún otro modelo de negocio
para ellos. Esto es malo.

No estoy sugiriendo que deba ser ilegal. Tendría que ser obsoleto. Somos
tecnólogos, deberíamos _arreglarlo_.

Estoy contento de estar con ustedes hasta ahora. Cuando llego a cómo
debemos arreglarlo espero que todavía estén conmigo para que podamos
hacerlo.

Pero digamos, por ahora, que ese es un muy buen ejemplo de cómo lo
hicimos mal y lo que nos pasó por eso. Es más engañoso con Gmail por esa
mágica cualidad de no haber sido tocado por manos humanas. Cuando le
digo a mis estudiantes, "por qué dejan que otra gente lea sus correos?",
me responden "pero nadie está leyendo mi correo, ningún ser humano lo ha
tocado. Eso me horrorizaría, me asustaría que los tipos de Google estén
leyendo mi correo. Pero no está pasando así que no tengo problema."

Ahora, no podemos decir esto de Facebook. En efecto, ellos saben
demasiado sobre Facebook si se permitieran saberlo realmente. Ustedes
leyeron y saben. Los trabajadores de Facebook saben quién va a tener un
amorío antes que la gente porque pueden ver que X revisa obsesivamente
la página en Facebook de Y. Hay algunas investigaciones muy buenas
hechas un par de años atrás por estudiantes del MIT que no voy a nombrar
porque no respetaron los términos de servicio de Facebook durante su
investigación. Sólo estaban revolviendo el contenido de algunas páginas,
pero el propósito de esto era demostrar que podían encontrar
homosexuales no declarados en Facebook.

No dicen nada sobre su orientación sexual. Sus amigos están declarados,
sus intereses son los intereses de sus amigos declarados. Sus fotos
están etiquetadas con sus amigos declarados y ellos están declarados
sólo que no. Sólo están declarados en Facebook si alguien mira, que
seguramente no es lo que tenían en mente y seguramente no es lo que
teníamos en mente sobre ellos. En efecto, el grado potencial de
desigualdad informacional y la alteración y dificultad que surgen de un
malentendido, un error heurístico, en las mentes de los seres humanos
acerca de qué es y qué no es descubrible acerca de ellos no es nuestro
mayor problema con la privacidad.

Mis estudiantes, y sospecho que muchos de los estudiantes de los
educadores de esta sala también, muestran constantemente está dificultad
en nuestro diálogo.  Ellos piensan todavía en la privacidad como "el
gran secreto que no quiero que se revele" y ese no es el problema. Su
problema es todo el resto que forma el relleno, los datos que rellenan
la vida, que no piensan de ninguna manera como un secreto pero que se
agrega a lo que no quieren que nadie sepa. Lo que se agrega, en efecto,
no sólo a lo que no quieren que otros sepan sino también a modelos
predictivos sobre ellos de los que se horrorizarían si supieran que
existen. La simplicidad con la que podés desanonimizar datos
teóricamente anónimos, la facilidad con la que, de múltiples fuentes
disponibles a través de terceras o cuartas partes, se puede ensamblar
información, hacer mapas de la vida de la gente. La facilidad con la que
empezás a juntar, con las pocas cosas que sabés de la gente, los datos
que están disponibles para inferir inmensidad de cosas más.

Mi amigo y colega Bradly Kuhn que trabaja en el Centro Legal del
Software Libre (SFLC) es uno de esos seres humanos arcaicos que cree que
su número de seguridad social es una cosa privada. Y se toma grandes
molestias para asegurarse que su número de seguridad social no sea
revelada, lo cual es su derecho bajo nuestra ley, aunque suene raro.
Pero, tratá de obtener seguro médico o una caja de depósitos segura, o
de hecho, operar en negocios siquiera. A veces hacemos malabares con
nuestros asuntos porque el número de seguridad social de Bradly es un
secreto. Un día le dije "sabés, ya está, Google ya conoce tu número de
seguridad social". Él dijo, "no, no lo saben, nunca se lo dije a nadie".
Yo dije, "si pero conocen los números de seguridad social de todos los
demás que nacieron en Baltimore ese año. El tuyo es el que falta".

Y como ustedes saben, es verdad. Los datos que inferimos son los datos
en los agujeros entre los datos que ya conocemos, si sabemos lo
suficiente.

Así que el lugar donde vivimos se ha convertido en un lugar del que
sería muy poco inteligente decir que no hay nada que no se sepa. Si sos
bastante bien conocido en la Red, y cada uno de nosotros por una razón u
otra es bastante bien conocido en la Red. Queremos vivir ahí. Es nuestro
vecindario. Lo que no queremos es vivir con una cámara en cada árbol y
un micrófono en cada arbusto y un minero de datos bajo nuestros pies
mientras caminamos y la Red es así ahora.  Este no es un juicio estético
del '95 sobre cómo el vecindario se llenó de gente que no comparte
nuestro etnocentrismo tecnogeek. No estoy lamentando el progreso de
alguna forma democratizante. Al contrario, lamento el progreso hostil a
la libertad humana. Todos sabemos lo que es hostil a la libertad humana.
Todos comprendemos las posibilidades despóticas gracias a las distopías
en que es fértil la ciencia ficción que leímos cuando éramos chicos. La
Guerra Fría fue fértil en la invención fantástica de cómo vivimos ahora
y es difícil aceptarlo aunque sea verdad. Afortunadamente, por supuesto,
no es propiedad del gobierno.  Bueno, lo es. Es afortunado. Es verdad.
Es afortunado que sea propiedad de gente a la que podemos sobornar no
importa quién seas. Si sos el gobierno hay formas muy fáciles de
hacerlo. Llenás un formulario de citación (subpoena) y lo mandás por
correo.

Pasé dos horas ayer en una clase de leyes explicando en detalle por qué
la Cuarta Enmienda ya no existe porque fue un jueves por la noche y
¿quién haría eso un viernes por la noche? Pero la Cuarta Enmienda no
existe más. Voy a poner la grabación en la Red y el FBI y ustedes pueden
escucharla cuando quieran.

Tenemos que avivarnos si somos los que nos preocupamos por la libertad,
el juego empezó hace tiempo y estamos atrasados. Hicimos muchas cosas
buenas y tenemos un montón de herramientas dando vueltas que construimos
durante los últimos 25 años. Yo mismo ayudé a la gente a construirlas.
Ayudé a la gente a mantenerlas a salvo, ayudé a la gente a prevenir que
el monopolio ponga todas esas herramientas en su bolsa y se las lleve y
estoy contento de que esas herramientas estén por ahí pero tenemos que
admitir que no las hemos usado para proteger la libertad porque la
libertad está decayendo y eso es lo que quiso decir David en su amable
introducción.

De hecho, la gente que está invirtiendo en las nuevas empresas de la
no-libertad es también la que escuchás si pasas tiempo en Sillicon
Valley en estos días diciendo que el código abierto se ha vuelto
irrelevante. ¿Cuál es su lógica? Su lógica es que el software como un
servicio se está convirtiendo en la forma del mundo. Ya que nadie va a
obtener software nunca más, las licencias que dicen "si le das software
a la gente también tenés que darles libertad" ya no importan porque no
le estás dando software a nadie. Sólo les estás dando servicios.

Bueno, está bien. El código abierto ya no importa. El software libre
importa mucho porque, por supuesto, el software libre es código abierto
con libertad.  Stallman tenía razón. La libertad es lo que importa. El
resto es sólo código fuente. La libertad todavía importa y lo que
tenemos que hacer es hacer que el software libre importe en el problema
en el que servicios no libres son proveídos en formas no libres que
empiezan a deteriorar la estructura de la libertad humana.

Como un montón de no-libertades, el verdadero proceso social inmanente
que fuerza esta no-libertad no es más que la conveniencia percibida.

Todas las formas de libertad sobrepasan la conveniencia percibida.
Ustedes lo saben. Han dejado de pagar las cosas en efectivo. Usan una
tarjeta que pueden agitar frente a un lector RFID.

La conveniencia dicta que necesitás alojamiento web gratuito y
chirimbolos PHP como recompensa a dejarte espiar todo el tiempo porque
los servidores web son terriblemente difíciles de correr. ¿Quién podría
tener un servidor web propio y mantener los registros? Sería brutal.
Bueno, lo sería si fuera IIS[^1]. Era una autorrealización, estaba
pensado para que así fuera.  Estaba diseñado para decir "vos sos un
cliente, yo soy un servidor, yo inventé Windows 7. Me voy a quedar los
registros, muchas gracias." Así era la industria. Nosotros construimos
otra industria. Está aquí. Pero no está \[en uso\]. Bueno, sí, está aquí
de alguna manera. Asi qué ¿dónde no está? Bueno, no está en el servidor
web personal que no tengo y que prevendría que cayera...  bueno, ¿por
qué no hacemos algo al respecto?

¿Qué necesitamos? Necesitamos un buen servidor web que puedas poner en
tu bolsillo y enchufar en cualquier lado. En otras palabras, no debería
ser más grande que un cargador de celular y deberías poder enchufarlo en
cualquier tomacorriente del mundo y en cualquier cable cercano o
sincronizarlo con cualquier router WiFi que esté en el vecindario.
Tendría que tener un par de puertos USB para enchufarle cosas. Debería
saber cómo levantarse solo. Debería saber cómo iniciar el servidor web,
cómo recolectar todas tus cosas de las redes sociales en que las tengas.
Debería saber cómo enviar una copia de seguridad cifrada de todo a los
servidores de tus amigos. Debería saber cómo microbloguear. Debería
saber cómo hacer un ruido que suene como tweet pero no infrinja la marca
de nadie. En otras palabras, debería saber cómo ser vos... ah perdónenme
porque necesito usar una palabra peligrosa -tu avatar- en una red libre
que trabaja para vos y que mantiene los registros. Siempre podés saber
qué pasa en tu servidor y si alguien quiere saberlo tiene que
conseguirse una orden de registro.

Y si querés mudar tu servidor a Oceanía o Sealand o Nueva Zelanda o el
Polo Norte, te comprás un pasaje de avión y lo ponés en tu bolsillo. Lo
llevás ahí.  Lo dejás. Ahora hay un poco más que necesitamos hacer. Es
trivial. Necesitamos DNS dinámico y todas cosas que ya inventamos. Está
todo ahí, nadie necesita algo especial. ¿Tenemos el servidor que podés
poner en tu bolsillo? En efecto, lo tenemos. De la góndola de hardware.
Hermosos y pequeños aparatos de pared con chips ARM. Exactamente lo que
especifiqué recién. Los enchufás, los conectás.  ¿Cuál es el software
que tiene? Bueno, es cualquier software que le quieras poner.

De hecho, te lo mandan con la [distro] más popular adentro, sólo tenés
que decir la que querés. ¿Cuál querés? Bueno podés querer Debian
GNU/Linux para Redes Sociales y va a serte entregado libremente,
libremente como en libertad quiero decir. Lo que hace que todas las
cosas que nombro -levantarse, correr su pequeño Apache o lighttpd o su
diminuto httpd, hacer todas las cosas que necesito que haga
-sincronizarse, obtener tus datos de redes sociales, absorberlos, buscar
tus copias de seguridad, encontrar a tus amigos, registrar tu DNS
dinámico. Todo es trivial. Todas son cosas que tenemos.  Necesitamos
ponerlas juntas. No estoy hablando de algo que es difícil para nosotros.
Tenemos que armar un dispositivo de distribución de software libre.
¿Cuántos necesitamos?

Necesitamos darles un montón a todos nuestros amigos y necesitamos
decirles, tomen jueguen con esto y mejórenlo. Necesitamos hacer lo que
realmente somos buenos haciendo porque todo lo demás ya está hecho, en
la bolsa, listo y barato.  Esos servidores de pared están US\$99 ahora y
están bajando a 79 USD y cuando haya cinco millones de ellos costarán
29.99 USD.

Entonces vamos a la gente y les decimos US\$29.99 por única vez, muy
buena red social, se actualiza automáticamente, el software es tan
fuerte que no lo podrías voltear aunque lo patearas, usado en miles de
millones de servidores en todo el planeta haciendo un trabajo
maravilloso. ¿Y sabés qué? Obtenés no-espionaje gratis. ¿Quieren saber
qué es lo que tenés ahí? Que se consigan una orden de registro de tu
casa, tu castillo, el lugar donde la Cuarta Enmienda todavía existe de
alguna manera cada martes o jueves cuando la Corte Suprema no entra en
sesión. Podemos hacerlo. Podemos hacerlo. Eso requiere que hagamos sólo
lo que somos realmente buenos haciendo. El resto lo conseguimos
libremente. ¿El Sr. Zuckerberg? No tanto.

Porque por supuesto, cuando hay un competidor a "todo el espionaje
permanente aunque no te guste", la competencia va a ir realmente bien.
No esperen que Google sea el competidor. Esa es nuestra plataforma. Lo
que necesitamos es hacer algo tan grasoso que no haya otra plataforma de
red social nunca más. ¿Podemos hacerlo? Si, absolutamente. De hecho, si
no tienen cita el viernes a la noche, armemos un hackfest y hagámoslo.
Está bien a nuestro alcance.

¿Vamos a hacerlo antes que el IPO de Facebook? ¿O vamos a esperar hasta
después?  ¿Realmente? ¿Honestamente? Seriamente. El problema que tiene
la ley muy a menudo en el mundo en que vivimos y practicamos y
trabajamos, el problema que la ley tiene muy a menudo, es el problema
que la tecnología puede solucionar. Y el problema que la tecnología
puede solucionar es el lugar al que vamos a la ley.  Ese es el
movimiento del software libre. Está el hacking de software por acá y
está el hacking legal por allá y cuando juntás ambos el todo es superior
a la suma de las partes. Entonces, no es que tenemos que vivir en la
catástrofe. No es que empezar a revertir la catástrofe es difícil para
nosotros. Necesitamos rearquitecturar los servicios en la Red.
Necesitamos redistribuir los servicios de vuelta hacia los bordes.
Necesitamos devirtualizar los servidores donde nuestra vida está
almacenada y necesitamos recuperar alguna autonomía para vos como el
dueño del servidor.

Las medidas para tomar estos pasos son técnicas. Como es usual, los
fabricantes de los aparatos se nos adelantaron. El hardware no nos
limita. Como es usual, en estos días, el software no es una limitación
porque hicimos mucho software maravilloso que de hecho es usado por
todos los tipos que están del lado de la mala arquitectura. No quieren
pasársela sin nuestro software. La mala arquitectura está habilitada,
sostenida por nosotros. La rearquitectura también.  Y tenemos nuestro
beneficio mágico habitual. Si tenemos una copia de lo que estamos
hablando, tenemos todas las copias que necesitamos. No tenemos
limitaciones de manufactura o transporte o logística. Si terminamos el
trabajo, ya está. Escalamos.

Este es un desafío técnico por una razón social. Es una frontera por
explorar de la gente técnica. Hay un enorme retorno social por hacerlo.

El retorno es claro porque el daño a reparar existe y gente que conocen
está sufriéndolo. Todo lo que sabemos acerca de por qué hacer software
libre dice que este es el momento en que estamos en nuestro ambiente. Es
un desafío técnico alcanzable incrementalmente por extensión de dónde
estamos parados ahora y de quiénes nos preocupamos mejor. Nunca en 25
años de hacer este trabajo, nunca nos he visto fallar al enfrentar un
desafío que puede definirse en estos términos.  Así que tampoco pienso
que vayamos a fallar ahora.

El Sr. Zuckerberg merece la bancarrota por lejos.

Vamos a dársela. Gratis.

Y yo prometo, y ustedes deberían prometer también, no espiar en el
proceso de bancarrota. No es nuestro asunto. Es privado.

Esta es una historia con un final feliz en potencia. Es una historia
potencialmente feliz y si lo hacemos entonces habremos acallado un rumor
más acerca de nuestra irrelevancia y todo el mundo en el Valle va a
tener que encontrar otra palabra de moda y todos los tipos que piensan
que Sandhill Road va a surgir en nuevo poder y gloria espiando a todos y
monetizando el espionaje va a tener que encontrarse otra línea de
trabajo, y todo esto está puramente del lado de los ángeles. Puramente
del lado de los ángeles.

No nos vamos a sacar de encima todos nuestros problemas, de ninguna
manera, pero solamente el mover los registros de ellos a ustedes es el
mayor paso que podemos tomar hacia resolver un rango entero de problemas
sociales que siento muchísimo sobre lo que queda de mi Constitución
estadounidense y que sentiré muchísimo si estuviera viendo fallar la ley
de protección de datos europea desde adentro en lugar de desde afuera y
que me sentiré un poco esperanzado si fuera, no sé, un amigo mío en
China. Porque ustedes saben que por supuesto tenemos que poner una VPN
adentro de ese aparato.

Y probablemente tengamos que ponerle un enrutador Tor.

Y por supuesto, tenemos Bittorrent, y al momento de terminar todo esto,
tenemos el aparato de la libertad. Tenemos un aparato que no solamente
nos saca del pozo en el que estamos, tenemos un aparato que pone una
escalera para la gente que está más profundo que nosotros en ese pozo,
que es otra cosa que nos encanta hacer.

Lo que creo es que el Departamento de Estado de EEUU va a estar puteando
\[slanging\] al Partido Comunista Chino por un año o dos acerca de la
libertad en Internet y creo que el Partido Comunista Chino va a putear
también y lo que van a decir es "¿Ustedes piensan que tienen una buena
privacidad y autonomía en la Internet en su vecindario?" Y cada vez que
hacen eso ahora como si lo hubieran estado haciendo desde hace 2 semanas
solamente diría ¡ay! si fuera Hillary Clinton y supiera algo del tema
porque no la tenemos. No la tenemos. Es verdad.  Tenemos un tipo
capitalista y ellos tienen uno de tipo vanguardia centralista del
partido o tal vez algo así como marxista o tal vez marxista o tal vez
sólo totalitaria pero no vamos a ganar la discusión sobre la libertad en
la Red con Facebook sobre nuestras espaldas. No vamos a ganarla.

Pero empiecen a instalar esos servidores de pared en la sociedad
norteamericana y empiecen a retomar los registros y ¿querés saber con
quién hablé el viernes a la noche? Conseguite una orden de registro y
dejá de leer mi correo. A propósito ahí está mi llave GPG y ahora
estamos realmente cifrando y así y así y así y empieza a parecerse a
algo que querríamos convertir en una cruzada nacional. Realmente estamos
creando libertad para otra gente. Para gente que vive en lugares en los
que la web no funciona.

Así que no es un desafío que no queremos enfrentar. Es uno que queremos
enfrentar con ganas. De hecho, estamos en un estado feliz donde todos
los beneficios que podemos conseguir sobrepasan por mucho la complejidad
técnica de hacer lo que tenemos que hacer, que no es mucho.

De ahí es de donde venimos. Venimos de donde nuestra tecnología era más
libre de lo que pensamos y de donde regalamos un montón de libertad
antes de que supiéramos que en realidad no existía más. Venimos de donde
el software no libre tuvo malas consecuencias sociales más allá de lo
que incluso los agitadores libertarios sabían. Venimos de metáforas no
libres que tienden a producir mala tecnología.

En otras palabras, venimos de cosas a las que nuestro movimiento estaba
diseñada para enfrentar desde el principio pero venimos de ahí. Y
todavía estamos viviendo con las consecuencias de no haberlo hecho lo
bastante bien la primera vez, aunque lo alcanzamos gracias a Richard
Stallman y seguimos.

Donde vivimos ahora no es el lugar donde vamos a ver vivir a nuestros
nietos.  Donde vivimos ahora no es el lugar donde queremos hacer tours
guiados. Antes les decía a mis estudiantes ¿cuántas cámaras hay entre el
lugar donde viven y la Escuela de Leyes? Cuéntenlas. Ahora le digo a mis
estudiantes ¿cuántas cámaras hay entre la puerta del colegio y este
aula? Cuéntenlas.

Ahora les digo a mis estudiantes "¿pueden encontrar un lugar donde no
haya cámaras?" Ahora, lo que pasó en ese proceso fue que creamos
inmensos auxiliares cognitivos para el Estado -enormes máquinas para
escuchar. Ustedes saben cómo es si viven en una universidad
estadounidense gracias a las compañías de música y películas que te
recuerdan todo el tiempo que vivís en el medio de una red enorme de
vigilancia. Estamos rodeados por gente escuchándonos y mirándonos.
Estamos rodeados de datos explotables.

No todo eso va a desvanecerse porque tomemos Facebook y lo dividamos y
nos llevemos nuestros pequeños fragmentos de él. No va a desvanecerse
porque ya no aceptemos alojamiento web gratis con espionaje adentro.
Tenemos otro trabajo que hacer. Algo de ese trabajo es trabajo de
abogados. Admito eso. Algo de este trabajo es escribir leyes y litigar y
crear problemas y otras cosas de abogados.  Está bien. Estoy listo.

Mis amigos y yo vamos a hacer la parte de los abogados. Sería mucho más
simple hacer el trabajo de abogado si viviéramos en una sociedad que
entendiera mejor qué es la privacidad. Sería mucho más simple hacer el
trabajo de abogado si la gente joven se diera cuenta cuando crezca y
empiece a votar o ya esté votando ahora que es grande, que esto es un
problema. Que necesitan terminar de hacer lo que queda de la misma
manera que arreglábamos las grandes cosas cuando éramos chicos. Vamos a
tenerlo mucho más fácil con la enorme confusión de solapamiento
internacional de regímenes cuando hayamos deteriorado la inmensa fuerza
del capitalismo norteamericano que nos fuerza a ser menos libres y más
vigilados para provecho de otra gente todo el tiempo. No es que esto va
a resolver todos los problemas pero el trabajo fácil es muy rico y
gratificante ahora mismo.

Estos problemas son muy malos. Terminar con los más fáciles va a mejorar
la política para resolver los difíciles y está justo en nuestro camino.
La solución está hecha de nuestras partes. Tenemos que hacerlo. Ese es
mi mensaje. Es viernes a la noche. Alguna gente no quiere irse derecho a
programar, estoy seguro. Podemos atrasarlo hasta el martes pero ¿cuánto
más quieren esperar?  Saben que cada día que pasa se van más datos que
nunca van a volver. Cada día que pasa hay más inferencias sobre los
datos que no podemos deshacer. Cada día que pasa apilamos más cosas en
las manos de la gente que tiene demasiado. Así que no es que debamos
decir "uno de estos días me voy a poner a hacerlo". No es que debamos
decir "Creo que en cambio voy a pasar mi tiempo navegando noticias sobre
el iPad".

Es mucho más urgente que eso.

Es que no nos hemos dado a nosotros mismos la dirección a la que ir así
que démosnos la dirección a la que ir. La dirección a la que ir es hacia
la libertad usando software libre para hacer justicia social.

Pero ustedes saben esto. Ese es el problema de hablar un viernes por la
noche.  Hablás por una hora y todo lo que le decís a la gente es algo
que ya saben.

Así que muchas gracias. Ahora acepto preguntas.



[^1]: Internet Information Server, servidor web que viene con Microsoft Windows

[^2]: _logs_.

[0]: http://ur1.ca/1jyl4 "Eben Moglen"
[1]: http://www.isoc-ny.org/ "Internet Society New York"
[2]: http://ur1.ca/lch5 "Grabación de Libertad en la Nube"
[3]: http://ur1.ca/uups "Desgrabación"
[4]: http://creativecommons.org/licenses/by-sa/3.0/us/legalcode "CC-BY-SA 3.0 US"

[distro]: Distribución de GNU/Linux.
