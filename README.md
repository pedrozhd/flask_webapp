<h1> 📌 Projeto Flask: Catálogo de Jogos </h1>
<p></p>Um WebApp para catalogar jogos em uma biblioteca virtual, desenvolvido com Flask!</p>

<h1>🚀 O que aprendi?</h1>
<h2>Fundamentos do Flask</h2>

- Entendi por que o Flask é um micro-framework ideal para desenvolvimento ágil e projetos menores.

- Aprendi a estrutura básica: app.py, rotas, e a magia por trás de if __name__ == "__main__".

<h2>Rotas e Templates</h2>

- Criei rotas dinâmicas com @app.route e parâmetros (<int:id>).

- Integrei Python com HTML usando render_template() e variáveis dinâmicas ({{ nome }}).

<h2>Formulários e Métodos HTTP</h2>

- Processei dados de formulários com métodos GET (para buscas) e POST (para envios).

- Usei request.form para acessar dados enviados pelo usuário.

<h2>Orientação a Objetos (POO)</h2>

- Estruturei o projeto com classes para modelos de dados (ex: class Jogo).

- Organizei a lógica em funções reutilizáveis.

- Debugging e Eficiência
  - Ativei o debug mode (app.run(debug=True)) para atualizações automáticas sem reiniciar o servidor.

- Usei mensagens de log e tratativas de erro para identificar bugs rapidamente.

<h2>Bootstrap e Front-End</h2>

- Implementei um layout responsivo com Bootstrap ({% extends "base.html" %}).

- Organizei arquivos estáticos (CSS, JS) na pasta static/.

<h2>Templates e Herança</h2>

- Eliminei código repetido com herança de templates (arquivo base.html).

- Usei partials (como _navbar.html) para componentes reutilizáveis.

<h2>Sessões e Autenticação</h2>

- Gerenciei logins com session para manter usuários autenticados.

- Protegi rotas com @login_required (simulado via decorators).

<h1>🛠️ Como executar o projeto?</h1>

<h4>Clone o repositório:</h4>

<h6>bash</h6>
git clone https://github.com/seu-usuario/catalogo-jogos-flask.git

<h4>Instale as dependências:</h4>

<h6>bash</h6>
pip install -r requirements.txt

<h4>Execute o app:</h4>

<h6>bash</h6>
python app.py
