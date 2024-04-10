Projeto  de consumido de api, da escola DNC
link do Site Disponibilizado : https://projetodncweather.netlify.app/
Nesse projeto Foram Avalidados 
Desenvolvendo as telas
1. Desenvolvimento Baseado no Protótipo: Utilize o protótipo disponível no
Figma como referência precisa para a criação da interface. Isso inclui o layout,
elementos gráficos, posicionamento de campos e botões, cores e estilos.
Garanta que a interface seja fiel ao design apresentado no protótipo.
2. Implementação da Tela de Informações: Concentre-se na criação da tela de
informações, onde os usuários poderão inserir os dados necessários, como
nome, endereço e cidade. Certifique-se de criar todos os campos relevantes
de acordo com as especificações do protótipo.
3. Validação de Campos: Implemente validações de entrada de dados para
garantir que todos os campos obrigatórios sejam preenchidos
adequadamente e que os dados inseridos estejam no formato correto.
Forneça feedback claro aos usuários caso haja problemas de validação.
4. Utilização do Bootstrap (Opcional): Você tem a opção de utilizar o framework
Bootstrap para facilitar o desenvolvimento do design da aplicação. O
Bootstrap oferece componentes e estilos predefinidos que podem acelerar o
processo de desenvolvimento. No entanto, seu uso não é obrigatório e fica a
critério do aluno decidir se deseja utilizá-lo.

Construindo a integração

1. Desenvolvimento dos Formulários: Comece desenvolvendo os formulários
em HTML para que os usuários possam inserir os dados necessários.
Certifique-se de seguir o layout e os elementos gráficos conforme definido no
protótipo do Figma.
Desafio: Desenvolva tela funcional com consumo de API 4
2. Funcionalidade de Consumo de Dados: Desenvolva as funcionalidades de
consumo de dados utilizando JavaScript. Você precisará criar duas funções
separadas: uma para consumir os dados do CEP e outra para consumir os
dados da previsão do tempo.
3. Utilização de Práticas Assíncronas: Utilize as práticas async e await para
criar essas funções assíncronas. Isso garantirá um comportamento eficaz na
tela que irá exibir os dados, permitindo que a aplicação continue funcionando
de forma responsiva enquanto aguarda a resposta da API.

Desenvolver as duas funcionalidades necessárias
utilizando JavaScript para consumir as API´s. Para conseguir realizar o
desenvolvimento dessas funcionalidades siga esses passos:
1. Declaração de Variáveis: Inicie declarando variáveis para armazenar os
dados fornecidas pelo usuário. Esses valores serão utilizados para realizar a
consulta na API´s de cep e previsão do tempo.
2. Chamada da API: Utilize o método fetch para fazer uma requisição na API´s.
3. Atualização da Interface: Utilize os dados obtidos da API para atualizar
dinamicamente a interface do usuário (DOM) com as informações relevantes.
Por exemplo, você pode exibir a temperatura atual da região em um elemento
HTML específico.

Testando as informações
Garantir a qualidade e a confiabilidade das APIs que você desenvolveu nas etapas
anteriores. É essencial que as APIs funcionem corretamente e forneçam dados
precisos. Para isso, siga as seguintes diretrizes
Verifique se todas as informações solicitadas pelos usuários estão sendo
recebidas corretamente.
Certifique-se de que a API está respondendo com um código HTTP 200
quando as solicitações são feitas.
Certifique-se que os dados entregue das API´s, estão de acordo com os
dados enviados para ela.
Garanta que os dados estejam sendo armazenados nos campos apropriados
da aplicação, de acordo com a estrutura definida nas etapas anteriores.


