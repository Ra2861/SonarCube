### o que é sonarcube:

O SonarQube é uma ferramenta que além de avaliar a saúde geral de uma aplicação, pode destacar problemas e bugs no código. Com um Portão de Qualidade em vigor, você pode limpar o código enquanto o escreve e melhorar sistematicamente a qualidade do código. Além disso, essa ferramenta facilita o planejamento e a alocação de tarefas para um grupo de programadores.

O SonarQube pode ajudar a medir o progresso facilmente e validar a importância do trabalho técnico que é difícil de visualizar ou demonstrar, especialmente para clientes não técnicos. Vamos explorar alguns dos benefícios do SonarQube e como você pode implementá-lo em seu fluxo de trabalho.

**Recursos Principais do SonarQube:**

Portão de Qualidade que permite definir um padrão de qualidade aceitável para mesclar branches e lançar aplicações em produção.
Análise de código apresentada de forma gráfica e transparente, permitindo que programadores e não programadores tenham visibilidade do progresso de codificação.
Oferece insights para analisar bugs, vulnerabilidades de segurança e duplicação de código.
Permite priorizar rapidamente as mudanças e melhorias de código.
Não se limita apenas a problemas de qualidade de código predefinidos. Se desejar, é possível criar regras personalizadas para monitorar problemas específicos.
Oferece suporte para mais de 27 linguagens de programação.
Oferece uma Edição Comunitária gratuita e de código aberto, juntamente com várias Edições para uso comercial.

**Preparar o Ambiente SonarQube:**

Instalamos o Java e o Docker. Recomenda-se o uso do Docker, uma abordagem popular atualmente, e o Java SDK é necessário para o funcionamento do SonarScanner.
Configuramos uma aplicação de exemplo para análise com o SonarQube.
Executamos a Análise do Projeto com o SonarQube:

Inicie o servidor SonarQube com o comando docker run.
Instale o SonarScanner para .NET Core e execute a análise de código.
Resultados da Análise no SonarQube:

Visualize as informações principais do SonarQube acessando a URL http://localhost:9000, onde o container Docker do SonarQube está exposto. Essa visualização apresenta informações gerais, como contadores de bugs, vulnerabilidades e problemas de código, além de duplicações de código.

Esta visualização apresenta informações gerais, como contadores de bugs, vulnerabilidades e número de duplicações de código. 

Essa é a visão mais simples: 

![image](https://github.com/Ra2861/SonarCube/assets/99209068/9465d617-7a48-4905-a934-bbae0fbcbe23)<br/>

Relatórios mais detalhados da seção Medidas: <br/>
![image](https://github.com/Ra2861/SonarCube/assets/99209068/d8a7beda-cb84-4834-8b48-10e9eb2d6824)

É possível determinar quantos bugs cada arquivo de projeto contém e visualizar as linhas de código problemáticas: 
![image](https://github.com/Ra2861/SonarCube/assets/99209068/fd79a2c7-12ee-476e-a83d-398ee870ec5e)

