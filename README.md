*Calculadora de IMC com Django*

Este projeto é uma aplicação web desenvolvida em Django para calcular o Índice de Massa Corporal (IMC). O usuário insere seu peso e altura, 
e o sistema retorna o IMC calculado junto com a classificação correspondente.

📌 O cálculo do IMC segue a fórmula padrão:

𝐼𝑀𝐶 = 𝑝𝑒𝑠𝑜 / 𝑎𝑙𝑡𝑢𝑟𝑎²

🚀 Tecnologias Utilizadas foram Python 3, Django e HTML/CSS básico

O sistema também classifica o resultado do IMC, retornando uma das seguintes classificações:
 
- Abaixo do peso: IMC abaixo de 18.5
- Peso normal: IMC entre 18.5 e 24.9
- Sobrepeso: IMC entre 25 e 29.9
- Obesidade grau 1: IMC entre 30 e 34.9
- Obesidade grau 2: IMC entre 35 e 39.9
- Obesidade grau 3: IMC acima de 40
 
Essas métricas vão de encontro com o sistema da OMS (Organização Mundial da Saúde), que utiliza o Índice de Massa Corporal (IMC) como um dos principais indicadores para avaliar o estado nutricional de um indivíduo.

Suas funcionalidades:
 
- Recebe o peso e a altura como entrada via formulário.
- Calcula o IMC com base nos valores fornecidos.
- Classifica o IMC e retorna a classificação.
- Exibe mensagens de erro para valores inválidos, como valores negativos ou não numéricos.

📌 Como Executar o Projeto

1️⃣ Clonar o Repositório

git clone https://github.com/seu-usuario/imc_project.git

cd imc_project

2️⃣ Criar um Ambiente Virtual (Recomendado)
python -m venv venv

Ative o ambiente virtual

> Windows (cmd/PowerShell)

> Linux/Mac

3️⃣ Instalar Dependências


pip install -r requirements.txt

Caso o arquivo requirements.txt ainda não exista, crie-o executando:

pip freeze > requirements.txt


4️⃣ Rodar Migrações do Banco de Dados (Opcional)

python manage.py migrate


5️⃣ Iniciar o Servidor

python manage.py runserver

Acesse no navegador: http://127.0.0.1:8000/


🛠 Estrutura do Projeto

imc_project/

│-- imc_project/         # Configuração principal do Django

│-- imc_app/             # Aplicação da Calculadora de IMC

│   ├── migrations/      # Migrações do banco de dados

│   ├── templates/       # Templates HTML

│   ├── views.py         # Lógica da Calculadora de IMC

│   ├── urls.py          # Rotas da Aplicação

│-- manage.py            # Script de gerenciamento Django

│-- requirements.txt     # Dependências do projeto

│-- README.md            # Instruções do projeto


📌 Como Usar a Calculadora

Insira seu **peso (kg)**.

Insira sua **altura (m)**.

Clique em **Calcular**.

O sistema exibirá seu IMC e sua classificação.


📝 Melhorias Futuras


🎨 Melhorar o design utilizando Bootstrap.


📊 Adicionar gráficos para acompanhar a evolução do IMC.


📁 Armazenar histórico de IMC dos usuários.


🤝 Contribuição


Sinta-se à vontade para contribuir com o projeto! Para isso:

Faça um fork do repositório.

Crie uma branch para sua melhoria (git checkout -b minha-melhoria).

Commit suas mudanças (git commit -m 'Adicionei uma nova funcionalidade').

Faça um push para a branch (git push origin minha-melhoria).

Abra um Pull Request.

📜 Licença

Este projeto está sob a licença MIT. Sinta-se livre para utilizá-lo e modificá-lo! 😊

source venv/bin/activate

venv\Scripts\activate


Kauan Lacerda E Silva - 202412124

Renan Souza Borges - 202410864

Enzo Nascimento Cabrera - 202320732

João Vitor Mendes Da Silva 202411713
