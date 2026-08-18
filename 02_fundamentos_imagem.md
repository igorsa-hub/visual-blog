# Do olho humano à imagem digital
**18/08/2026**

Na aula sobre fundamentos da imagem digital, vimos dois assuntos que pareciam distantes de "computação" à primeira vista: a biologia do olho humano e a física da luz. Fiquei me perguntando por que um curso de Ciência da Computação começa por aí — e ao final da aula ficou bem mais claro. Trago aqui duas perguntas simples que resumem o que mais me chamou atenção.

***"O que a visão humana tem a ver com a formação de imagens digitais?"***

O olho é revestido por três membranas (córnea/esclera, coroide e retina), e é na retina que ficam os fotorreceptores responsáveis por converter luz em impulsos nervosos: os cones (sensíveis à cor, concentrados na fóvea, usados na visão fotópica/diurna) e os bastonetes (sensíveis a baixos níveis de luz, espalhados pela retina, usados na visão escotópica/noturna). O que mais me interessou foi que a nossa percepção de brilho não é uma simples função da intensidade real da luz — fenômenos como as bandas de Mach e o contraste simultâneo mostram que o cérebro "ajusta" o que vemos dependendo do contexto ao redor (a ilusão do tabuleiro de xadrez da sombra, do Edward Adelson, é um exemplo clássico disso). Ou seja, muito antes de existir uma câmera ou um sensor digital, o próprio sistema visual humano já faz um tipo de "processamento de imagem" — e entender essas limitações e comportamentos ajuda a entender por que certas técnicas de processamento digital de imagens existem (como ajustes de contraste e correção de brilho).

***"Como a luz e o espectro eletromagnético explicam as cores que enxergamos — e por que usamos RGB nas imagens digitais?"***

A luz visível é só uma fatia bem pequena do espectro eletromagnético, entre aproximadamente 400 nm (violeta) e 700 nm (vermelho), cercada por ultravioleta de um lado e infravermelho do outro. Cada cor que vemos corresponde a uma faixa de comprimento de onda, e um objeto tem a cor que tem porque reflete certos comprimentos de onda e absorve outros (um objeto verde, por exemplo, reflete luz principalmente entre 500 e 570 nm). Achei interessante que a retina humana consiga captar toda essa variedade de cores com apenas três tipos de cone, cada um mais sensível a uma faixa (aproximadamente vermelho, verde e azul) — é basicamente a teoria tricromática da visão. E é exatamente por isso que representamos cores em imagens digitais combinando três canais primários (R, G, B): o padrão não foi uma escolha arbitrária de engenharia, mas sim um reflexo de como o próprio olho humano decompõe a luz em três "canais" de sensibilidade.

No fim, essas duas perguntas se conectam: entender como o olho humano vê é o que explica por que escolhemos representar e processar imagens digitais do jeito que fazemos.

---
[Voltar à página inicial](index.md)
---
