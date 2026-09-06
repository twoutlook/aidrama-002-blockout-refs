# Blockout reference clips

Untextured Blender previz for a 20-second rooftop-chase short. Two grey
blockout figures, four camera setups, 24fps.

These files exist for one reason: BytePlus ModelArk's video generation API
accepts a `reference_video` only as a public web URL — a `data:` URI is
rejected with `reference_video must be provided as a web url`. So the clips
are served from here and referenced by URL.

| file | frames | length |
|---|---|---|
| `blockout_20s.mp4` | 1–480 | 20.000s |
| `shot_01.mp4` | 1–120 | 5.000s |
| `shot_02.mp4` | 121–240 | 5.000s |
| `shot_03.mp4` | 241–360 | 5.000s |
| `shot_04.mp4` | 361–480 | 5.000s |

960×540, h264. Motion and staging only — the flat grey is deliberate, all
material and lighting comes from the text prompt downstream.

No people, likenesses, or identifying content: every figure is untextured
primitive geometry.
