# TodoApi
API desenvolvida para cadastrar, editar e excluir uma lista de TODO's

## Criação 
O projeto foi criado a partir do modelo API Web do ASP.NET Core (Visual Studio 2022)
 
## Banco de Dados
O projeto utiliza o contexto de banco de dados Microsoft.EntityFrameworkCore.InMemory, instalado pelo gerenciados de pacotes NuGet

### Pré-requisitos
Visual Studio 2022 com a carga de trabalho de desenvolvimento Web e do ASP.NET.

### Como criar do zero
* No menu arquivo , selecione novo project.
* Insira a API Web na caixa de pesquisa.
* Selecione o modelo de API Web do ASP.NET Core e selecione avançar.
* Na caixa de diálogo Configurar seu novo projeto, nomeie o projeto TodoApi e selecione Avançar.
* Na caixa de diálogo informações adicionais:
  * Confirme se a estrutura é .net 6,0 (suporte a longo prazo).
  * Confirme se a caixa de seleção para usar controladores (desmarque para usar APIs mínimas) está marcada.
  * Selecione Criar.

### Como adicionar pacotes NuGet
O contexto de banco de dados é a classe principal que coordena a funcionalidade do Entity Framework para um modelo de dados. Essa classe é criada derivando-a da classe Microsoft.EntityFrameworkCore.DbContext.

* No menu ferramentas, selecione NuGet Gerenciador de Pacotes / gerenciar pacotes de NuGet para solução.
* Selecione a guia procurar e, em seguida, insira na caixa de pesquisa Microsoft.EntityFrameworkCore.InMemory.
* Selecione Microsoft.EntityFrameworkCore.InMemory no painel esquerdo.
* Marque a caixa de seleção do projeto (TodoApi) no painel direito e, em seguida, selecione instalar.
