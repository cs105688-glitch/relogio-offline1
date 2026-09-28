# Relógio

Aplicativo de relógio completo, leve e 100% offline.

**Relógio · Alarme · Cronômetro · Temporizador**

![Licença](https://img.shields.io/badge/licença-MIT-blue.svg)
![Offline](https://img.shields.io/badge/offline-100%25-success.svg)
![Sem anúncios](https://img.shields.io/badge/anúncios-nenhum-success.svg)
![Sem rastreadores](https://img.shields.io/badge/rastreadores-nenhum-success.svg)

## Características

- **Relógio** digital + analógico com data em português
- **Alarme** com múltiplos alarmes, rótulo, ligar/desligar e soneca de 5 minutos
- **Cronômetro** com precisão de centésimos e registro de voltas
- **Temporizador** com presets rápidos e anel de progresso
- Tema **preto puro** (AMOLED) + modo claro
- Interface moderna com ícones SVG
- Dados salvos localmente (localStorage)
- Som gerado no próprio dispositivo (Web Audio API)
- Vibração quando disponível

## Princípios

| Item                    | Status     |
|-------------------------|------------|
| Conexão com internet    | Nenhuma    |
| Anúncios                | Nenhum     |
| Rastreadores            | Nenhum     |
| Código aberto           | Sim (MIT)  |
| Dependências externas   | Nenhuma    |

O arquivo HTML é **autocontido**. Não há CDN, fontes externas, analytics nem qualquer chamada de rede.

## Como usar

### No navegador
Abra o arquivo `relogio-2.html` em qualquer navegador moderno (Chrome, Firefox, Safari, Edge).

### Como PWA / atalho
No celular, abra o arquivo no navegador e use a opção **“Adicionar à tela inicial”**.

### Gerar APK (Android)
1. Use um construtor de HTML → APK (ex.: HTML to APK, WebIntoApp, AppGeyser, Website 2 APK Builder)
2. Envie o arquivo `relogio-2.html`
3. Configure:
   - Nome: **Relógio**
   - Orientação: Retrato
   - Tema da barra de status: Preto
4. Gere e instale o APK

## Estrutura do projeto
