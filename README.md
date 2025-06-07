🛰️ Alerta Cidadão – Sistema de Monitoramento de Enchentes
Alerta Cidadão é uma aplicação Java desenvolvida com o objetivo de oferecer suporte à população em áreas urbanas de risco, por meio do monitoramento de enchentes. A proposta é fornecer informações relevantes em tempo real e facilitar a atuação da defesa civil.

⚙️ Tecnologias Utilizadas
Java (Spring Boot)

Thymeleaf (template engine)

HTML/CSS (estilização das páginas)

Spring Data JPA (persistência de dados)

Banco de Dados H2

Spring MVC

🎯 Objetivo do Sistema
O sistema foi projetado para auxiliar moradores de regiões com histórico de alagamentos a se informarem de forma rápida e precisa. O foco principal é:

📍 Cadastrar e listar rotas seguras de evacuação em casos de enchente;

🔎 Pesquisar e filtrar rotas por bairro ou cidade;

✏️ Editar e remover rotas conforme atualizações da Defesa Civil;

🧭 Facilitar o acesso às informações de localização, bairro, cidade, CEP e endereço completo.

🖼️ Funcionalidades da Interface
A interface do sistema apresenta um visual moderno e intuitivo:

Barra de busca de rotas;

Filtro para visualização de todas as rotas;

Cartões com informações completas de cada rota;

Botões de editar e excluir rotas;

Opção de adicionar nova rota;

Botão para voltar à página inicial.

## 💡 Funcionalidades

- ✅ Cadastro de rotas seguras com:
  - Bairro
  - Endereço completo
  - Cidade/UF
  - CEP
- ✅ Listagem de rotas cadastradas
- ✅ Filtro de busca por rotas
- ✅ Edição e exclusão de rotas
- ✅ Interface responsiva com design moderno
- ✅ Integração com Thymeleaf para renderização dos dados
- 🛠️ Backend estruturado com DTOs, Services e Repositories

🗂️ Estrutura do Projeto
controller/ – Controladores responsáveis pelo fluxo da aplicação.

model/ – Classes de domínio (entidades).

repository/ – Interfaces para acesso ao banco de dados.

templates/ – Arquivos HTML com integração via Thymeleaf.

static/ – Arquivos CSS utilizados para a estilização.

application.properties – Configurações da aplicação e banco de dados H2.

▶️ Como Executar
Clone o repositório ou extraia os arquivos .zip no IntelliJ IDEA ou Eclipse.

Execute a aplicação com a classe principal AlertaCidadaoApplication.

Acesse no navegador: http://localhost:8080/rotas

✅ Instruções para Acesso e Testes
Siga os passos abaixo para executar e testar o sistema Alerta Cidadão em sua máquina local.

▶️ Execução Local
✔️ Pré-requisitos:
Java 17 ou superior instalado

Maven instalado


🚀 Passo a passo:
Clone ou extraia o projeto em sua máquina:

git clone [URL do repositório]  (caso esteja no GitHub)
ou apenas abra a pasta do projeto na IDE.

No terminal da raiz do projeto, execute:

mvn spring-boot:run

Acesse no navegador:

http://localhost:8080/rotas

🧪 Como Testar o Sistema
1. 📄 Página Inicial
2. 
Exibe todas as rotas cadastradas.

Permite busca por bairro ou cidade.

Mostra cartões com endereço, bairro, cidade e CEP.

2. ➕ Cadastrar Nova Rota
Clique em “Cadastrar nova rota”.

Preencha os seguintes campos:

Endereço

Bairro

Cidade

CEP

Clique em Salvar para registrar a nova rota.

3. ✏️ Editar uma Rota Existente
Na listagem de rotas, clique no botão Editar ao lado da rota desejada.

Faça as alterações nos campos.

Clique em Atualizar rota para salvar as mudanças.

4. ❌ Excluir uma Rota
Clique no botão Excluir ao lado da rota que deseja remover.

A rota será removida da base de dados.

5. 🔍 Buscar por Localização
Use o campo de busca no topo da página para filtrar rotas por:

Bairro

Cidade

O sistema exibirá somente as rotas que correspondem à pesquisa.

💡 Observações
O sistema utiliza banco de dados em memória H2, que é reiniciado sempre que a aplicação é parada.

Ideal para testes rápidos e demonstrações locais.

O layout é responsivo e intuitivo, facilitando a navegação para qualquer usuário.

Os botões de editar e excluir permitem a gestão fácil dessas rotas.

## 👨‍💻 Desenvolvedor

- RM 553941 - LORENZO AUGUSTO VAZ FRANCISCO
- RM 553079 - GABRIEL OLIVEIRA RODRIGUES DOS SANTOS
  
- Orientado para segurança urbana e uso de tecnologia em benefício da população
