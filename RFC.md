# Capa

- **Título do Projeto**
- **Ainda não definido**
- **Nome do Estudante:** Alexandre Salgado  
- **Curso:** Engenharia de Software  
- **Data de Entrega:** 31/03/2025  

# Resumo

 Este projeto tem como objetivo desenvolver um aplicativo mobile em Flutter, para facilitar
 a interação entre tutores de pets e promover a adoção e o reencontro de animais perdidos. A
 plataforma contará com três funcionalidades principais: uma rede social exclusiva para cães e 
 gatos, uma aba para adoção de pets e uma seção para publicação de animais desaparecidos,
 permitindo o fornecimento de informações adicionais de contato. O aplicativo oferecerá um
 sistema de cadastro no qual os usuários poderão registrar seus animais, informando raça, foto
 de perfil, data de nascimento e localização. A arquitetura do sistema será baseada no Firebase
 Firestore para armazenamento de dados e Firebase Storage para upload de imagens. O projeto
 busca criar uma solução acessível e intuitiva para conectar amantes de pets, contribuindo para
 o bem-estar animal e a redução do abandono.

## 1. Introdução

- **Contexto**: A adoção de animais e o reencontro de pets perdidos são desafios comuns
enfrentados por tutores e organizações de bem-estar animal. Muitas iniciativas utilizam
redes sociais convencionais para esses propósitos, mas não há um ambiente dedicado
exclusivamente para essa finalidade. A ausência de uma plataforma especializada
dificulta a conexão entre adotantes e doadores, bem como a localização rápida de
animais desaparecidos.

- **Justificativa**: O desenvolvimento deste aplicativo se justifica pela necessidade de uma
ferramenta centralizada que facilite a interação entre tutores de animais, promovendo a
adoção responsável e auxiliando na busca por pets perdidos. No campo da engenharia
de software, o projeto se destaca pelo uso de tecnologias modernas, como Flutter e
Firebase, oferecendo uma solução eficiente e escalável para um problema social
relevante.

- **Objetivos**: O objetivo principal do projeto é criar um aplicativo intuitivo e funcional que
conecte donos de animais, interessados em adoção e pessoas que buscam reencontrar
seus pets perdidos. Como objetivos secundários, destacam-se:

  - Implementar um sistema de cadastro que permita aos usuários registrar informações sobre seus pets.
  - Criar uma rede social restrita a publicações relacionadas a cães e gatos.
  - Desenvolver uma aba dedicada à adoção de animais.
  - Disponibilizar uma seção para publicação de animais desaparecidos, incluindo
informações adicionais para contato.


## 2. Descrição do Projeto

- **Tema do Projeto**: O projeto consiste no desenvolvimento de um aplicativo mobile em
Flutter, utilizando Firebase para gerenciamento de banco de dados e armazenamento de
imagens. O app será uma plataforma voltada exclusivamente para cães e gatos,
oferecendo uma rede social onde os donos podem postar fotos de seus pets, além de
contar com funcionalidades voltadas para adoção e localização de animais perdidos. A
proposta é criar um ambiente interativo e útil para os amantes de pets, promovendo a
adoção responsável e facilitando o reencontro de animais desaparecidos.

- **Problemas a Resolver**:
  - Dificuldade na comunicação entre adotantes e doadores de animais.
  - Falta de uma plataforma exclusiva para donos de pets compartilharem fotos deseus animais.
  - Falta de uma ferramenta centralizada para publicação e busca de animais perdidos.
  - Dificuldade em encontrar pets desaparecidos ou disponíveis para adoção próximos à localização do usuário.

- **Limitações**:
  - O aplicativo será restrito a cães e gatos, não abrangendo outros tipos de animais.
  - A funcionalidade de geolocalização será baseada nos dados cadastrados pelos usuários
  (cidade, estado, bairro), sem rastreamento em tempo real.
  - Não será implementado um sistema de verificação de autenticidade para adoções,
  ficando a responsabilidade para os usuários. Para minimizar riscos, o aplicativo contará com:
    - Termos de uso e avisos informando que a adoção é de responsabilidade
    dos usuários.
    - Dicas de adoção segura, incentivando boas práticas.

## Especificação Técnica

### Tecnologias
- **Flutter** para o desenvolvimento do app.
- **Firebase Firestore** para banco de dados.
- **Firebase Storage** para imagens.
- **Firebase Authentication** para login.
- **Google Maps API** para localização.

### Algoritmos e Protocolos
- JWT para autenticação.
- Feed dinâmico com base na localização (cidade, estado, bairro).
- Sistema de denúncias com moderação automática.

### Funcionalidades
- Cadastro de usuários e pets.
- Upload de fotos.
- Publicação de pets para adoção e desaparecidos.
- Feed com prioridade para postagens locais.
- Sistema de denúncias para moderação.


## Requisitos de Software

### Requisitos Funcionais
- RF01: Criar conta e login.
- RF02: Registrar pets (raça, idade, foto, localização).
- RF03: Postar fotos dos pets.
- RF04: Visualizar e interagir no feed.
- RF05: Exibir no feed pets perdidos e para adoção.
- RF06: Cadastrar pet para adoção ou desaparecido.
- RF07: Denunciar postagens inadequadas.

### Requisitos Não Funcionais
- RNF01: Compatível com Android e iOS.
- RNF02: Feed deve carregar em menos de 3 segundos.
- RNF03: Dados devem ser protegidos com autenticação e criptografia.
- RNF04: Usar Firebase Firestore para escalabilidade.


## Representação dos Requisitos
(UML de Casos de Uso – a ser inserida)


## Stack Tecnológica

### Linguagens
- **Dart**

### Frameworks/Bibliotecas
- Flutter
- Firebase Authentication
- Firebase Firestore
- Firebase Storage
- Google Maps API

### Ferramentas
- **Figma** – Prototipação de interfaces
- **Visual Studio Code (VSCode)** – IDE
- **GitHub** – Versionamento
- **Trello** – Gestão de tarefas

---

## Considerações de Segurança

- Autenticação via Firebase
- Criptografia de dados
- Sistema de moderação
- Avisos sobre responsabilidade na adoção

---

## Referências

- [Flutter](https://flutter.dev)
- [Firebase](https://firebase.google.com)
- [Dart](https://dart.dev)
- [Google Maps API](https://developers.google.com/maps)
- [Figma](https://www.figma.com)
- [Visual Studio Code](https://code.visualstudio.com)
- [GitHub](https://github.com)
- [Trello](https://trello.com)

---

## Avaliações dos Professores

Adicionar páginas ao final com espaços para as considerações e assinaturas:

- Considerações Professor(a):
- Considerações Professor(a):
- Considerações Professor(a):
