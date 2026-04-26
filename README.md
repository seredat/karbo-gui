# Karbo-GUI
Alt. wallet for Karbo

⚠️ PROJECT MOVED: This repository is no longer maintained here. Please find the latest version and report issues at: https://github.com/Karbovanets/Karbo-GUI




**1. Clone wallet sources**

```
git clone https://github.com/seredat/karbo-gui.git
```

**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../karbowanec cryptonote
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/seredat/karbowanec.git cryptonote
```

**3. Build**

```
mkdir build && cd build && cmake .. && make
```

