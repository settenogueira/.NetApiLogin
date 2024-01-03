<h1 align="center"> .NET 6 e Identity: implementando controle de usuário </h1>

<p align="center">
Projeto de uma api para controle de acesso de usuários feito por Thiago Sette.
</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;
  |&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Projeto</a>&nbsp;&nbsp;&nbsp;
  |&nbsp;&nbsp;&nbsp;
  <a href="#-Identity">Identity</a>&nbsp;&nbsp;&nbsp;
  |&nbsp;&nbsp;&nbsp;
  <a href="#-Token">Token JWT</a>&nbsp;&nbsp;&nbsp;
  |&nbsp;&nbsp;&nbsp;
  <a href="#-Política de acesso">Política de acesso</a>&nbsp;&nbsp;&nbsp;
  |&nbsp;&nbsp;&nbsp;
  <a href="#-Handlers">Handlers</a>&nbsp;&nbsp;&nbsp;
  |&nbsp;&nbsp;&nbsp;
  <a href="#-Secrets">Secrets</a>&nbsp;&nbsp;&nbsp;
  |&nbsp;&nbsp;&nbsp;
  <a href="#-LINQ">LINQ</a>&nbsp;&nbsp;&nbsp;
 </p>
<br>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- Autenticação e Cadastro de Usuários:
  * Utilização eficiente do Identity para simplificar o cadastro e autenticação de usuários.

- Segurança:
  * Implementação de tokens JWT para reforçar a segurança.

- Comunicação e Interatividade:
  * Integração do ASP.NET para aprimorar o envio eficiente de e-mails.

- Proteção de Dados Sensíveis:
  * Adoção de práticas de segurança, como ocultação de informações através de secrets.

- Usabilidade:
  * Combinação de tecnologias visando proporcionar uma solução eficaz e intuitiva para os usuários

## 💻 Projeto

Em nosso projeto, focamos na criação de uma arquitetura sólida, priorizando a compreensão de conceitos como organização de código e implementação eficiente do Identity para facilitar o cadastro e autenticação de usuários. Reforçamos a segurança ao incorporar tokens JWT e adotamos o ASP.NET para aprimorar a comunicação através do envio de e-mails. Para proteção de dados sensíveis, implementamos a prática de ocultar informações por meio de secrets. O resultado é uma solução eficaz que combina desempenho, segurança e usabilidade de forma coesa e intuitiva.


## 💻 Token

A tecnologia de Token JWT (JSON Web Token) é uma ferramenta eficaz para garantir a segurança e integridade das informações em aplicações web. Funcionando como um padrão aberto (RFC 7519), o JWT é um formato compacto e autocontido que permite a transferência segura de dados entre partes, geralmente utilizado para autenticação e autorização. Sua estrutura baseada em JSON facilita a leitura e interpretação, enquanto a assinatura digital proporciona autenticidade e verificabilidade dos dados. Um aspecto notável do JWT é sua capacidade de armazenar informações de forma encapsulada, tornando-o ideal para comunicações entre microsserviços ou em ambientes distribuídos. Sua versatilidade e eficiência fazem do JWT uma escolha popular para a implementação de sistemas seguros e escaláveis em diversas aplicações web e serviços online.

## 💻 Política de acesso

A Política de Acesso é uma tecnologia crucial para o controle de permissões e restrições em sistemas de software. Essa abordagem define diretrizes e regras que determinam quais usuários ou entidades têm autorização para acessar recursos específicos dentro de uma aplicação. Ao estabelecer políticas de acesso, os desenvolvedores podem gerenciar de maneira granular as permissões de usuários, restringindo ou permitindo ações com base em funções, atributos ou outros critérios definidos. Essa tecnologia é fundamental para garantir a segurança e a conformidade em ambientes digitais, permitindo a configuração flexível de acessos de acordo com as necessidades específicas de cada sistema. A implementação eficiente de políticas de acesso contribui para a construção de aplicações robustas, adaptáveis e alinhadas aos princípios de segurança e governança exigidos em diversos contextos.Handlers

## 💻 Handlers

Handlers são uma tecnologia essencial no desenvolvimento de software, desempenhando um papel fundamental na manipulação de eventos, requisições ou situações específicas em um sistema. Em contextos como frameworks web, os handlers são frequentemente utilizados para processar solicitações HTTP, permitindo que desenvolvedores personalizem o comportamento da aplicação em diferentes estágios do ciclo de vida de uma requisição. Esses componentes são responsáveis por lidar com tarefas específicas, como autenticação, autorização, logging, entre outros. A flexibilidade oferecida pelos handlers permite a modularização do código, simplificando a manutenção e proporcionando uma arquitetura mais escalável e adaptável. Ao permitir a execução de código personalizado em momentos específicos, os handlers desempenham um papel crucial na implementação de lógicas específicas, contribuindo para a eficiência e a personalização de sistemas diversos.Secrets

## 💻 Secrets

Handlers são uma tecnologia essencial no desenvolvimento de software, desempenhando um papel fundamental na manipulação de eventos, requisições ou situações específicas em um sistema. Em contextos como frameworks web, os handlers são frequentemente utilizados para processar solicitações HTTP, permitindo que desenvolvedores personalizem o comportamento da aplicação em diferentes estágios do ciclo de vida de uma requisição. Esses componentes são responsáveis por lidar com tarefas específicas, como autenticação, autorização, logging, entre outros. A flexibilidade oferecida pelos handlers permite a modularização do código, simplificando a manutenção e proporcionando uma arquitetura mais escalável e adaptável. Ao permitir a execução de código personalizado em momentos específicos, os handlers desempenham um papel crucial na implementação de lógicas específicas, contribuindo para a eficiência e a personalização de sistemas diversos.