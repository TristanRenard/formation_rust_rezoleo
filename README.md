# Formation Introductive à Rust 🦀

#### Formation pour le club d'informatique de l'ECLille: Rézoléo

## Plan

1. Motivation
2. Le problème du C
3. Ownership & RAII
4. Borrowing & Borrow Checker
5. Syntaxe & Forces Expressives
6. Écosystème

## Comment compiler ?

> Dépendances : minted (pip install latexminted), beamer

- Installer latex full scheme
- Installer `latexminted` (nécessaire pour minted v3+) : `pip install latexminted`
- Puis executer:

```bash
  lualatex --shell-escape formation_rust.tex
```

### macOS

```bash
brew install --cask mactex
pip3 install latexminted
```

> Ouvrir un nouveau terminal après l'installation de MacTeX pour que le PATH soit à jour (`lualatex`, `latexminted`). Le post install de MacTeX ne met pas à jour le PATH automatiquement pour le terminal courant.

### Linux

```bash
sudo apt install texlive-full
pip install latexminted
```

### Windows

- Installer [MiKTeX](https://miktex.org/download) ou [TeX Live](https://www.tug.org/texlive/) (full scheme)
- Installer Python puis `pip install latexminted`
- Compiler depuis un terminal (PowerShell/cmd) avec la même commande `lualatex --shell-escape formation_rust.tex`
