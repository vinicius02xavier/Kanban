# Kanban

Projeto Kanban simples com HTML, CSS e JavaScript.

Este projeto implementa um quadro Kanban básico com colunas e cards que podem ser movidos entre as colunas usando drag and drop.

## Funcionalidades

- Layout responsivo em colunas
- Cards com prioridade e informações básicas
- Arrastar e soltar cards entre colunas
- Estilização moderna com efeitos de hover e sombras

## Estrutura do projeto

- `src/index.html` - marcação HTML do quadro Kanban
- `src/css/styles.css` - estilos do projeto
- `src/javascript/script.js` - lógica de drag and drop
- `src/images/` - imagens usadas nos cards

## Como abrir

### Opção 1: Abrir diretamente no navegador

Abra o arquivo `src/index.html` no navegador.

### Opção 2: Usar servidor local (recomendado)

No terminal, rode a partir da pasta do projeto:

```bash
cd '/home/vigaxa/Área de trabalho/kanban'
python3 -m http.server 8000
```

Depois abra:

```
http://localhost:8000/src/index.html
```

## Como contribuir

1. Fork neste repositório
2. Crie uma branch nova: `git checkout -b minha-melhoria`
3. Faça suas alterações
4. Commit: `git commit -m "Minha melhoria no Kanban"`
5. Push para a branch e abra um pull request

## Notas

- Este é um projeto estático, sem back-end.
- O foco é a experiência visual e a movimentação dos cards.