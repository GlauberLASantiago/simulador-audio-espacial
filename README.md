## Simulador de Áudio Espacial

Aplicação web didática desenvolvida para demonstrar, de forma simples e interativa, princípios básicos de espacialização sonora.

O simulador permite comparar diferentes modos de reprodução, incluindo áudio mono, panorama estéreo e espacialização binaural com HRTF. O usuário pode carregar um arquivo de áudio próprio ou utilizar um sinal de teste, movimentando a fonte sonora ao redor do ouvinte por meio de controles de azimute, elevação e distância.

Também é possível ativar uma órbita automática de 360°, facilitando a percepção do deslocamento espacial do som com o uso de fones de ouvido.

### Principais recursos

* carregamento de arquivos de áudio;
* sinal sonoro de demonstração;
* reprodução em mono;
* controle de panorama estéreo;
* espacialização binaural com HRTF;
* ajuste de azimute, elevação e distância;
* movimentação automática em 360°;
* visualização gráfica da posição da fonte sonora;
* funcionamento direto no navegador, sem necessidade de instalação.

### Objetivo educacional

O app foi concebido como recurso de apoio ao ensino de áudio espacial, permitindo que estudantes, músicos e produtores sonoros experimentem conceitos que normalmente são apresentados apenas de forma teórica.

A proposta é tornar mais concretas diferenças entre:

* reprodução mono;
* panorama estéreo;
* localização sonora;
* percepção de distância;
* movimento ao redor do ouvinte;
* espacialização binaural.

### Como usar

1. Abra o arquivo `simulador_audio_espacial.html` em um navegador moderno.
2. Utilize fones de ouvido.
3. Carregue um arquivo de áudio ou selecione o som de teste.
4. Escolha o modo de reprodução.
5. Ajuste a posição da fonte sonora no campo gráfico ou pelos controles.
6. Ative a órbita de 360° para ouvir o deslocamento contínuo.

### Tecnologias utilizadas

* HTML5;
* CSS3;
* JavaScript;
* Web Audio API;
* `StereoPannerNode`;
* `PannerNode` com modelo HRTF.

### Observação técnica

O modo binaural utiliza recursos de espacialização da Web Audio API. Portanto, o aplicativo não implementa uma cadeia completa de codificação e decodificação Ambisonics. Trata-se de uma simulação pedagógica voltada à compreensão inicial de direção, distância, azimute e elevação sonora.

### Requisitos

* navegador atualizado, preferencialmente Google Chrome, Microsoft Edge ou Firefox;
* fones de ouvido;
* nenhum servidor ou instalação adicional é necessário.

### Possíveis aplicações

* aulas de áudio e produção musical;
* introdução à espacialização sonora;
* demonstrações em cursos de música;
* estudos sobre percepção auditiva;
* comparação entre mono, estéreo e áudio binaural;
* apoio a pesquisas sobre áudio imersivo.
