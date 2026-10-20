# Custom character

The game currently uses the original Chrome T-Rex artwork. To replace it,
add your transparent PNG as:

```text
assets/custom-character.png
```

The renderer scales the image to the same player bounds as the T-Rex, so the
jump, duck, obstacle collision, scoring, speed, day/night cycle, and restart
behavior remain unchanged. A transparent image works best; the source image
can be any size.
