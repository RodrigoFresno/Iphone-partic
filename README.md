# Particle Flow

Experiência web de partículas luminosas interativas, inspirada na estética fluida do Quick Start do iPhone (não é uma cópia dos recursos internos da Apple).

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie **todos os arquivos desta pasta** para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e `/ (root)`.
5. Salve e aguarde o endereço publicado.

## Instalar no celular

Abra o endereço HTTPS no Chrome (Android) ou Safari (iPhone) e use o menu do navegador → **Adicionar à tela inicial / Instalar app**. A disponibilidade do comando varia conforme navegador e dispositivo. O app usa manifest e service worker para oferecer modo standalone e cache offline depois da primeira visita.

## Controles

- Arraste o dedo para perturbar o campo de partículas.
- Escolha uma paleta ou uma cor personalizada.
- Ajuste quantidade, velocidade, brilho e força.
- Oculte os controles e use tela cheia.

## Implementação

HTML/CSS/JavaScript sem dependências externas. O render é feito em Canvas 2D; o campo combina movimento orgânico, interação por Pointer Events, brilho aditivo e rastros com persistência. Para referência técnica de simulações de fluido GPU/WebGL2, veja:
- https://github.com/PSCactux/fluid-particles
- https://github.com/pchadik/fluidtouch
- https://github.com/emooney/fluid-sim

## Observação

A animação é uma interpretação visual original: a implementação proprietária do Quick Start da Apple não é pública, então não é possível garantir reprodução pixel a pixel. Esta base prioriza resposta ao toque, movimento fluido, brilho e personalização, mantendo compatibilidade ampla em navegadores móveis.
