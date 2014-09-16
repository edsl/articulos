---
layout: post
title: "Proyecto Harmony considerado dañino"
author: "Bradley M. Kuhn"
cover: "images/cover_endefensadelsl_nr1.png"
old-slug: harmony_harmful.html
license: https://creativecommons.org/licenses/by-sa/3.0/us
---

Proyecto Harmony considerado dañino
===================================

> Esta traducción y el artículo original se liberan bajo
> [Creative Commons Atribución CompartirDerivadasIgual
> 3.0 de Argentina](http://ur1.ca/2djpm) y [Estados
> Unidos](http://creativecommons.org/licenses/by-sa/3.0/us/legalcode)
> respectivamente. Traducido por Nicolás Reynolds y Mauricio Pasquier
> Juan.

_Jueves 7 de Julio de 2011 por Bradley M. Kuhn_

Mucha publicidad se diseña para convencernos de comprar o usar algo que no
necesitamos. Cuando escucho a alguien zumbando sobre alguna cosa nueva,
maravillosa, me preocupo pensando que esos tipos están tratando de venderme
algo.

Muy pronto, es probable que vean una campaña de marketing para esta cosa
llamada Proyecto Harmony (que recientemente ha lanzado la versión 1.0 de sus
plantillas de documentos). Incluso el nombre es marketing: no es realmente
descriptivo, sino que trata de venderte una "buena onda" sobre el proyecto aun
sin saber de qué se trata. (Además tuvo una [seria][9] [colisión][10] de
[nombres][11], [incluso][12] con otro proyecto de software libre.)

El Proyecto Harmony se vende a sí mismo como reparación de algo que nuestra
comunidad realmente no considera roto. El Proyecto Harmony es un juego de
plantillas de documentos, principalmente promulgadas y diseñadas por abogados
corporativos, que intentan seducir a los desarrolladores a entregar el control
de su trabajo a las compañías.

Mi análisis a continuación trata principalmente sobre cómo estos acuerdos son
problemáticos para los desarrolladores individuales. Un análisis de los
acuerdos a la luz de las compañías u organizaciones que los usen entre sí puede
o no tener las mismas conclusiones, pero no puedo asegurarlo todavía.

\[ A propósito, soy conciente que he fallado en proveer una versión TL;DR de
este artículo. Intenté hacerlo dos veces y finalmente decidí que no puedo.
Estos problemas son complejos y tenía que tomar una década de licenciamiento de
software libre, políticas y conocimiento organizacional para articular
completamente qué es lo que está mal con los acuerdos del Proyecto Harmony. Me
doy cuenta de que suena a "fue difícil de escribir, debería ser difícil de
leer", pero no sé cómo resumir estos problemas gordianos. No obstante espero
que los desarrolladores se tomen el tiempo de leer esto antes de firmar un
acuerdo del Proyecto Harmony, o, de hecho, cualquier CLA o ©AA. \]


Una cesión de copyright que carece de garantías reales
------------------------------------------------------

Antes que nada, casi la mitad del Proyecto Harmony se trata de acuerdos de
asignación de copyright (©AA por sus siglas en inglés). La asignación de
copyright cede completamente el trabajo a alguien más. Una vez que el ©AA está
firmado, el trabajo deja de pertenecer al asignante. Es como si el trabajo en
realidad hubiera sido hecho por el asignado. Admitido, hay algún valor en la
asignación de copyright, particularmente cuando los desarrolladores quieren
asegurarse que la GPL u otra forma de copyleft es debidamente protegida en su
trabajo pero no tienen el tiempo de hacerlo ellos mismos. (Aunque los
desarrolladores también pueden designar un agente de ejecución que lo haga
en su nombre sin tener que asignar el copyright, así que esa necesidad es
limitada.)

Uno debe tener una confianza inmensa en la organización asignada.
Personalmente, yo sólo he asignado algunos de mis copyright a una sola
organización en toda mi vida: la [Free Software Foundation][13], porque la FSF
es la única organización que he encontrado que está institucionalmente
comprometida a hacer lo correcto con los copyrights de forma similar a mis
creencias morales personales.

En primer lugar, [como he escrito antes][14], los ©AA de la FSF hacen toda
suerte de promesas al asignante. En segundo, la FSF está institucionalmente
comprometida con [la GPL][15] y en hacer cumplir la GPL de forma de avanzar la
militancia sin fines de lucro de la FSF por la libertad del software. Toda esta
actividad está contenida en mis principios morales, por lo que no he tenido
problema en firmar los ©AA de la FSF.

Aún así, he conocido _muchos_ desarrolladores que se niegan a firmar los ©AA de
la FSF. Mientras muchos de ellos aprueban la GPL, no necesariamente acuerdan
con las posiciones morales de la FSF. En efecto, en muchos casos, estos
desarrolladores se oponen completamente a asignar el copyright a nadie, sea la
FSF o cualquier otro. Por ejemplo, [Linus Torvalds][16], fundador de Linux, ha
declarado repetidas veces que "nunca quis\[o\] hacer asignaciones de copyright,
por varias razones: personalmente piens\[a\] que son sucias y erróneas, odiaría
hacer todo el papeleo y piens\[a\] que actuaría como detractor del modelo de
desarrollo".

Obviamente, mi posición no es tan radical como la de Linus; pienso que los ©AA
pueden ser apropiados en ciertas ocasiones. Pero también creo que los
desarrolladores nunca deberían asignar su copyright a una compañía u
organización cuya filosofía moral no cabe en la suya propia.

La FSF, por su parte, se expide sobre su posición moral en sus ©AA mismos. Como
[mencioné en otra parte][17], y como [Groklaw][18] recientemente cubrió en
detalle, los ©AA de la FSF realizan varias promesas con validez legal a los
desarrolladores que las firman. Mientras, los ©AA del Proyecto Harmony ponen
unas pocas opciones que parecen vagamente aceptables (aunque tienen problemas
propios que discuto más abajo), no las hacen obligatorias. Yo mismo he señalado
en varias ocasiones a los que escribieron los borradores de Harmony que [los
términos][19] que la FSF ha propuesto deberían ser obligatorios en cualquier ©AA
de una compañía con fines de lucro, pero se han negado a incorporar estas
garantías como un requisito de sus acuerdos. (Noten que tales garantías también
deben incluirse en las opciones de los CLA; ver debajo para más detalles.)

Por último me gustaría señalar que la FSF **no** requieren ©AAs para todos los
[paquetes GNU][20]. Esta confusión es tan común que me gustaría llamar la
atención sobre ella, aunque sea un punto tangencial a este contexto. Los ©AA de
la FSF son obligatorios, según mi conocimiento, si los paquetes GNU fueron (a)
desarrollados por empleados de la FSF en sus primeras versiones o (b) los
desarrolladores originales le _pidieron_ a la FSF que realice una asignación de
copyright cuando su proyecto se unió a GNU. En todos los demás casos, la
asignación a la FSF es opcional. Algunos proyectos GNU, como [GNOME][21],
tienen sus propias posiciones sobre los ©AAs que difieren radicalmente de las
de la FSF. Dudo seriamente que las compañías que adopten los acuerdos del
Proyecto Harmony lleguen a ser tan flexibles en cuanto a la asignación de
copyright como lo es la FSF, o que alguna de las opciones posibles que el
Proyecto Harmony provea sean aceptables para la política actual de GNOME.


¿Regalar tus derechos para que las compañías sientan mariposas en la panza?
---------------------------------------------------------------------------

El Proyecto Harmony, sin embargo, proclama que la parte importante no son los
©AAs, sino los Acuerdos de Licencia del Contribuidor (CLA por sus siglas en
inglés). Para considerar brevemente la historia de los CLAs de Software Libre,
hay que notar que [el CLA de Apache][22] fue probablemente el primer CLA usado
en la comunidad del Software Libre. La Apache Software Foundation siempre ha
estado fuertemente influenciada por IBM y otras compañías, y tales compañías
generalmente han sentido "mariposas en la panza" al lograr que cada contribuidor
asienta a firmar un documento legal complejo que afirma varias garantías
respecto al código y da ciertos poderes a la compañía.

El punto principal de un CLA (y hasta cierto punto válido) es asegurar que los
desarrolladores han verificado su derecho a contribuir código bajo la licencia
de copyright del proyecto. Tanto el CLA de Apache como los CLA del Proyecto
Harmony llegan a extremos de longitud y verborragia para requerir que los
desarrolladores acuerden que saben que la contribución es suya. De hecho, si un
desarrollador firma uno de estos CLAs, realiza un contrato formal con la
entidad (usualmente una compañía con fines de lucro) en el que reconoce que la
contribución se licencia bajo la licencia del proyecto. ¡Y entonces el
desarrollador asume toda responsabilidad si ese hecho es incorrecto o se pone
en disputa!

Por supuesto, mover toda la responsabilidad sobre los orígenes del código
produce muchas "mariposas en la panza" a los abogados de la compañía. Esos
abogados saben que ahora pueden fácilmente **demandar a un desarrollador
individual** por incumplimiento de contrato si el desarrollador se equivocó en
el código. Si la compañía distribuye el código de un desarrollador y termina
recibiendo una demanda por infracción por la que paga millones de dólares,
pueden fácilmente darse vuelta y demandar al desarrollador.[^0] La compañía
argumentará en la corte que el desarrollador rompió el contrato. Si este
desenlace posible no te preocupa _inmediatamente_ en tanto desarrollador
individual cuando firmás un CLA del Proyecto Harmony por tu contribución libre,
debería.


La "Elección de Ley" y los Arreglos Contractuales embarran los reclamos de copyright
------------------------------------------------------------------------------------

El CLA de Apache no posee una cláusula de elección de ley, lo que es preferible
en mi opinión. La mayoría de los abogados _aman_ una cláusula de "elección de
ley" ("choice of law" en inglés) por varias razones. La más grande es que
significa que las reglas que se aplican sobre el acuerdo son las más familiares
a los abogados y la jurisdicción para las disputas será la jurisdicción local
de la compañía, no la del desarrollador. Adicionalmente, los abogados a menudo
eligen jurisdicciones particulares que son muy favorables a su cliente pero no
lo son para los otros firmantes.

Desafortunadamente, _todos_ los borradores del Proyecto Harmony incluyen una
cláusula de "elección de ley".[^1] Espero que los que escriben los borradores
argumentarán en respuesta que la jurisdicción es una variable de configuración.
No obstante, el problema es que la _compañía_ es la que decide el valor de esa
variable, que casi siempre será la que no prefiera el desarrollador individual.
Probablemente el término no sea negociable en ese punto, aunque haya podido
configurarse en la plantilla.

Y no sólo eso, imaginá un escenario mucho más probable para ese CLA: la
compañía falla en usar la licencia saliente que prometieron. Por ejemplo, supongan que
prometieron a los desarrolladores que sería AGPL para siempre (¡aunque ninguna
opción como esta existe en el Proyecto Harmony, vean más abajo!), pero entonces
la compañía lanza versiones propietarias. Los desarrolladores que firmaron el
CLA todavía detentan copyright, por lo que pueden ejercer sus derechos bajo la ley de
copyright que, por sí misma, puede lograr que los desarrolladores hagan cumplir la
licencia bajo la ley en cualquier jurisdicción que les parezca (asumiendo que
la infracción sucede en esa, por supuesto).

Sin embargo, al firmar un CLA con la clásula de "elección de ley", los
desarrolladores acordaron mantenerse bajo la jurisdicción establecida en el
CLA. El CLA convierte lo que de otra forma hubiera sido una demanda de
infracción de copyright mundana operando solamente bajo la reglamentación de
copyright local al desarrollador en una disputa contractual entre los
desarrolladores y la compañía bajo las leyes de la jurisdicción elegida.
Obviamente ese acuerdo incluiría la AGPL y/o GPL por referencia, pero el
reclamo por infracción de copyright hecho por violación de la GPL está ahora
embarrado por el contrato CLA que los desarrolladores firmaron, y donde
cedieron algunos derechos y permisos a la compañía que van más allá de la GPL.

Aún peor, si el desarrollador realiza la demanda en su propia jurisdicción, esa
jurisdicción se ve forzada a interpretar las leyes de otro lugar. Esto lleva
a resultados altamente variables y confusos.


Problemas para hacer cumplir el copyright individualmente contra terceras partes
--------------------------------------------------------------------------------

Además, aún cuando los desarrolladores individuales retienen sus copyrights,
los CLAs del Proyecto Harmony garantizan muchos derechos y permisos
transferibles al receptor del CLA (otra vez, usualmente a una compañía). Aún
_si_ las razones para requerirlos fuesen nobles, introducen un manojo de
permisos extra que pueden ser pasados a otras entidades.

De repente, lo que una vez fuera una simple demanda para hacer cumplir el
copyright hecha por un desarrollador que descubre una violación del copyleft se
convierte en una pregunta: "¿Recibió de alguna manera esa entidad violatoria
permisos especiales de esta otra entidad colectora del CLA?" Los violadores van
a moverse rápidamente a este tipo de defensa. Aunque la defensa pueda no
tener mérito (por ejemplo, el receptor del CLA ni siquiera conoce al violador),
introduce confusión. La mayoría de los procedimientos legales que involucran
software ya son suficientemente confusos para las cortes debido a la compleja
tecnología involucrada. Agregar algo como esto sólo causará problemas y
demoras, agregando más peso a nuestros mínimamente financiados esfuerzos por
hacer cumplir el copyleft de la comunidad.

![](images/harmony.png)

Entrante=Saliente es todo lo que necesitás
------------------------------------------

Mientras tanto, la pregunta sobre el CLA es esta única consideración
fundamental: ¿Necesitamos esto? La respuesta del Proyecto Harmony es clara: sus
defensores claman que existe una confusión masiva sobre los CLAs y ninguna
estandarización, por lo que el Proyecto Harmony debe proveer un set estándar de
acuerdos que encarnen todas las opciones usadas típicamente.

Aun más, el Proyecto Harmony ha rechazado a propósito ofrecer la opción más
simple y popular de todas, que mi colega Richard Fontana (un abogado de Red Hat
que [también se opone][24] al Proyecto Harmony) [ha llamado][25] [el año pasado
"entrante=saliente"][26]. Específicamente, el acuerdo por defecto en la abrumadora
mayoría de los proyectos FLOSS es simplemente esta: cada contribuidor acuerda
licenciar cada contribución bajo la licencia de copyright específica del
proyecto (o una licencia compatible).

No importa de qué lado mires al Proyecto Harmony, los otros problemas
contractuales descritos arriba vuelven imposible un verdadero entrante=saliente
porque el receptor del CLA nunca está legalmente obligado por la licencia del
proyecto. Mientras tanto, y aún bajo su mejor configuración, el Proyecto
Harmony no puede aproximarse adecuadamente a entrante=saliente.
Específicamente, el Proyecto Harmony intenta limitar el licenciamiento de
saliente en su sección 2.3 (llamada "Licencia saliente"). Sin embargo, todas las
versiones copyleft de esta plantilla incluyen una cláusula que dice: "Nosotros
\[los receptores del CLA\] acordamos licenciar la Contribución \[...\] bajo los
términos de las \[...\] licencias que Nosotros estemos utilizando a la Fecha de
Envío del Material". Pero _no hay forma_ de que el contribuyente verifique con
seguridad cuáles licencias usa en privado la entidad que recibe el CLA. Si esa
entidad ya tiene un modelo de negocio de [relicenciamiento propietario][27]
a la Fecha de Envío, entonces el contribuyente concede su permiso para tal
relicenciamiento en esa contribución nueva, aún si el resto de la sección 2.3
le promete copyleft. Esto no es hipotético: ha habido muchos casos donde no
está claro si la compañía estaba o no estaba involucrada en relicenciamiento
propietario, para más tarde descubrir que lo habían estado haciendo en privado
durante años. Tal como está escrita, por lo tanto, **cualquier configuración de
la sección 2.3 del Proyecto Harmony es inútil para prevenir la apropiación
propietaria**.

Aunque ese bug sea arreglado, lo más cercano que el Proyecto Harmony va a estar
de entrante=saliente es restringiendo sus CLA a "la lista de la FSF de
licencias copyleft recomendadas". Sin embargo, esta categoría no hace ninguna
distinción entre la [AGPL][28] y la GPL, y en última instancia le permite a la
FSF el poder de relicenciar (ya que la FSF [puede cambiar][29] su lista de
copyleft recomendadas a voluntad). Si los contribuyentes son serios sobre la
AGPL, entonces el Proyecto Harmony **no** puede asegurar que sus cambios
permanezcan bajo esta licencia. Aún más, los contribuyentes _deben_ confiar en
la FSF a perpetuidad, aún _más de lo que actualmente necesitan_ en las opciones
"... o subsiguientes" de las licencias de la FSF en existencia. Estoy de
acuerdo en confiar en la FSF en la mayoría de los casos. Sin embargo, ya que
prefiero sólo AGPLv3 o subsiguientes para mi código, el Proyecto Harmony es
completamente incapaz de acomodarse a mis preferencias y aproximarse a un
entrante=saliente que sea AGPL (aún si ignoro los numerosos problemas ya
discutidos).

Mientras tanto, la normal, mundana y extendida práctica entrante=saliente es
simple, efectiva y no mezcla sus complicadas disputas contractuales
y estructuras de control con la gobernanza del proyecto. En esencia, para la
mayoría de los proyectos FLOSS, la licencia de copyright del proyecto sirve
como su Constitución y no le mezcla ninguna otra complicación. El Proyecto
Harmony busca darle maripositas a los abogados a expensas de tirarles el fardo
legal y molesto a los desarrolladores.


Los Hackers de Linux han fijado ingeniosamente entrante=saliente
----------------------------------------------------------------

Hace casi 10 años atrás, recuerdo haber asistido a un sesión del [USENIX 2001
Linux BoF][30]. En esa sesión, [Ted T'so][31] y yo tuvimos un acalorado debate; yo
afirmé que el ©AA de la FSF aseguraba certeza legal sobre el código GNU, pero
que Linux no poseía tal seguro. (Por cierto, incluso _yo_ estaba confundido en
esos días y pensaba que todos los paquetes de GNU requerían un ©AA de la FSF.)
Ted explicó, en la manera clara y brillante habitual, que tales métodos duros
no eran necesarios para darle certeza legal a la GPL y que la comunidad de
Linux quería encontrar una alternativa.

Me fui sacudiendo la cabeza escépticamente. Recuerdo haber pensado: "Ted no
entiende". Pero estaba equivocado; él _sí_ entendía. De hecho, muchos de los
desarrolladores clave de Linux lo hacían. Tres años después de esa conversación
pública con Ted, el [Certificado de Origen del Desarrollador][32] (DCO por sus
siglas en inglés) se convirtió en la forma oficial de manejar el "problema de
los CLA" en Linux y sigue siendo [la política oficial][33] al día de hoy. (Ver
el item 12 en el archivo Documentation/SubmittingPatches de Linux.)

El DCO, en efecto, ¡es el único CLA que necesita cualquier proyecto FLOSS!
Implementa entrante=saliente en una forma simple y directa, sin darle poderes
especiales a ninguna compañía o entidad en particular. Los desarrolladores
mantienen su propio copyright y unilateralmente atestiguan su derecho
a contribuir y la licencia de su contribución. (Además pueden firmar un ©AA con
alguna otra entidad, como la FSF, si quieren.) El DCO también provee una
metodología simple (es decir, la etiqueta Signed-off-by:) para realizar ese
atestiguamiento.

Debo admitir que me he burlado de la simplicidad (que consideraba naïve) del
DCO en comparación al ©AA de la FSF. Desde entonces me he convencido que el DCO
de Linux cumple claramente con su trabajo principal a la vez que se ajusta a la
forma de trabajo preferida por muchos desarrolladores. Los ©AA tienen su lugar,
particularmente cuando los desarrolladores encuentran una organización
confiable que se alinea con su código moral personal y se encargarán de
defender el copyleft por ellos. No obstante, para los CLAs, el DCO de Linux
cumple con este importante trabajo y deja de lado el costado pro-corporativo
inútil.

Francamente, si tengo que elegir entre hacer las cosas fáciles para los
desarrolladores o hacerlas fáciles para los abogados corporativos, voy a elegir
lo primero en todos los casos: los desarrolladores escriben el código;
mientras que la mayor parte del tiempo, los departamentos legales de una
compañía sólo se meten en el medio. La comunidad de FLOSS necesita cubrirse el
culo lo suficiente como para zafar; el DCO muestra lo que es realmente
_necesario_, en oposición a lo que los abogados corporativos _desean_ que hagan
sus desarrolladores.


¿Qué pasa con el relicenciamiento?
----------------------------------

El DCO de Linux no permite que una sola entidad relicencie el código; esta es
la razón por la que el cambio a GPLv3 en Linux será una ardua tarea de procesos
públicos por conseguir el permiso para el cambio. Sin embargo, hay que notar que la cultura
linuxera _cree_ que la GPLv2 es el fundamento moral y el principio de su
comunidad. No es un principio con el que concuerdo; la mayoría de mis lectores
saben que mi [licencia preferida][34] es la AGPLv3 o superior. Pero este es el
punto: entrante=saliente es _la_ forma en que una comunidad FLOSS implementa su
moralidad; el Proyecto Harmony busca remover las decisiones comunitarias
sobre el licenciamiento de casi todos los proyectos.

Estoy a favor de permitir el relicenciamiento "o superior"; la GPL, la LGPL y
la AGPL han dejado la opción a la comunidad ya que la [GPLv1][35] fue publicada
a finales de los '80. Los proyectos se declaran "GPLv2 o superior" o "LGPL o
superior", o incluso ["GPLv1 o superior o Artística"][36] (como Perl 5) para
identificar su cultura y permisos de relicenciamiento. Aunque a veces
sería bueno tener una autoridad en relicenciamiento, el precio es muy caro: el
abandono de una claridad comunitaria con respecto a los términos en que se
define su cultura de desarrollo.


¿Una parcialidad anti copyleft fuerte?
--------------------------------------

Lo que es aun peor, es que el Proyecto Harmony se mantiene parcial contra
algunas de las más afinadas versiones de la cultura copyleft. Por ejemplo,
[Allison Randal][37], quien está muy involucrada en el Proyecto Harmony,
argumentó en el [episodio 204][38] de Linux Outlaws que "la mayoría de los
desarrolladores que contribuyen bajo una licencia copyleft, estarían contentos
de hacerlo bajo cualquier otra, sea AGPL, GPL o LGPL". Sin embargo existen
varias [razones bien definidas][39] de por qué los desarrolladores eligirían la
GPL antes que la LGPL. Por eso, entregarle a una compañía con fines de lucro (o
una sin fines de lucro que no necesariamente comparta los valores de los
desarrolladores) el poder unilateral de tomar decisiones de relicenciamiento
y convertir un proyecto bajo GPL en LGPL o cualquier otra licencia de copyleft
débil es ridículo.

En su lanzamiento 1.0, el Proyecto Harmony intentó agregar una opción de "sólo
copyleft fuerte". Por supuesto que no funciona, por las razones discutidas más
arriba. Pero aun así, esta solución es sólo una de las muchas y no es requerida
por defecto cuando un proyecto ya es copyleft.

Por último, es importante notar que las [GPLv3, AGPLv3 y LGPLv3][40] ya ofrecen
una "opción de apoderado (proxy)"; los proyectos pueden nombrar a alguien para
decidir cambiar a "o superior" más tarde. Por eso, para aquellos proyectos que
estén usando cualquiera del grupo "sólo LGPLv3", "sólo AGPLv3", "sólo GPLv3",
"GPLv2 o superior", "GPLv1 o superior" o "LGPLv2.1 o superior", sus
desarrolladores _ya poseen_ mecanismos para moverse a versiones superiores de
la licencia con facilidad al especificar un apoderado. No hay necesidad de un
CLA para cumplir tal tarea en la familia de licencias GPL, a menos que el
objetivo sea erosionar los copylefts fuertes para convertirlos en copylefts
débiles.


Esto no es Creative Commons, pero si lo fuera, ¿vale la pena emularlo?
----------------------------------------------------------------------

Los defensores del Proyecto Harmony aman compararlo con [Creative
Commons][41], pero la comparación no es particularmente apta. Aún más, no estoy
convencido de la que la comunidad FLOSS deba emular al grupo de licencias de CC
del todo, ya que algunos aspectos de la estructura de CC son problemáticos al
migrarlos al licenciamiento FLOSS.

En primer lugar, [Larry Lessig][42] (quien es ampliamente considerado como un
visionario) inició el licenciamiento CC para capturar un movimiento por la
Cultura Libre que se estaba moldeando a semejanza del movimiento del Software
Libre (la cual pasó una década estudiando). Sin embargo, Lessig realizó varios
compromisos morales en su intento de construir un puente a la mentalidad
"algunos derechos reservados". Así, muchas de las licencias CC -notablemente
las que incluyen las cláusulas NoComercial (NC) o SinDerivadas (ND)- son
consideradas demasiado restrictivas y son por lo tanto rechazadas tanto por
[activistas de la Cultura Libre][43] como por [militantes del Software
Libre][44].

Después de una década, esos militantes empezaron lentamente a convencer a los
titulares de copyright de evitar las opciones NC y ND de CC, pero la
promulgación continua de estas opciones por parte de CC deslegitiman esos
intentos. Así, CC y el Proyecto Harmony cometen el mismo error: actúan
amoralmente en su intento de construir una estructura de licencias/acuerdos que
trata de aunar entendimiento entre una comunidad FaiF ("libre como en libertad",
en inglés "Free as in Freedom") y aquellos que recién están comenzando
a conocerla. Elegí la palabra amoral, como [usualmente hago][45], para denotar
una situación donde existen importantes principios morales, pero sus actores
principales buscan remover la moralidad de consideración con la excusa de dejar
el poder de decisión "a la magia del mercado". El Proyecto Harmony repite el
error de las licencias CC que la comunidad de la Cultura Libre ha pasado una
década (y contando) de limpiar.


Conclusiones
------------

Por favor noten que no soy un abogado y que esto no es un aviso legal. Sólo soy
un desarrollador tanto individual como comunitario enfocado en políticas de
software libre que tiene serias preocupaciones por la forma en que operan los
acuerdos del Proyecto Harmony. No puedo proveer un análisis legal refinado,
porque francamente soy un amateur cuando se trata de leyes, pero _soy_ un
experto en políticas de libertad del software. En esa vena -sin tener en cuenta
el apoyo de los abogados corporativos- mi opinión es que el Proyecto Harmony
debe abandonarse por completo.

De hecho, la distinción entre experticia política y legal muestra la raíz del
problema del Proyecto Harmony. Es un sistema de documentos diseñados por un
comité compuesto principalmente por abogados corporativos, aun cuando se
muestra como un consenso de desarrolladores FLOSS. En efecto, el Proyecto
Harmony fue iniciado por [Amanda Brock][46], una abogada corporativa con fines
de lucro de Canonical, Ltd, que aun trabaja en los borradores. Más tarde,
[Canonical, Ltd.][47] contrató a Mark Radcliffe (un abogado que [ha
defendido][48] [violadores de la GPL][49]) para escribir el borrador de las
versiones alpha del documento, y aun continúa haciéndolo. Aún más, el proceso
primario de escritura de esos borradores se hizo en secreto en reuniones
cerradas dominadas por abogados corporativos hasta que los documentos
estuvieron casi completos; el proceso no se hizo público a la comunidad hasta
abril del 2011. La versión 1.0 de los documentos poco difiere de los borradores
que se lanzaron en abril, y por lo tanto se mantienen como documentos que
fueron principalmente redactados en secreto por abogados corporativos que sólo
tienen una lejana familiaridad con la cultura del software libre.

[He preguntado][50] muchas veces a los defensores del Proyecto Harmony quién
está a cargo del mismo hoy, y nadie puede darme una respuesta directa. Uno se
pregunta quién toma las decisiones finales y cuál es el proceso que existe para
incluir o excluir texto en los borradores. El proceso que una vez fue secreto
ahora parece ser caótico porque fue abierto mucho más tarde de lo necesario
para resolver sus problemas fundamentales.

Sólo unos pocos desarrolladores están involucrados en el proyecto. Pero el
Proyecto Harmony no es algo que los desarrolladores hayan pedido; fue iniciado
por compañías que _quisieran_ convencerlos de adoptar pasivamente estos
extralimitados CLAs y ©AAs. Para mí, el proceso completo del Proyecto Harmony
se siente como una guerra de desgaste para convencer a los desarrolladores de
aceptar algo que no necesariamente quieren con un mínimo de disenso. En
definitiva, la necesidad del Proyecto Harmony no se ha articulado para los
desarrolladores.

Por último, pregunto, ¿qué es lo que está realmente roto? La industria ha
estado adoptando GNU y Linux durante años de manera continua. GNU, por su
parte, tiene las asignaciones de la FSF para muchos de sus proyectos tempranos,
pero los últimos proyectos ([GNOME][51] en particular) han sido absolutamente
contrarios tanto al uso de ©AAs como de CLAs, o se han mostrado indiferentes y
han usado entrante=saliente. Linux, por su lado, usa el DCO, que realiza el
trabajo de manejar las partes más urgentes e importantes de un CLA sin ponerse
en el camino de los desarrolladores y sin forzarles riesgos legales extra y
entregarle las decisiones de licenciamiento (incluyendo las debilitantes del
copyleft) a una única entidad (usualmente con fines de lucro).

En definitiva, el Proyecto Harmony es una solución mal diseñada buscando un
problema.


Véase también (en inglés)
-------------------------

* [El problema con Harmony, Parte I][52] de Richard Fontana

* [Los acuerdos Harmony 1.0][53] de Dave Neary

* [Algunos pensamientos sobre la asignación de copyright][54] de Michael Meek

* [La asignación de copyright y otras barreras para ingresar][55] de Dave Neary

* [El relicenciamiento propietario es el nuevo shareware][56] por mí mismo

* [Cuando una compañía te pide tu copyright][57] de RMS

* [La FSF y el Proyecto Harmony][58] de Brett Smith

* [Hay][59] [varios][60] [hilos][61] [diferentes][62] [que][63] [pueden][64]
  [encontrarse][65] [en][66] [identi.ca][67] [donde][68] [se][69]
  [discuten][70] [los][71] [acuerdos][72] [del][72] [Proyecto][73]
  [Harmony][74]. El hashtag ["#Harmony"][75] se usa a menudo. El hashtag
  ["#CLA"][76] también puede ser de interés.

* [El problema de traer armonía a la asignación de copyright][77] de Jos
  Poortvliet

* [Balanceando transparencia y privacidad][78] de Simon Phipp

* [Política de asignación de copyright de GNOME][79]

* [Los lineamientos de la Fundación GNOME sobre la asignación de copyright][80]

* [El Proyecto Harmony busca mejorar los acuerdos de contribución][81] de
  Amanda Brock

* [Los archivos de la lista de correo del Proyecto Harmony][82]

* [Los borradores de los Acuerdos Harmony][83]

* [Políticas de contribución de proyectos de código abierto][84] diapositivas
  de la charla de Richard Fontana.


[^0]: Los defensores del Proyecto Harmony reclamarán que su sección 5, "Renuncia
consecuencial de daño", protege adecuadamente a los desarrolladores. Noto que
deja afuera explícitamente a, por ejemplo, los daños estatutarios de la
infracción de copyright. Además, no puede renunciarse a algunos tipos de daños
(y es por eso que esa sección le grita al lector "EN LA MEDIDA EN QUE LA LEY LO
PERMITA"). Noten mi discusión sobre las jurisdicciones en el texto principal de
este artículo, y consideren el hecho que el receptor de un CLA obviamente
seleccionará la jurisdicción donde se pueda renunciar a la menor cantidad de
daños. Finalmente, noten que la parte "O NOSOTROS" de esa sección 5 está
disponible opcionalmente, y seguramente los abogados corporativos la usarán, lo
que significa que si ellos violan el acuerdo, básicamente no tenés forma de
recibir alguna renuncia de daño de parte de ellos, aun si prometieron mantener
el código bajo copyleft.

[^1]: *Nota:* Versiones tempranas de este artículo mezclaron "elección de sede" con
"elección de ley". El fraseo ha sido aclarado para solucionar este problema.
Por favor envíenme comentarios o correo si creen que no ha sido corregido
adecuadamente.

[1]:http://ebb.org/bkuhn/rss.xml
[2]:http://ebb.org/bkuhn/blog/rss.xml
[3]:http://identi.ca/bkuhn/
[4]:http://identi.ca/api/statuses/user_timeline/bkuhn.rss
[5]:http://ebb.org/bkuhn/articles/rss.xml
[6]:http://github.com/bkuhn/jekyll
[7]:http://orgmode.org/
[8]:http://github.com/Chrononaut/happyblogger/tree/master
[9]:http://www.projectharmony.com/
[10]:http://www.projectharmonynyc.org/
[11]:http://www.harmony-project.org/
[12]:http://harmony.apache.org/
[13]:http://fsf.org
[14]:http://ebb.org/bkuhn/blog/2010/02/01/copyright-not-all-equal.html
[15]:http://www.gnu.org/licenses/gpl.html
[16]:http://groups.google.com/group/fa.linux.kernel/msg/b0587ac4dcb7a79b
[17]:http://ebb.org/bkuhn/blog/2010/02/01/copyright-not-all-equal.html
[18]:http://www.groklaw.net/articlebasic.php?story=20110524120303815
[19]:http://www.fsf.org/blogs/rms/assigning-copyright
[20]:http://www.gnu.org/help/evaluation.html
[21]:http://live.gnome.org/CopyrightAssignment
[22]:http://www.apache.org/licenses/icla.txt
[23]:http://www.apache.org/licenses/icla.txt
[24]:http://opensource.com/law/11/7/trouble-harmony-part-1
[25]:http://identi.ca/conversation/45589896
[26]:http://ref.fedorapeople.org/fontana-linuxcon.html
[27]:http://ebb.org/bkuhn/blog/2009/10/16/open-core-shareware.html
[28]:http://www.gnu.org/licenses/agpl.html
[29]:http://www.gnu.org/licenses/recommended-copylefts.html
[30]:http://www.usenix.org/event/usenix01/bofschedule.html
[31]:http://thunk.org/tytso
[32]:http://permalink.gmane.org/gmane.linux.kernel.commits.head/33254
[33]:http://www.kernel.org/doc/Documentation/SubmittingPatches
[34]:http://ebb.org/bkuhn/blog/2011/05/26/choose.html
[35]:http://www.gnu.org/licenses/gpl-1.0.txt
[36]:http://dev.perl.org/licenses/
[37]:http://ebb.org/bkuhn/blog/2011/06/26/identica-weekly.html
[38]:http://linuxoutlaws.com/podcast/ogg/204
[39]:http://www.gnu.org/philosophy/why-not-lgpl.html
[40]:http://www.gnu.org/licenses/gpl.html#section14
[41]:http://creativecommons.org/
[42]:http://en.wikipedia.org/wiki/Lawrence_Lessig
[43]:http://blog.ninapaley.com/2011/07/04/rantifesto/
[44]:http://en.wikipedia.org/wiki/Creative_Commons#Other_criticism_of_the_non-commercial_license
[45]:http://ebb.org/bkuhn/blog/2010/06/23/open-source.html#footnote-amoral-word-choice
[46]:http://www.linkedin.com/pub/dir/Amanda/Brock
[47]:http://identi.ca/notice/74444380
[48]:http://www.archive.org/download/gov.uscourts.nysd.327540/gov.uscourts.nysd.327540.3.0.pdf
[49]:http://sec.gov/Archives/edgar/data/1375365/000119312509084731/filename1.htm
[50]:http://identi.ca/conversation/74175630#notice-76902928
[51]:http://live.gnome.org/CopyrightAssignment/Guidelines
[52]:http://opensource.com/law/11/7/trouble-harmony-part-1
[53]:http://blogs.gnome.org/bolsh/2011/07/06/harmony-agreements-reach-1-0/
[54]:http://people.gnome.org/~michael/blog/copyright-assignment.html
[55]:http://blogs.gnome.org/bolsh/2009/04/08/copyright-assignment-and-other-barriers-to-entry/
[56]:http://ebb.org/bkuhn/blog/2009/10/16/open-core-shareware.html
[57]:http://www.fsf.org/blogs/rms/assigning-copyright/
[58]:http://www.fsf.org/blogs/licensing/project-harmony
[59]:http://identi.ca/conversation/60847947
[60]:http://identi.ca/conversation/60848873
[61]:http://identi.ca/conversation/61240820
[62]:http://identi.ca/conversation/68596018
[63]:http://identi.ca/conversation/68858735
[64]:http://identi.ca/conversation/68886640
[65]:http://identi.ca/conversation/68887235
[66]:http://identi.ca/conversation/69308469
[67]:http://identi.ca/conversation/70389379
[68]:http://identi.ca/conversation/70648339
[69]:http://identi.ca/conversation/71854529
[70]:http://identi.ca/conversation/72024908
[71]:http://identi.ca/conversation/73129548
[72]:http://identi.ca/conversation/73225057
[73]:http://identi.ca/conversation/74175630
[74]:http://identi.ca/conversation/74979814
[75]:http://identi.ca/tag/harmony
[76]:http://identi.ca/tag/cla
[77]:http://www.linuxuser.co.uk/news/the-issue-of-bringing-harmony-to-copyright-assignment/
[78]:http://opensource.com/life/11/4/balancing-transparency-and-privacy
[79]:http://live.gnome.org/CopyrightAssignment
[80]:http://live.gnome.org/CopyrightAssignment/Guidelines
[81]:http://opensource.com/law/10/6/project-harmony-looks-improve-contribution-agreements-0
[82]:http://lists.harmonyagreements.org/mailman/listinfo
[83]:http://harmonyagreements.org/agreements.html
[84]:http://ref.fedorapeople.org/fontana-linuxcon.html
[85]:http://identi.ca/conversation/75670941#notice-78261971
[86]:http://creativecommons.org/licenses/by-sa/3.0/us/
[87]:http://creativecommons.org/licenses/by-sa/3.0/us/
[88]:http://ebb.org/bkuhn/
[89]:mailto:bkuhn@ebb.org
