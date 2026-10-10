# ⚡ Painel de Ligações — Simulador de Instalação Elétrica Online

**Acesse:** https://asguth.github.io/simulador-instalacao-eletrica/

Simulador de instalação elétrica residencial que roda direto no navegador, grátis e sem cadastro.
Monte o quadro, puxe os fios entre os componentes e energize o circuito para testar.

## O que dá para fazer

- **Quadro e proteção:** entrada de energia/medidor, disjuntores 1P/2P/3P, DR 30 mA, DPS, barramentos de neutro e terra
- **Conectores Wago:** 221, 222 e 2273 de 2 a 8 vias
- **Interruptores:** simples (1 a 4 teclas), paralelo (three-way), intermediário (four-way), pulsador, dimmer e **interruptor inteligente Wi-Fi**
- **Cargas:** lâmpadas, plafon, spot, fita LED, ventilador de teto, campainha e tomadas 10/20 A
- **Simulação:** corrente fluindo nos fios, lâmpadas acendendo, disjuntor desarmando em curto-circuito, osciloscópio, potência e consumo
- **Exportar:** projeto `.json`, imagem `.png` e `.pdf` com lista de materiais
- Cores de fio conforme a NBR 5410, modo claro/escuro, desfazer/refazer e atalhos de teclado

## Como publicar uma nova versão

O site é publicado no GitHub Pages **automaticamente a cada release**:

1. Crie uma release com uma tag no formato `vX.Y.Z` (ex.: `v1.1.0`) em *Releases → Draft a new release*
2. O workflow [`deploy.yml`](.github/workflows/deploy.yml) coloca a versão da tag no rodapé do site e publica

Pela linha de comando:

```bash
gh release create v1.1.0 --generate-notes
```

## Rodar localmente

É um único arquivo HTML: basta abrir o `index.html` no navegador.

## Licença

[MIT](LICENSE) © 2026 Alberto Guth
