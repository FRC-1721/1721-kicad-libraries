# 1721's Custom KiCAD libraries

## To use!

```
git submodule add https://github.com/FRC-1721/1721-kicad-libraries
```

Just like the espressif library, if you want 3D models, you'll need to
open `Preferences` and `Configure Paths` then add the following enviorment variable:

```
Name: 1721_3DMODELS
Path: <Path to folder>
```

And if you use kibot, add this to your `pre_flight`

```
preflight:
  ...
  set_text_variables:
    - name: "1721_3DMODELS" # 3D models for the FRC-1721 Library
      command: "echo 'Hardware/Board/Libraries/1721-kicad-libraries/3d'"
```

# Projects using this lib:
