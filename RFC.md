
# Ambiente Interativo para Aprendizagem de Violão Assistida por Inteligência Artificial

**Nome do Estudante**: Alexandre Salgado  
**Curso**: Engenharia de Software  
**Data de Entrega**: 07/06/2025  

---

## Resumo

Este projeto tem como objetivo principal desenvolver um software interativo para auxílio no aprendizado e na prática de violão, focado no reconhecimento de acordes em tempo real. A aplicação será desenvolvida em Flutter, permitindo a criação de versões para desktop (Windows) e mobile (Android/iOS) a partir de uma única base de código. A plataforma integrará funcionalidades didáticas, como uma partitura interativa inspirada no Songsterr, um metrônomo visual e sonoro, e um braço de violão virtual que exibe as digitações corretas. O aplicativo oferecerá um sistema de feedback instantâneo ao usuário sobre a precisão da execução dos acordes. A inteligência artificial para o reconhecimento de acordes será processada em um backend em Python, utilizando bibliotecas como TensorFlow/Keras e Librosa, com o aplicativo Flutter comunicando-se com este backend. O software busca não apenas auxiliar no aprendizado e prática, mas também engajar o usuário através de elementos de gamificação que tornam o processo mais motivador e divertido.

---

## 1. Introdução

### Contexto

O aprendizado de violão, especialmente a correta execução dos acordes e a leitura de partituras, é um desafio comum para iniciantes e mesmo para músicos intermediários. A ausência de feedback preciso e interativo durante a prática solo é uma barreira significativa para o aprimoramento técnico e musical. Ferramentas digitais existentes muitas vezes carecem de uma integração fluida entre reconhecimento em tempo real, visualização interativa da música e recursos didáticos completos.

### Justificativa

O desenvolvimento deste software se justifica pela necessidade de uma ferramenta centralizada e multiplataforma que ofereça feedback preciso e interativo para praticantes de violão. Ao combinar o reconhecimento de acordes por Inteligência Artificial com elementos didáticos visuais e auditivos (partitura interativa, metrônomo e braço do violão), o projeto visa preencher uma lacuna no mercado de ferramentas de aprendizado musical, oferecendo uma experiência imersiva e eficaz. Essa eficácia será potencializada pela inclusão de elementos de gamificação, que visam aumentar o engajamento do usuário e a motivação a longo prazo, transformando a prática em uma jornada mais divertida e recompensadora. A escolha do Flutter se justifica pela sua capacidade de criar aplicativos de alta performance para desktop e mobile a partir de uma única base de código, otimizando o desenvolvimento, a manutenção e a acessibilidade da solução. No campo da engenharia de software, o projeto se destaca pelo uso de tecnologias modernas de IA e desenvolvimento multiplataforma, oferecendo uma solução eficiente, escalável e com ampla compatibilidade para um problema de aprendizado relevante.

### Objetivos

O objetivo principal do projeto é criar um software intuitivo e funcional, compatível com sistemas desktop (Windows) e dispositivos móveis (Android/iOS), que auxilie praticantes de violão a dominar a execução de acordes com precisão e confiança.

**Como objetivos secundários, destacam-se:**

- Implementar um sistema de reconhecimento de acordes baseado em IA que opere em tempo real, fornecendo feedback instantâneo.
- Implementar elementos de gamificação, como sistema de níveis, desafios diários e conquistas, para aumentar o engajamento e a motivação do usuário.
- Desenvolver uma interface de usuário rica e performática em Flutter, com foco na interatividade da partitura.
- Integrar um metrônomo configurável com feedback visual e sonoro, sincronizado com o reconhecimento de acordes e a partitura.
- Criar uma visualização interativa do braço do violão que exiba as digitações corretas dos acordes da partitura.
- Prover a opção de escolha entre microfone embutido e interfaces de áudio externas como fonte de entrada de áudio.
- Gerenciar a comunicação eficiente e de baixa latência entre o aplicativo Flutter (frontend) e o backend Python (IA).

---

## 2. Descrição do Projeto

- **Tema do Projeto**: Tutor virtual de violão com IA para reconhecimento de acordes.
- **Problemas a Resolver**:
  - Falta de feedback interativo durante a prática.
  - Dificuldade em saber se o acorde está correto.
  - Falta de motivação e acompanhamento do progresso.

- **Limitações**:
  - Reconhecimento limitado a acordes comuns.
  - Sensível à qualidade do áudio.
  - Partitura inicial em formato simplificado.

- **Elementos de Gamificação**:
  - Sistema de níveis e XP.
  - Desafios diários.
  - Conquistas e emblemas.

---

## 3. Especificação Técnica

### Tecnologias

- **Frontend**: Flutter (Dart) – multiplataforma  
- **Backend**: Python com Flask  
- **IA**: TensorFlow/Keras, Librosa  
- **Comunicação**: HTTP/WebSockets  
- **Áudio**: Plugins Flutter (`record`, `audio_stream`)

### Algoritmos e Protocolos

- CNN-LSTM para reconhecimento de acordes  
- Algoritmo de sincronização com metrônomo  
- Suavização de saída do modelo para estabilidade

### Funcionalidades

- Captura e envio de áudio para backend  
- Partitura interativa com rolagem  
- Braço do violão com digitação e feedback  
- Metrônomo visual/sonoro  
- Feedback instantâneo  
- Gamificação (XP, níveis, desafios, conquistas)

---

## 4. Requisitos de Software

### Requisitos Funcionais (RF)

- RF01: Seleção de entrada de áudio  
- RF02: Captura e envio de chunks de áudio  
- RF03: Reconhecimento de acordes pelo backend  
- RF04: Carregamento e exibição de partitura  
- RF05: Feedback visual na partitura e braço do violão  
- RF06: Configuração de BPM  
- RF07: Feedback gamificado (XP, conquistas)  
- RF08: Notificações de progresso e desafios  
- RF09: Visualização do braço do violão com digitações  
- RF10: Sistema de XP e recompensas  
- RF11: Sessões de prática (iniciar/pausar/parar)  
- RF12: Exibição de progresso e conquistas  
- RF13: Sistema de moeda virtual

### Requisitos Não Funcionais (RNF)

- RNF01: Compatibilidade com Windows, Android e iOS  
- RNF02: Latência de resposta inferior a 300ms  
- RNF03: Precisão de reconhecimento superior a 85%  
- RNF04: Interface intuitiva e responsiva  
- RNF05: Suporte a variações de áudio e técnicas de toque  
- RNF06: Gamificação eficiente sem impacto na performance

---

## 5. Representação dos Requisitos

```mermaid
graph TD
    Usuario([Usuário])
    RF01[Selecionar fonte de áudio]
    RF02[Capturar e enviar áudio]
    RF03[Reconhecer acorde via backend]
    RF04[Carregar partitura]
    RF05[Exibir partitura interativa]
    RF06[Configurar BPM do metrônomo]
    RF07[Receber feedback visual e sonoro]
    RF08[Notificações de progresso e desafios]
    RF09[Exibir braço do violão e digitações]
    RF10[Receber XP e conquistas]

    Usuario --> RF01
    Usuario --> RF02
    Usuario --> RF03
    Usuario --> RF04
    Usuario --> RF05
    Usuario --> RF06
    Usuario --> RF07
    Usuario --> RF08
    Usuario --> RF09
    Usuario --> RF10
```

---

# 6. Stack Tecnológica

### Linguagens

- Dart (frontend)  
- Python (backend)  

### Frameworks/Bibliotecas

- Flutter  
- Flask  
- TensorFlow/Keras  
- Librosa  
- NumPy  

### Ferramentas

- VSCode  
- GitHub  
- Trello  
- Figma  

---

# 7. Considerações de Segurança

- Comunicação segura via HTTPS  
- Segurança na API Flask  
- Termos de uso claros  
- Robustez contra entradas inválidas  
- Considerações sobre ataques adversariais (IA)

---

# 8. Referências

- [Flutter](https://flutter.dev)  
- [Dart](https://dart.dev)  
- [Flask](https://flask.palletsprojects.com)  
- [TensorFlow](https://www.tensorflow.org)  
- [Keras](https://keras.io)  
- [Librosa](https://librosa.org)  
- [Guitar Chords Dataset - Kaggle](https://www.kaggle.com/datasets/fabianavinci/guitar-chords-v2)  
- [Visual Studio Code (VSCode)](https://code.visualstudio.com)  
- [GitHub](https://github.com)  
- [Trello](https://trello.com)  
- [Songsterr](https://www.songsterr.com)  

---

# 9. Avaliações dos Professores

- Considerações Professor(a):  
- Considerações Professor(a):  
- Considerações Professor(a):
