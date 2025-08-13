<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
</head>
<body>
  <h1>🏦 Projeto DioBank - IA para Geração de SQL com Linguagem Natural</h1>

  <p>
    Este projeto foi desenvolvido como parte do desafio final da formação de Inteligência Artificial aplicada à geração de SQL da <strong>DIO (Digital Innovation One)</strong>. O objetivo foi criar um agente inteligente capaz de interpretar perguntas em linguagem natural e traduzi-las em consultas SQL válidas para um banco de dados MySQL.
  </p>

  <h2>🎯 Objetivo do Projeto</h2>
  <ul>
    <li>Desenvolver uma aplicação com interface interativa usando <strong>Streamlit</strong>.</li>
    <li>Conectar a um banco de dados <strong>MySQL</strong> real com tabelas relacionadas.</li>
    <li>Utilizar a <strong>API da OpenAI</strong> para geração de consultas SQL a partir de linguagem natural.</li>
    <li>Demonstrar conhecimento em integração de IA com aplicações reais.</li>
  </ul>

  <h2>🧠 Tecnologias Utilizadas</h2>
  <ul>
    <li>Python 3.11</li>
    <li>Streamlit</li>
    <li>Panda</li>
    <li>MySQL</li>
    <li>MySQL Connector (mysql-connector-python)</li>
    <li>OpenAI API (ChatGPT)</li>
    <li>dotenv para gerenciamento de variáveis sensíveis</li>
  </ul>

  <h2>📂 Estrutura do Projeto</h2>
  <ul>
    <li><code>agentes/terminal_agent.py</code> – Arquivo principal com interface e integração</li>
    <li><code>protocolos/prompt.json</code> – Arquivo com o prompt de sistema usado para gerar SQL</li>
    <li><code>.env</code> – Contém as variáveis de ambiente (chave da OpenAI e credenciais do banco)</li>
  </ul>

  <h2>⚙️ Configuração e Execução</h2>
  <ol>
    <li>Clone o repositório</li>
    <li>Crie e ative um ambiente virtual</li>
    <li>Instale as dependências com <code>pip install -r requirements.txt</code></li>
    <li>Preencha o arquivo <code>.env</code> com sua chave OpenAI e credenciais do banco</li>
    <li>Execute o projeto com <code>streamlit run agentes/terminal_agent.py</code></li>
  </ol>

  <h2>📷 Capturas de Tela</h2>
  <p>As capturas estão disponíveis na pasta <code>/images</code>.</p>

  <h2>🚀 Resultado</h2>
  <p>O agente foi capaz de compreender perguntas como:</p>
  <ul>
    <li>"Me mostre todos os clientes"</li>
    <li>"Quais pagamentos foram feitos em 2025?"</li>
    <li>"Liste as movimentações de valor acima de 5000"</li>
  </ul>

  <p>Essas perguntas foram convertidas automaticamente em SQL e executadas no banco de dados.</p>

  <h2>📝 Conclusão</h2>
  <p>
    O projeto demonstra com sucesso a aplicação de Inteligência Artificial para traduzir linguagem natural em consultas SQL, conectando teoria e prática em um cenário real. É uma base sólida para evoluir sistemas inteligentes de análise de dados com foco no usuário final.
  </p>

  <hr />
  <p>Desenvolvido por <strong>Alisson Ramos</strong> – 2025</p>
</body>
</html>
