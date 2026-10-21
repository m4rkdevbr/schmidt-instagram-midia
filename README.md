# schmidt-instagram-midia

Controle das publicações do Instagram [@aschmidtsolucoes](https://instagram.com/aschmidtsolucoes).

Como funciona: as imagens de cada post sobem numa branch temporária `post/<nome>`, o conector publica usando os links
públicos dessa branch e, depois que a publicação é confirmada, a branch é apagada. Na `main` fica só o registro em
[PUBLICACOES.md](PUBLICACOES.md).
