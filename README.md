# AutoSim Dashboard

AutoSim est une application graphique écrite en C avec GTK+3 permettant de simuler l'état d'un véhicule à travers une interface utilisateur moderne et intuitive.

---

## Objectif

Simuler l'état d'un tableau de bord automobile :
- Vitesse
- Température
- Niveau de batterie
- Kilométrage
- Allumage/moteur
- Boutons de contrôle interactifs

---

## Technologies

- Langage :C 
- Interface graphique : GTK+3
- Style visuel : GTK CSS
- IDE recommandé : Visual Studio Code
- OS : Windows (compatible MSYS2/Mingw-w64)

---


## Compilation

Assurez-vous d’avoir installé GTK+3 avec `pkg-config`.

```bash
gcc main_gui.c voiture.c -o autosim_gui.exe `pkg-config --cflags --libs gtk+-3.0`

