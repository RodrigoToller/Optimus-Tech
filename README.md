# 7 Days of Code

Este projeto faz parte de um desafio de 7 dias, no qual será implementada uma nova funcionalidade a cada dia.

# Funcionalidades

- ## Dia 1: Implementação do Cabeçalho (Navbar)

  ### HTML:
  - Criação da tag Header, para controle do cabeçalho 
  - Criação de Divs e Nav para separação do conteudo
  - Dentro da Nav efetuada a criação de uma lista para dispor elementos ancora
  - Introduzido Logo e Botões de registro e Login ( Inicio e fim da pagina)

  ### CSS:

  - importa a fonte "Merriweather" do Google Fonts.
  - Define variáveis de cores.
  - Aplica estilos globais para o corpo da página.
  - Estiliza o cabeçalho com flexbox e transições suaves.

---
  ![Imagem do Cabeçalho](img/README%20FILES/cabeçalho.png)
---


## - Dia 2: Estruturação da Main:

  ### HTML: 
  - Criação da tag main, para controle do conteudo da pagina
  - Criação da seção "largura maxima"
  - Inclusão das informações do "Sobre nós"
  ### CSS:
  - Corpo-da-pagina: Conteúdo principal.
  - secao-corpo-largura-maxima: Seção com largura máxima.
  - sobre-nos: subtitulo "Sobre nós".
  - porque-diferentes: Título "Por que somos diferentes?".
  - texto-main: Texto explicativo.

---
  ![Imagem do Sobre nós](img/README%20FILES/Sobre-nós.png)
--- 



## - Dia 3: Informações da empresa

  ### HTML:
  - Criada a seção informações da empresa
  
  ##### - Dentro da seção, foi criada uma div "INFO-CLASSE", com os elementos  h3, h4 e p:
  - H3 - Numeros em evidencia
  - H4 - Subtitulo
  - p - Descrição da informação 

  ### CSS:
  #####  Foi efetuada a estilização utilizando hieraquia de seletor descendente com a classe INFO-CLASSE sendo nossa classe pai
  #
  - H3 - Estilização: cor principal (vermelha), tamanho do texto (grande)
  - H4 - Estilização: cor padrão (preta), tamanho do texto (pequeno)
  - p -  Estilização: cor subtexto (cinza), tamanho do texto (pequeno)
  
  
---
![Imagem Info Empresa](img/README%20FILES/Informacoes-empresa.png)
---






## - Dia 4: Oportunidades de Carreira

### HTML:
  - Criada a seção para oportunidades de carreira
  
  ##### - Dentro dessa seção iremos encontrar os seguintes elementos:

  - H2 - "balão" chamativo "vagas abertas"
  - H3 - Titulo em evidência 
  - p - texto descritivo 
  - img - imagem da equipe

### CSS:
#####  Nosso CSS foi construido a base de classes cada uma estilizando um elemento
#

 - Foi efetuada a mudança de fonte do projeto para Kanit para um melhor design da pagina.

### .texto-vagas-evidencia

- Texto de tamanho médio e em negrito
- Cor principal e fundo colorido suave
- Alinhado ao centro
- Tem margem em cima e preenchimento
- Bordas arredondadas
- Texto em letras maiúsculas

### .titulo-destaque-vagas

- Título grande e em negrito
- Cor preta
- Alinhado ao centro

### .texto-vagas

- Texto de tamanho médio e leve
- Cor de texto suave
- Alinhado ao centro

### .imagem-equipe

- Imagem ocupa 80% da largura
- Altura média
- Bordas arredondadas
- Sombra suave ao redor da imagem


---
![Imagem Info Empresa](img/README%20FILES/dia%204.png)
---




# - Dia 5: Campo Vagas

### HTML:
  - Criada a seção profissão (local onde encontraremos as oportunidades de trabalho da empresa)
  
  #### - Dentro dessa seção iremos encontrar a seguinte estrutura:

  **Div Profissão**  - separa por tipo do cargo (Ex: Designer), nesta div teremos:

     h2 - Titulo do tipo do cargo 
     div - card da vaga 

  **div Card da vaga:** - separa as vagas disponiveis pela seguinte estrutura:

    span - titulo da vaga 
    h5 jornada de trabalho
    h5 - salario


 

### CSS:
#####  Nosso CSS foi construido para deixar as vagas mais bonitas e organizadas
#


### .card-vaga

- Organiza o conteúdo em uma grade
- Tem uma largura média
- Espaçamento entre os itens
- Tem um fundo colorido suave
- Tem bordas arredondadas e uma margem em cima

### .titulo-cargo

- Título maior e em negrito
- Cor preta

### .titulo-vaga

- Título com margem em cima
- Texto mais destacado

### .campos-informativos-profissao

- Informações organizadas em linha
- Espaçamento entre as informações
- Cor de texto suave
---
![Imagem Info Empresa](img/README%20FILES/dia%205.png)
---

# Dia 6: Depoimentos

### HTML:
  - Criada a seção depoimentos (local onde encontraremos os depoimentos dos colaboradores da empresa)
  
  #### - Dentro dessa seção iremos encontrar a seguinte estrutura:

     p - Informação sobre o depoimento
     h2 - Evidencia do depoimento 
     img - foto do colaborador 
     p - Nome do colaborador
     p - Cargo do colaborador
 

### CSS:
#####  Nosso CSS foi construido para deixar a seção de depoimentos mais atrativa e organizada

## Estilos de Depoimentos

### .secao-depoimento

- Organiza o conteúdo em uma grade
- Espaçamento entre os itens
- Tem margens nas laterais e em cima/baixo
- Tem um preenchimento interno
- Fundo colorido suave
- Bordas arredondadas
- Conteúdo centralizado

### .alinhar

- Centraliza os itens

### .info-depoimento

- Texto com margem em cima
- Cor principal
- Tamanho médio e peso moderado

### .titulo-depoimento

- Título grande e em negrito
- Cor preta
- Alinhado ao centro

### .nome-colaborador

- Tamanho médio e peso moderado
- Cor preta

### .cargo-colaborador

- Texto com margem embaixo
- Tamanho médio e peso leve
- Cor de texto suave
---
![Imagem Info Empresa](img/README%20FILES/dia%206.png)
---



# Dia 7: Rodapé

### HTML:
  - Criada o Rodapé da pagina.
  
  #### - No rodapé iremos encontrar a seguinte estrutura:

    
     h2 - Titulo do rodapé
     p - descrição da informação do rodapé
     input - Input para campo email
     button - botão para cadastrar o email
     p - mensagem de copyright
 

### CSS:
#####  Nosso CSS foi construido para deixar o rodapé mais convidativo e atrativo.

### footer

- Sem margens
- Fundo com cor suave
- Preenchimento interno

### .rodape-secao

- Organiza o conteúdo em uma grade
- Espaçamento entre os itens
- Margens laterais e em cima/baixo

### .titulo-oportunidades

- Título grande e peso moderado
- Cor preta
- Alinhado ao centro

### .subtitulo-oportunidades

- Tamanho médio e peso leve
- Cor de texto suave
- Alinhado ao centro

### .campo-email

- Organiza os itens em linha
- Espaçamento entre os itens

### .input-email

- Preenchimento interno
- Bordas arredondadas
- Tamanho de texto médio
- Peso moderado
- Bordas sólidas e cor suave

### .botao-cadastro

- Preenchimento interno
- Bordas arredondadas
- Tamanho de texto médio
- Peso moderado
- Alinhado ao centro
- Sem bordas
- Cursor de ponteiro
- Efeito de transição ao passar o mouse
- Fundo com cor principal
- Texto com cor de fundo suave

### .texto-copy

- Tamanho pequeno e peso leve
- Cor de texto suave
- Alinhado ao centro



---
![Imagem Info Empresa](img/README%20FILES/dia%207.png)
---







