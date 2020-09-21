# Fox.Build 3d Printer Configurations

This repository uses submodules to link in the upstream Marlin repositories. The `fox.build` directory contains individual printer configurations. To update, copy the upstream firmware into the printers directory then re-checkout the directory.

```
cd fox.build/mks2
cp -R ../../Marlin/* .
git checkout -- fox.build/mks2
```

From there building proceeds as usual.
