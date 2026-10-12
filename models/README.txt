3D people for Kundan's Gym Tracker
==================================
Upload this whole "models" folder into your website repository, next to index.html:

  your-repo/
    index.html
    models/
      body_m.glb  shorts_m.glb  tank_m.glb  shoes_m.glb  hair_m.glb    (man: sando + shorts)
      body_f.glb  shorts_f.glb  bra_f.glb   shoes_f.glb  hair_f.glb    (woman: sports bra + shorts)

The app loads them only when someone opens a 3D view (about 3.5 MB per person, then cached).
If the folder is missing, the app falls back to the simple figure, so nothing breaks.

Licence: CC0 1.0 (public domain). Bodies, hair and clothing come from the MakeHuman CC0
system assets as exported by github.com/kblood/CharacterCreator (output/ files, CC0-1.0),
then baked into fixed male/female shapes for this app. No attribution required.
