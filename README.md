# Postman Instalaçãoo e Criacao de testes Automatizados

## Instalação
Fazer o download do Postman no seguinte link: https://www.postman.com/downloads/
  next next next

## Criação dos Testes
O Postman trabalhar com a seguinte estrutura, para criação de requisições:
   1. Colections
        -Pasta com conjunto de requisições
   2. Requisições
        -Verbos, JSON, cabeçalho e rota a ser testada.

## Pratica

#### 1. Criar uma Collection 
As collections agrupam os testes, é possível organizar em estruturas os grupos de testes. 
Uma collection nada mais é do que um local onde você irá agrupar todas as suas chamadas.
Exemplos:
![](/img-gif/collections.png)


#### 2. Requisições dos testes
O Postman fornece uma variedade de métodos pra realizar as requisições dos serviços, porém os homologados pelo RESTFULL são os métodos GET, POST, PUT, PATCH e DELETE e podem ser selecionados na aba da área de trabalho.
Exemplo:

#### 3. Informando uma requisição
A requisição (Request) é informada no campo ao lado de onde é escolhido o método, e possui a estrutura baseada em um servidor e sua porta, seguido do restante da URI - http://<server>:<port>/<resource>
Exemplo:
 
#### 4. Suite de Testes
Para gerar um conjunto de testes automatizados, cada requisição precisa ser salva dentro da estrutura da Collection, está por sua vez, pode conter subpastas, formando uma estrutura organizada.
 Exemplo:
 
Estrutura Criada: A suíte é composta por várias requisições e serão executadas sequencialmente no momento da exceção do teste automatizado.


#### 5. Executando o teste automatizado
O Postman proporciona a execução automática das requisições na opção Runner (Topo da tela), que por sua vez apresenta uma nova janela onde se pode parametrizar a execução. Estão disponíveis, por exemplo, as parametrizações para quantidade e iterações, atrasos, log das respostas, entre outras.


#### 6. Resultado do Teste
Após a execução é apresentado um relatório de cada requisição, informando o status de cada requisição que passou (PASS) e que falhou (FAIL).
