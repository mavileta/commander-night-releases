# Política de privacidad de Commander Night

*English below: [Privacy policy](#english).*

Última revisión: 28 de octubre de 2026. Se aplica a la app de escritorio
Commander Night y a la app de Android Commander Night Cámara.

## Resumen

Commander Night no tiene cuentas, ni anuncios, ni analítica, y no envía
datos a sus desarrolladores. Lo que creas o guardas se queda en tu equipo o
en tu móvil.

## Qué se guarda y dónde

**En tu ordenador**, en la carpeta de datos de la app, se guardan:

- tus mazos y tus replays;
- tus amigos (su alias y su clave de jugador);
- tu clave de jugador, que te identifica en las partidas en red;
- los móviles que has emparejado;
- los informes de fallos.

También hay una caché de las imágenes de cartas que se han bajado.

**En tu móvil** se guardan:

- el emparejamiento con tu escritorio y la identidad del móvil, en el
  almacén seguro del sistema (Keystore);
- los informes de fallos de la app.

Puedes borrarlo todo desinstalando las apps y su carpeta de datos. Los
informes de fallos también se borran desde la propia app.

## Cuándo se conecta y con quién

**Imágenes de cartas.** Si activas «Imágenes de Scryfall», la app las baja
de Scryfall. Scryfall ve tu dirección de red, como en cualquier descarga.

**Actualizaciones.** Al abrirse, la app de escritorio pregunta al servidor
de descargas si hay una versión nueva. Ese servidor ve tu dirección de red.

**Partidas en red.** Tu equipo se conecta directamente con los de tu sala, o
con el servidor dedicado que elijáis. Viajan:

- tu alias y tu clave pública de jugador;
- las jugadas de la partida;
- en los modos con cámara, el vídeo y el audio que compartes con esa
  partida.

Todo va cifrado y solo llega a los jugadores de esa partida; no se graba en
ningún servidor nuestro. Al crear una sala, la app la anuncia en tu red
local. Si lo marcas, también abre un puerto en tu router (UPnP).

**Móvil.** La app de cámara busca tu escritorio en tu red local. El vídeo de
la cámara va cifrado y solo a la partida de tu jugador, mientras estás
sentado en una sala. La app de Android no usa el micrófono.

## Informes de fallos

Si una app se cae, guarda un informe con la versión, el sistema y dónde
falló. Tu carpeta de usuario sale como `~`. El informe **no se envía**: la
app te avisa y tú decides si lo copias o lo compartes, y con quién.

## Menores

Las apps no piden datos personales ni tienen cuentas, así que no recogen
datos de menores.

## Cambios

Si esta política cambia, la nueva versión se publicará aquí con su fecha.

## Contacto

Para preguntas sobre privacidad: abre una incidencia en la pestaña *Issues*
de [mavileta/commander-night-releases](https://github.com/mavileta/commander-night-releases/issues).

---

<a id="english"></a>

# Commander Night privacy policy

Last revised: 28 October 2026. It applies to the Commander Night desktop app
and to the Commander Night Camera Android app.

## Summary

Commander Night has no accounts, no ads and no analytics, and it does not
send data to its developers. What you create or save stays on your computer
or your phone.

## What is stored and where

**On your computer**, in the app's data folder:

- your decks and your replays;
- your friends (their alias and player key);
- your player key, which identifies you in online games;
- the phones you have paired;
- crash reports.

There is also a cache of the card images that have been downloaded.

**On your phone**:

- the pairing with your desktop and the phone's identity, in the system's
  secure storage (Keystore);
- the app's crash reports.

You can delete all of it by uninstalling the apps and their data folder.
Crash reports can also be deleted from inside the app.

## When it goes online and with whom

**Card images.** If you turn on “Scryfall images”, the app downloads them
from Scryfall. Scryfall sees your network address, as with any download.

**Updates.** When it opens, the desktop app asks the download server whether
there is a new version. That server sees your network address.

**Online games.** Your computer connects directly to the others in your
room, or to the dedicated server you choose. What travels:

- your alias and your public player key;
- the game's moves;
- in the camera modes, the video and audio you share with that game.

All of it is encrypted and only reaches the players in that game; nothing is
recorded on any server of ours. When you create a room, the app announces it
on your local network. If you tick the option, it also opens a port on your
router (UPnP).

**Phone.** The camera app looks for your desktop on your local network. The
camera video is encrypted and only goes to your player's game, while you are
seated in a room. The Android app does not use the microphone.

## Crash reports

If an app crashes, it saves a report with the version, the system and where
it failed. Your user folder shows up as `~`. The report is **not sent**: the
app tells you about it and you decide whether to copy or share it, and with
whom.

## Children

The apps do not ask for personal data and have no accounts, so they do not
collect data from children.

## Changes

If this policy changes, the new version will be published here with its
date.

## Contact

For privacy questions, open an issue in the *Issues* tab of
[mavileta/commander-night-releases](https://github.com/mavileta/commander-night-releases/issues).
