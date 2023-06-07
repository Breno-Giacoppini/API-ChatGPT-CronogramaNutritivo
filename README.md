# GSPY
<h1>Projeto de Combate ao Desperdício - README</h1>

<p>Este é um projeto que visa combater o desperdício de alimentos, utilizando a tecnologia GPT-3.5 Turbo da OpenAI para criar um cronograma alimentar com base nos ingredientes fornecidos pelo usuário.</p>

<h2>Instruções de Uso</h2>

<ol>
<li><strong>Requisitos</strong>
   <ul>
   <li>Certifique-se de ter uma chave de API válida para o GPT-3.5 Turbo da OpenAI.</li>
   <li>Verifique se as dependências necessárias estão instaladas corretamente. O projeto requer a biblioteca <code>requests</code> e <code>json</code>.</li>
   </ul>
</li>
<li><strong>Obtenção do Cardápio</strong>
   <ul>
   <li>O programa solicitará que você digite os ingredientes disponíveis.</li>
   <li>Para cada ingrediente, digite o nome, a quantidade e a validade.</li>
   <li>Após inserir os ingredientes desejados, você será perguntado se deseja adicionar mais um item.</li>
   <li>O programa considera duas refeições por dia (almoço e janta).</li>
   </ul>
</li>
<li><strong>Definição do Cronograma</strong>
   <ul>
   <li>Após obter os ingredientes, o programa solicitará informações adicionais.</li>
   <li>Digite o número de dias para o cronograma alimentar.</li>
   </ul>
</li>
<li><strong>Geração do Cronograma Alimentar</strong>
   <ul>
   <li>O programa utilizará a tecnologia GPT-3.5 Turbo para gerar um cronograma alimentar com base nos ingredientes fornecidos.</li>
   <li>Será apresentado o cronograma de acordo com os ingredientes disponíveis.</li>
   </ul>
</li>
</ol>

<h2>Detalhes do Projeto</h2>

<p>Este projeto utiliza a biblioteca <code>apiKey</code> para importar a chave de API necessária para a autenticação com a API da OpenAI. Certifique-se de possuir uma chave válida para utilizar o serviço.</p>

<p>A função <code>gpt3_responder(pergunta)</code> realiza uma solicitação à API do GPT-3.5 Turbo, enviando a pergunta como entrada e obtendo uma resposta gerada pelo modelo.</p>

<p>A função <code>obter_cardapio()</code> solicita ao usuário que insira os ingredientes disponíveis, armazenando-os em uma lista juntamente com suas quantidades e validades.</p>

<p>A função <code>pergunta_chatgpt()</code> utiliza a função <code>obter_cardapio()</code> para obter os ingredientes, suas quantidades e validades, e monta uma pergunta para o GPT-3.5 Turbo com base nesses dados.</p>

<p>Por fim, o programa gera a pergunta para o GPT-3.5 Turbo e obtém a resposta correspondente, que será exibida na saída.</p>

<h2>Execução do Código</h2>

<p>Para executar o código, certifique-se de ter preenchido corretamente as informações necessárias, como a chave de API e as dependências do projeto. Após isso, execute o código e siga as instruções fornecidas pelo programa.</p>

<p>Lembre-se de que o código atualmente possui apenas a estrutura básica e pode ser aprimorado de acordo com as necessidades do projeto.</p>

<p>Esperamos que esse projeto ajude a reduzir o desperdício de alimentos e promova uma alimentação mais consciente e equilibrada.</p>
