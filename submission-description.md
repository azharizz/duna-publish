<p align="center">
  <img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/duna-banner.jpg" alt="DUNA: Duni the sand mascot, a glowing sand-art wall, the cymatics Light Box and the Sandbox table with two bare hands, in front of the lantern and aurora worlds" width="100%">
</p>

# DUNA

## Your room, made of sand.

**DUNA** turns your real room into a stage for **500+ sand art shows**. Press play and sand rains onto your floor, the table glows and dances to every note, and a story is drawn live across your wall. Catch what flies out with your bare hands. The one you keep opens your wall into another world.

<p align="center">
  <img src="https://img.shields.io/badge/ENTERTAINMENT%20TRACK-FFBA58?style=for-the-badge" alt="Entertainment track">
  <img src="https://img.shields.io/badge/NEW%20EXPERIENCE-1E140D?style=for-the-badge" alt="New Experience division">
  <img src="https://img.shields.io/badge/HANDS%20ONLY-FFF0DC?style=for-the-badge&labelColor=FFBA58" alt="Hands only">
  <img src="https://img.shields.io/badge/QUEST%203%20%C2%B7%203S-1E140D?style=for-the-badge&logo=meta&logoColor=white" alt="Meta Quest 3 and 3S">
  <a href="https://duna.quest"><img src="https://img.shields.io/badge/DUNA.QUEST-FFBA58?style=for-the-badge" alt="Official website: duna.quest"></a>
</p>

<p align="center"><img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/duna-film.gif" alt="DUNA in 20 seconds: the sand logo, the library, sand pouring into the room, the dancing board, the wall opening" width="88%"></p>

<p align="center"><img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/duna-stats.png" alt="500+ sand art shows, 7 hand gestures, 0 controllers, 1 real room" width="100%"></p>

## Inspiration

I love watching sand artists. A light box and two hands turn a pile of sand into a moving story, but you only ever see it on a screen, far away. I wanted the sand in **my** room, moving to the music, close enough to touch.

## What it does

<p align="center"><img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/duna-show-loop.gif" alt="One show: pick a show, sand pours in, the board dances, catch a Wonder, keep it as Glass, the wall opens" width="80%"></p>

<table>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/sand-pours.gif" alt="Sand pours into the real room"><br><sub><strong>Sand pours in.</strong> Your room fills, then a sand figure rises.</sub></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/cymatics.gif" alt="Cymatics on the Light Box"><br><sub><strong>The board dances.</strong> Live audio draws real Chladni patterns.</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/wall-drawing.gif" alt="Story drawn live on the wall"><br><sub><strong>Drawn live on your wall.</strong> Frame by frame, like a sand artist.</sub></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/glass-catch.gif" alt="Catching a Wonder as Glass"><br><sub><strong>Catch it, keep it.</strong> Close both hands: it becomes Glass.</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/wall-opens.gif" alt="The wall opens into a world"><br><sub><strong>Your Glass opens the wall</strong> into its world.</sub></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/point-to-fly.gif" alt="Point a finger to fly"><br><sub><strong>Point a finger to fly</strong> through the lanterns.</sub></td>
  </tr>
</table>

### Sandbox: make your own show

| Draw in 3D sand | Pour from your fist | Your own ending |
| --- | --- | --- |
| ![One finger leaves real grooves](https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/sandbox-draw.gif) | ![Close a hand to pour sand](https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/pour-sand.gif) | ![The aurora ending](https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/aurora-ending.gif) |

Draw with a finger, gather five fingertips to photograph something real and turn it into sand art, place figures on a timeline, record your voice, pick an ending, then play it back like any show.

## How we built it

<p align="center"><img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/duna-architecture.gif" alt="How DUNA works: room, hands, song and camera feed the conductor, sand engine, cymatics and Wonders, which become the sand floor, Light Box, wall art and worlds" width="100%"></p>

| Meta capability | How DUNA uses it |
| --- | --- |
| **MR Utility Kit** | Finds walls, floor, tables and couches. The art lands on a real wall and the sand floor fits your room. |
| **Passthrough** | You stay in your room. It dims during a show, like a cinema. |
| **Hand tracking** (XR Hands) | Seven gestures: touch, draw, pour, catch, point, gather and reach. Our own pose reader prevents accidental triggers. |
| **Passthrough Camera API** | The five-finger photo that becomes sand art. |
| **Spatial audio + mic** | Music around you; your voice recorded into your pieces. |

Unity 6, URP, OpenXR and Meta XR SDK v207. The sand is a GPU height field. A score file per song conducts the Wonders on the beat, and build-time tools generate and check the whole library.

## Challenges

Thousands of grains, a pushable sand surface and a full world at once on a standalone headset. Gestures that feel natural but never fire by accident. Rooms we have never seen.

## What's next

- New shows every week.
- Share your Sandbox shows.
- Watch together in shared mixed reality.
- More worlds and seasonal events.
- Launch on the Meta Horizon Store.

<p align="center">
  <img src="https://raw.githubusercontent.com/azharizz/duna-publish/main/assets/logo.gif" alt="The DUNA logo forming from sand" width="60%"><br>
  <strong>Official website: <a href="https://duna.quest">duna.quest</a></strong>
</p>
