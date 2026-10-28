# Commander Night — user guide

*Español: [guia-de-usuario.md](guia-de-usuario.md).*

Commander Night is a program for playing Commander games with 2 to 10
players: against bots, online with friends, with digital cards, with your
physical cards in front of a camera, or a mix of both. Inside the app,
“Help” summarises this guide.

## Installing

**Windows.** Run `Commander Night_<version>_x64-setup.exe`. It installs for
your user only, without asking for administrator rights. The installer is
not signed yet, so the first time Windows SmartScreen warns about an unknown
publisher: click “More info” and then “Run anyway”.

**Updates.** When it opens, the app checks for a new version. If there is
one, a notice offers “Update and restart”. Updates are signed and the app
rejects anything else.

**Uninstalling.** Close the app and uninstall it from “Settings → Apps”. Your
decks and replays stay in your data folder in case you install it again.

**Phone (Android).** Install Commander Night Camera. You only need it to use
your phone as the camera for your seat at the table.

## Your first game

1. On the start screen choose how many opponents you want, your deck (a
   random test deck or one of yours from the builder), the bots' level and
   the clock.
2. Press “Start game”.
3. The table highlights what you can play and pays the mana for you. Click a
   card to play it; targets are chosen on the table.
4. Shortcuts: Space passes priority, Ctrl+Z undoes and Esc cancels.

The phase bar lets you set stops on the steps where you want the game to
pause even when you have nothing to do.

## Levels and copilot

Bots play at four levels: Easy, Medium, Hard and Expert. Medium is the
default level.

- **Copilot.** At the table, “What would the bot do?” tells you the play the
  Expert would make in your place.
- **Training mode.** It counts how many of your decisions matched the Expert
  and tells you what it would have done in the last one.

## Decks

The builder imports decks as text (ManaBox, MTGA, Moxfield, Archidekt) or
CSV. It then checks whether the deck is legal in Commander (colour identity,
partners, companion, banned cards) and saves it on your computer. You can
also start a game with that deck from the builder.

## Playing online

“Play online” gives you two options:

- **Create a room.** Your computer is the server. Share the invitation as
  text or as a QR code.
- **Join a room** by pasting another player's invitation.

There are three game modes:

- **Digital:** the app handles all the cards and the rules.
- **Webcam:** everyone plays with their physical cards. The app keeps track
  of life, commander damage, tax and turns. This mode has no bots.
- **Hybrid:** digital and physical cards in the same game. Players with
  physical cards register what they play, with the camera or by name.

Rooms on your local network show up by themselves. To play over the
internet, tick “Open the port on the router (UPnP)” when you create the room.
If your router does not allow it, open the port by hand or use a dedicated
server. In “Friends” you can save people by their player key so you
recognise them.

## Your phone as a camera

1. With the phone and the computer on the same network, open “Play online →
   My devices → Pair a phone” on the desktop.
2. On the phone, open Commander Night Camera and scan the QR code.
3. When you take a seat in a room, the phone becomes your camera. Mark the
   four corners of your play area so the others see it straightened, as if
   from above.
4. The phone also keeps your score and tells you when it is your turn.

If the phone gets hot or runs low on battery, it lowers the video quality to
keep going. If another app takes the camera, it recovers it as soon as the
camera is free.

## Replays

Games that finish on your computer, against bots or as host, are saved
automatically. In “Replays” you can watch them step by step from any
player's seat.

## If something goes wrong

If the app crashes, it saves a report **only on your computer** (or your
phone) and tells you the next time you open it.

- **On the desktop**, “Crash reports” lists them, with “Copy” and “Delete
  all”.
- **On the phone**, the notice offers “Share the report”.

Nothing is sent by itself: if you want to help, send the report yourself.

## Privacy

In short: no accounts, no ads and no analytics; your things stay on your
computer. The details are in the [privacy policy](../privacidad.md#english).

## Licenses and notices

Commander Night is licensed under Apache-2.0. Third-party components and
their licenses are under “Help → Licenses” on the desktop and “Privacy and
licenses” on the phone (summary in [licencias-terceros.md](../licencias-terceros.md)).

Commander Night is unofficial Fan Content permitted under the Fan Content
Policy. Not approved/endorsed by Wizards. Portions of the materials used are
property of Wizards of the Coast. ©Wizards of the Coast LLC. Card data and
images come from Scryfall; Commander Night is not affiliated with Scryfall.
