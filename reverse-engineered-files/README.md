# One Night At Bills — Recovered Project Data

Extracted from One_Night_At_Bills_.exe (Clickteam Fusion 2.5+, build 292).
Original project file was: C:\Users\Yousof\Desktop\FNAF Game\One Night At Bills' (many changes).mfa

## Contents
- images/            All 62 images as PNG, named by internal handle. index.json has size/hotspot/action-point per image.
- images/by_object/  Same images, grouped into folders per game object (e.g. 9_Office, 29_jumpscare, 22_cameras).
- sounds/            All 10 sounds with their original names (mp3/wav).
- objects.json       All 37 objects: name, type, and which image handles each uses (animation frame lists included).
- meta.json          App info + all 5 frames (Menu, nightOneLoading, nightOne, 6AM, deathscreen) with every
                     object instance's exact X/Y position and layer.
- events/            Raw decrypted event-sheet data per frame (frameN_events.bin) + instance data +
                     strings_found.txt (readable text pulled from the event sheets: animation names,
                     camera names, sound triggers, expressions like billAI, cameraSwitch, etc).

## Notes
- Fonts: game uses TTFs embedded in the exe (not extracted here — ask if you want them).
- The Perspective.mfx extension object was used on the nightOne frame (layer 1) for the camera-pan effect.
- Event sheets are recovered as raw data; the logic structure (conditions/actions) is intact but needs
  either Clickteam-side reconstruction or a rebuild in another engine.
