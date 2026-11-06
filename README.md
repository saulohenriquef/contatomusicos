# Contatos dos Músicos

Lista de contatos de músicos (qualquer instrumento) para enviar a quem contrata. É uma página única, sem servidor, publicada pelo GitHub Pages.

**Site:** https://saulohenriquef.github.io/contatomusicos/

## O que tem aqui

| Arquivo | Para quê |
|---|---|
| `index.html` | A página (versão v11). O histórico de mudanças (changelog) está no comentário no fim do arquivo. |
| `Lista_Contatos_Musicos_contatos.json` | Os contatos: é o "banco de dados" que a página lê. |
| `Lista_Contatos_Musicos_cidades.json` | As cidades e suas coordenadas (para mostrar primeiro quem está mais perto). |
| `fotos/` | As fotos dos contatos (JPEG 256 × 256). O nome do arquivo vai no campo `foto` do contato. |

A página lê os dois arquivos `.json` e as fotos por caminho relativo. Por isso os nomes dos arquivos e da pasta `fotos` não devem mudar.

## Como atualizar a lista

- Pelo **Painel de Contatos**, que é um arquivo guardado no seu computador (não fica neste repositório): cadastra, edita e publica aqui com um clique.
- Ou editando os dois `.json` direto no GitHub (ícone de lápis, depois *Commit changes*).

O site mostra a mudança de 1 a 3 minutos depois. Para ver na hora, use Ctrl+F5.

## Campos de um contato

`nome`, `foto`, `cidades` (ex.: `"Passos/MG"`), `instrumentos`, `selos` (ex.: `"IFC"`), `instagram`, `youtube`, `email`, `whatsapp`, `telefones`, `links` e `observacoes`. Só aparece no cartão o que o contato tem. Os botões de instrumento da página saem sozinhos do campo `instrumentos`.

## Observações

- A página pede aos buscadores que não a listem (`noindex, nofollow`).
- A localização de quem abre a página, se for liberada, fica só no aparelho dela.
- O repositório é público (necessário para o GitHub Pages gratuito): os contatos ficam visíveis para quem abrir os arquivos `.json` aqui.

## Versão e changelog

- Página: **v11** (2026-11-05). Changelog completo no fim do `index.html`.
- README v1 — 2026-11-05: criado ao mudar a lista para o repositório `contatomusicos`.
