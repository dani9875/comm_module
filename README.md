# Jules Audio codec hat

## Cloning the Repository

To get started, clone the repository and initialize submodules:

```sh
git clone --recurse-submodules <repository-url>
cd <repository-name>
```

If the submodules are not initialized, run:
```sh
git submodule update --init --recursive
```

## Adding the Component Library to KiCad

### Symbol Library

1. Open KiCad and navigate to **Preferences > Manage Symbol Libraries**.
2. Under the **Global Libraries** tab, click **Add existing library**.
3. Locate and select the symbol library file:
   ```
   root/kicad_components/pepy_sym_lib.kicad_sym
   ```
4. Click **OK** to confirm.

### Footprint Library

1. Open KiCad and navigate to **Preferences > Manage Footprint Libraries**.
2. Under the **Global Libraries** tab, click **Add existing library**.
3. Locate and select the footprint library folder:
   ```
   root/kicad_components/pepy_sim_lib.pretty
   ```
4. Click **OK** to confirm.

Your component library is now added to KiCad and ready for use.

