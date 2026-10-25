# Desenvolvimento

Este repositório é a fonte principal do Pac-Man. O perfil do GitHub exibe diretamente `assets/pacman.svg` deste projeto, sem manter outra cópia da simulação ou da animação.

A lógica está em `scripts/pacman_game.py`, a geração da animação em `scripts/generate_pacman.py` e os testes em `scripts/test_pacman_game.py`.

Com Python instalado, execute na raiz:

```bash
python -m unittest discover -s scripts -p 'test_*.py'
python scripts/generate_pacman.py
```

O workflow `Build Pac-Man` executa essas etapas quando os scripts são alterados. O GitHub Pages usa a mesma animação em `index.html`.
