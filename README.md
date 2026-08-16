# The HUNT Begins — shareware E1A1 tribute

Self-contained three.js clone of Rise of the Triad shareware E1A1.
Original / synthesized art and sound only. No ripped WAD, sprites, or music.

Marc's `ROTT-Bounce.mp3` plays on the title screen (loop, click-to-start if the browser blocks autoplay, M to mute). It is not in-level BGM.

## Open it

From this folder:

    python3 -m http.server 8765

then http://localhost:8765/

Or open `index.html` directly. A local server is safer for the audio file.

## Controls

- Title has CLICK TO PLAY and CONTROLS. One click on play starts the game and pointer lock.
- WASD and arrow keys both move. Always. Shift run, Space jump, mouse look. These work even if lock is refused.
- Left click, right click, Ctrl, and Enter all fire. Fire works without pointer lock. The click that grabs lock also shoots.
- If lock drops, the game stays live and shows CLICK TO LOOK. Esc opens Controls. BACK click grabs lock again. Esc-close does not eat the next lock click.
- R reload, 1-5 weapons, E use / pushwall
- M mutes the title track. There is no MUTE button. Music on/off is also on the Controls screen.
- CONTROLS on the title, or ESC in-game, opens a VGA Controls screen: look slider, mute, key legend, click-to-rebind. ESC or BACK returns. Settings persist in localStorage. Closing does not leave a held key or steal focus.

## Level flow (shareware E1A1 shape)

1. Spawn on courtyard dirt, looking east down the yard. No pad underfoot. A bronze bounce pad sits three steps ahead on the dirt. Two guards stand past the fountain. A monk meal is beside them. Door is in the south wall. They do not shoot you while you stand on S. Ctrl and Enter fire.
2. Main door in the south wall into the hall, then the hub
3. Bounce pads later, up to the east catwalk for the gold key
4. Gold door north into the jagged / pillar wing
5. Drop into the sunken hall for the silver key
6. Silver door to the exit wing — green EXIT
7. Secret: behind the tree, touchplate / pushwall, timed door opens 3:00–5:00, elevator, secret exit

Bronze bounce pads launch you and keep run momentum. Several of them sit on the gold-key and secret routes.

## Weapons

Dual pistols at start. MP40, bazooka, heat-seekers, and drunk missiles sit in the courtyard past the first guard.
Headshots count. Gibs and wall blood. Guns are compressed noise cracks and low thumps, not oscillator spit.
