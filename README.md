# Sudoku Solver

___A simple Sudoku Sovler___

Sudoku Solver is a GTK4+libadwaita application that solves sudokus using the Wave Function Collapse Algorithm. 

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing

```
flatpak install flathub io.gitlab.cyberphantom52.sudoku_solver
flatpak run io.gitlab.cyberphantom52.sudoku_solver
```

## Building

```
git clone git@github.com:flathub/io.gitlab.cyberphantom52.sudoku_solver.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.gitlab.cyberphantom52.sudoku_solver.json
```

---

**Technologies**: GNOME, GTK4, Libadwaita, Rust
