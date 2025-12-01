# academy_hub
Gerenciamento de informações acadêmicas (alunos, cursos, notas, pagamentos etc.)

⚙ Instalação e Execução
*Clone o repositório:
git clone https://github.com/SEU-USUARIO/AcademicHub.git
cd AcademicHub

*Instale as dependências:
npm install

*Configure o banco de dados:
Ajuste a conexão com o SQL Server em src/config/db.js
Crie as tabelas necessárias ou execute o script de migração
Gere dados fictícios com os scripts em src/scripts/

*Inicie o servidor:
npm start
O servidor ficará disponível em http://localhost:3000.

*Acesse o frontend:
Navegue até a pasta public
Abra index.html no navegador

☁ Observações sobre Deploy
O projeto não utiliza serviços em nuvem.
O banco de dados é gerenciado localmente em Linux com o Azure Data Studio.

ℹ Nota
Desenvolvido para fins acadêmicos com foco em práticas de desenvolvimento full-stack, inspirado em metodologias de gestão de dados universitários.
