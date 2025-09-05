# Neumorphic UI Demo

Arquivos:
- `index.html`: Página de demonstração
- `styles.css`: Tema neumórfico (variáveis + utilitários)

Como usar:
1. Abra `index.html` no navegador.
2. Copie `styles.css` para seu projeto ou importe o arquivo.

Diretrizes aplicadas:
- Fundo claro monocromático `#e0e0e0` para toda a interface
- Elementos sem bordas duras; aparência esculpida da mesma superfície
- Sombra dupla sutil (clara e escura) para relevo/entalhe
- Profundidade mínima; efeito pressionado suave em interação

Classes principais:
- `.card`: container com relevo suave (extrudado)
- `.btn`: botão padrão
- `.btn-raised`: variação um pouco mais elevada
- `.btn-pressed` ou `:active`/`.is-pressed`: efeito pressionado (entalhado)
- `.input`: campo de entrada entalhado
- `.switch` / `.slider`: toggle neumórfico

Customização via variáveis CSS (em `:root`):
- `--surface`, `--text`, `--muted`
- `--radius`, `--shadow-light`, `--shadow-dark`, `--depth-1`, `--depth-2`

Acessibilidade:
- Focus visível em botões; suporte a teclado (Barra de espaço/Enter simulam pressionar)