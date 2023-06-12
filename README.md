# Tarefa 7 - Projeto e Implementação de Aplicativos - Macaroni Penguin

Este projeto é uma solução proposta para implementação de um sistema educacional completamente digital e facilitador. Ele foi desenvolvido com o objetivo de oferecer para empresas, a possibilidade de avaliar de maneira mais precisa e eficiente a qualidade técnica dos candidatos. O software engloba ferramentas e funcionalidades que visam oferecer capacitação técnica e acesso à vagas de emprego, tornando-o o ambiente ideal para o futuro do mercado. O projeto utiliza a linguagem Dart e o FrameWork Flutter para possibilitar o FrontEnd, enquanto que faz uso de Java 17 (JDK 17), Spring Boot 3.0 e MariaDB para os processos requisitados no BackEnd.



## Built With
Java 17 (JDK 17)

Spring Boot 3.0

MariaDB

Flutter (Dart)

## Funcionalidades


1. Sistema de Login
a. Autenticação por e-mail e senha;

b. Sistema de Cadastro;

2. Níveis de Permissão
a. Acesso para Alunos:

- Cursos, testes e vagas divulgadas.
b. Acesso para Mentores:

- Últimas atividades concluídas pelos alunos.

c. Acesso para Empresas Parceiras:

- Todas as atividades concluídas pelos alunos. Resultados (notas) intermediários e finais dos alunos nos cursos aos quais a empresa é parceira. Criação e Administração de Vagas de Emprego.

d. Acesso para Administradores:

- Tudo. Exclusividade na Criação e Administração de Treinamentos.

3. Funcionalidade de Treinamento (Criados por Administradores)

- Composição: Nome Comercial, Código Único gerado pelo Sistema, Descrição, Carga Horária, Data de início e fim das inscrições, Data de início e fim do treinamento, Quantidade mínima e máxima de inscritos para que o treinamento seja ofertado, Tarefa Seletora (Quiz de Seleção) com Sistema Automático de Correção, que é Registrado no Histórico do Aluno Possibilidade de Inscrição dos Alunos se o Período de Inscrição for atual.

4. Funcionalidade das Vagas de Emprego
- Empresas Parceiras podem administrar vagas, que contem: Título da Vaga, Empresa que Oferta a Vaga, Descrição das Atividades a serem Desempenhadas, Requisitos para Candidatura, Faixa Salarial, Lista com Usuários Inscritos, Possibilidade de Cadastro de Alunos

5. Atividades dos Alunos
a. Para os alunos e empresas parceiras, mostra o registro de todas as atividades que ele fez no sistema, incluindo:
- Treinamentos que ele se candidatou
- Treinamentos que ele não passou (com indicação do motivo)
- Treinamentos que ele concluiu
b. Para os Mentores, são exibidas apenas as 10 últimas atividades.




## Instalação e Uso Técnico:

Para realizar a instalação e configuração, afim de utilizar-se do software desenvolvido até o momento, siga as seguintes instruções:

Download e Configurações de Plataforma de Gerenciamento de Contêineres:

No caso, as instruções indicam diretamente o download e configuração do Docker.

### Baixar o Docker:

Visite o site oficial do Docker (Docker) e faça o download da versão compatível com o seu sistema operacional.
Siga as instruções de instalação específicas para o seu sistema operacional.

### Verificar a instalação do Docker:

Após a instalação, verifique se o Docker está corretamente instalado no seu sistema.

Abra um terminal ou prompt de comando e execute o comando docker --version para verificar a versão do Docker instalada.

Execute o comando docker run hello-world para verificar se o Docker está funcionando corretamente.

### 1. Instalar o Flutter SDK:

Faça o download do Flutter SDK no site oficial do Flutter (https://flutter.dev).

Extraia o arquivo zip em um local de sua preferência.

Adicione o diretório Flutter para o seu PATH do sistema operacional.

### 2. Instalar o Dart SDK:

Faça o download do Dart SDK no site oficial do Dart (https://dart.dev/).

Extraia o arquivo zip em um local de sua preferência.

Adicione o diretório do Dart SDK para o seu PATH do sistema operacional.

### 3. Configurar o Flutter no seu editor de código preferido:

Você pode usar o Android Studio, Visual Studio Code ou qualquer outro editor de sua preferência com suporte ao Flutter. (O Grupo Macaroni Penguin utilizou-se do IntelliJ IDEA Ultimate).

Instale a extensão Flutter para o seu editor de código escolhido.
