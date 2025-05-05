# RFC - Alexandre Salgado

## Título do Projeto
**Ainda não definido**

**Nome do Estudante:** Alexandre Salgado  
**Curso:** Engenharia de Software  
**Data de Entrega:** 31/03/2025  

---

## Resumo

Este projeto tem como objetivo desenvolver um aplicativo mobile em **Flutter**, para facilitar a interação entre tutores de pets e promover a adoção e o reencontro de animais perdidos. A plataforma contará com três funcionalidades principais:

1. Uma rede social exclusiva para cães e gatos;
2. Uma aba para adoção de pets;
3. Uma seção para publicação de animais desaparecidos, com informações adicionais de contato.

Será utilizado **Firebase Firestore** para armazenamento de dados e **Firebase Storage** para upload de imagens. O aplicativo visa conectar amantes de pets e contribuir para a redução do abandono animal.

---

## Introdução

### Contexto

A adoção de animais e o reencontro de pets perdidos são desafios enfrentados por tutores e ONGs. Hoje, a maioria das iniciativas acontece em redes sociais convencionais, que não são ideais para esse fim.

### Justificativa

A proposta é desenvolver uma ferramenta especializada que promova a adoção responsável e facilite a busca por animais desaparecidos, utilizando tecnologias modernas e escaláveis como Flutter e Firebase.

### Objetivos

#### Objetivo Geral
Criar um aplicativo intuitivo e funcional que conecte donos de animais, adotantes e pessoas que buscam reencontrar seus pets perdidos.

#### Objetivos Específicos
- Implementar sistema de cadastro de pets.
- Criar uma rede social para cães e gatos.
- Desenvolver uma aba para adoção.
- Adicionar uma seção para publicação de animais desaparecidos.

---

## Descrição do Projeto

### Tema do Projeto
Desenvolvimento de um aplicativo mobile usando Flutter e Firebase, voltado exclusivamente para cães e gatos, com funcionalidades sociais, adoção e localização de pets desaparecidos.

### Problemas a Resolver
- Dificuldade de comunicação entre adotantes e doadores;
- Ausência de plataforma social específica para pets;
- Falta de ferramenta centralizada para localização de animais perdidos;
- Localização ineficiente de pets disponíveis ou desaparecidos.

### Limitações
- Restrito a cães e gatos;
- Geolocalização baseada em dados manuais (sem GPS);
- Sem verificação de autenticidade nas adoções, mas com:
  - Termos de uso;
  - Dicas de adoção segura.

---

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

---

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

---

## Representação dos Requisitos
(UML de Casos de Uso – a ser inserida)

---

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
