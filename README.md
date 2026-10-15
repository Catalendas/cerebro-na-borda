# O Cérebro na Borda

Filme interativo em 3D sobre três famílias de microcontroladores — **ESP32**, **STM32** e **NXP i.MX RT** — e o que elas fazem com **Edge AI**.

**Ver online:** https://catalendas.github.io/cerebro-na-borda/

## O que tem

- Placas ESP32 DevKitC, STM32 "Blue Pill" e i.MX RT1170 modeladas em código com [Three.js](https://threejs.org/) — arraste para girar, passe o mouse nas peças para ver o que são.
- Modo **"Assistir o filme"**: a câmera percorre os 8 atos sozinha em cerca de 2 minutos, com barra de capítulos e timecode. Barra de espaço pausa.
- Rede neural em 3D mostrando inferência na borda, o pipeline do modelo ao chip (treinar → quantizar int8 → converter → rodar no MCU) e casos reais.

## Rodar localmente

É um único arquivo estático. Abra `index.html` no navegador ou sirva a pasta:

```bash
npx serve .
```

Os dados técnicos são valores públicos de cada família; confira o datasheet antes de usar em projeto.
