# Commander Night — guía de usuario

*English: [user-guide.md](user-guide.md).*

Commander Night es un programa para jugar partidas de Commander de 2 a 10
jugadores: contra bots, en red con amigos, con cartas digitales, con tus
cartas físicas ante una cámara o mezclando las dos cosas. Dentro de la app,
«Ayuda» resume esta guía.

## Instalar

**Windows.** Ejecuta `Commander Night_<versión>_x64-setup.exe`. Se instala
solo para tu usuario, sin pedir administrador. El instalador aún no está
firmado, así que la primera vez Windows SmartScreen avisa de un editor
desconocido: pulsa «Más información» y luego «Ejecutar de todas formas».

**Actualizaciones.** Al abrirse, la app mira si hay una versión nueva. Si la
hay, sale un aviso con «Actualizar y reiniciar»; las versiones van firmadas
y la app rechaza cualquier otra.

**Desinstalar.** Cierra la app y desinstálala desde «Configuración →
Aplicaciones». Tus mazos y replays se quedan en tu carpeta de datos por si
vuelves a instalarla.

**Móvil (Android).** Instala Commander Night Cámara. Solo hace falta si
quieres usar el móvil como cámara de tu sitio en la mesa.

## Tu primera partida

1. En el inicio elige cuántos rivales quieres, tu mazo (uno de prueba al
   azar o uno tuyo del constructor), el nivel de los bots y el reloj.
2. Pulsa «Empezar partida».
3. La mesa resalta lo que puedes jugar y paga el maná por ti. Pulsa una
   carta para jugarla; los objetivos se eligen sobre la mesa.
4. Atajos: Espacio pasa la prioridad, Ctrl+Z deshace y Esc cancela.

La barra de fases deja poner paradas en los pasos en los que quieres que la
partida se detenga aunque no tengas nada que hacer.

## Niveles y copiloto

Los bots juegan en cuatro niveles: Fácil, Medio, Difícil y Experto. Medio es
el nivel por defecto.

- **Copiloto.** En la mesa, «¿Qué haría el bot?» te dice la jugada que haría
  el Experto en tu lugar.
- **Modo entrenar.** Cuenta en cuántas decisiones has hecho lo mismo que el
  Experto y te dice qué habría hecho él en la última.

## Mazos

El constructor importa mazos en texto (ManaBox, MTGA, Moxfield, Archidekt)
o en CSV. Después comprueba si el mazo es legal en Commander (identidad de
color, compañeros, companion, cartas prohibidas) y lo guarda en tu equipo.
Desde el constructor también puedes empezar una partida con ese mazo.

## Jugar en red

En «Jugar en red» tienes dos caminos:

- **Crear una sala.** Tu equipo hace de servidor. Comparte la invitación
  como texto o como QR.
- **Unirte a una sala** pegando la invitación de otro jugador.

Hay tres modos de juego:

- **Digital:** la app lleva todas las cartas y las reglas.
- **Webcam:** cada uno juega con sus cartas físicas. La app lleva vidas,
  daño de comandante, impuesto y turnos. En este modo no hay bots.
- **Híbrido:** digitales y físicas en la misma partida. Quien juega con
  cartas físicas registra lo que juega, con la cámara o por nombre.

Las salas de tu red local aparecen solas. Para jugar por internet, al crear
la sala marca «Abrir el puerto en el router (UPnP)». Si tu router no lo
permite, abre el puerto a mano o usa un servidor dedicado. En «Amigos»
puedes guardar a la gente por su clave de jugador para reconocerla.

## Tu móvil como cámara

1. Con el móvil y el ordenador en la misma red, abre en el escritorio
   «Jugar en red → Mis dispositivos → Emparejar un móvil».
2. En el móvil, abre Commander Night Cámara y escanea el QR.
3. Cuando te sientes en una sala, el móvil será tu cámara. Marca las cuatro
   esquinas de tu zona de juego para que los demás la vean enderezada, como
   desde arriba.
4. El móvil también lleva tu marcador y te avisa cuando te toca.

Si el móvil se calienta o le queda poca batería, baja la calidad del vídeo
para aguantar. Si otra app le quita la cámara, la recupera sola en cuanto
quede libre.

## Replays

Las partidas que terminan en tu equipo, contra bots o como anfitrión, se
guardan solas. En «Replays» se ven paso a paso desde el sitio de cualquier
jugador.

## Si algo falla

Si la app se cae, guarda un informe **solo en tu equipo** (o en tu móvil) y
te avisa la próxima vez que la abras.

- **En el escritorio**, «Informes de fallos» los enseña y tiene «Copiar» y
  «Borrar todos».
- **En el móvil**, el aviso ofrece «Compartir el informe».

Nada se envía solo: si quieres ayudar, manda tú el informe.

## Privacidad

Resumen: sin cuentas, sin anuncios y sin analítica; lo tuyo se queda en tu
equipo. El detalle está en la [política de privacidad](../privacidad.md).

## Licencias y avisos

Commander Night tiene licencia Apache-2.0. Los componentes de terceros y sus
licencias están en «Ayuda → Licencias» en el escritorio y en «Privacidad y
licencias» en el móvil (resumen en [licencias-terceros.md](../licencias-terceros.md)).

Commander Night es contenido de fans no oficial permitido por la Fan Content
Policy. No está aprobado ni respaldado por Wizards. Partes de los materiales
usados son propiedad de Wizards of the Coast. ©Wizards of the Coast LLC. Los
datos y las imágenes de las cartas vienen de Scryfall; Commander Night no
está afiliado a Scryfall.
