# CINDERVALE

A co-op browser RPG. GBA-style pixel art, all generated in code — no downloaded assets. One HTML file.

Up to 10 players share one room. Light three embers to wake the Hollow King, then fight him together.

## Controls
| | Move | Strike | Dash | Menus |
|---|---|---|---|---|
| **Keyboard** | WASD / arrows | J, Space, or click | K / Shift | Enter select · Esc back |
| **Phone** | on-screen stick (slide, diagonals work) | **A** | **B** | A select · B back · tap works too |
| **Gamepad** | left stick / D-pad | A / X | B / RB | A select · B back |

On a phone the game fills the top of the screen in portrait with the controls underneath; in landscape the controls overlay the sides. Add it to your home screen for full-screen play. Plug in a controller and the touch controls hide themselves.

## Play together
HOST GAME → tap the room code to share the link (or read out the 6-character code) → A / Enter to start. Multiplayer uses WebRTC via PeerJS (needs HTTPS, which GitHub Pages provides). PeerJS is vendored in the repo.

MIT licensed. Built from a DeepSeek-generated design; packaged and published with Claude.
