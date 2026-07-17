# GMUD-2026-0020 · Atualização e Troca de IPs · BMC

Painel de acompanhamento da GMUD de migração de IPs externos do cliente **BMC** (Rede Externa / PNSCL).

## Sobre

- **Cliente:** BMC
- **GMUD:** 2026-0020
- **Escopo:** Troca de IPs externos (VPN SSL, DNS e regras de redirecionamento/NAT)
  - `200.218.225.74 → 45.225.26.72`
  - `200.218.225.21 → 45.225.26.122`

## Estrutura

- `index.html` — Painel de acompanhamento da GMUD, com status por tarefa (Não iniciado / Concluído) e mapeamento de-para de cada regra de porta.

## Como usar

Abra o `index.html` no navegador (ou acesse via GitHub Pages). O status de cada tarefa e regra é clicável e o progresso geral é calculado automaticamente.
