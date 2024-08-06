# Projeto de Tradução com Flask e Microsoft Azure

Este repositório contém uma aplicação web simples desenvolvida em Python usando Flask. A aplicação permite traduzir textos entre diferentes idiomas utilizando o serviço de tradução do Microsoft Azure.

## Funcionalidades

- Tradução de textos entre diversos idiomas.
- Interface web simples e intuitiva.
- Integração com o serviço de tradução do Microsoft Azure.

## Requisitos

- Python 3.8 ou superior
- Conta no Microsoft Azure com acesso ao serviço de Tradução (Azure Translator)
- Flask
- Requests

## Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
```
## 2. Crie um ambiente virtual
```bash
python -m venv venv
```
## 3. Ative o ambiente virtual
No Windows:
```bash
venv\Scripts\activate
```
No Linux/MacOS:
```bash
source venv/bin/activate
```
## 4. Instale as dependências
```bash
pip install -r requirements.txt
```
## 5. Configure as variáveis de ambiente
Crie um arquivo .env na raiz do projeto e adicione suas credenciais do Microsoft Azure ou outros serviços:
```bash
KEY= YOUR_API_KEY
ENDPOINT= YOUR_REPOSITORY_ENDPOINT
LOCATION= YOUR_SERVICE_LOCATION
```
## 6. Execute a aplicação
```bash
flask run
```
A aplicação estará disponível em http://127.0.0.1:5000/.

## Estrutura do Projeto
```bash
nome-do-repositorio/
├── app.py
├── templates/
│   └── index.html
|   └── results.html
├── static/
│   └── style.css
├── requirements.txt
└── README.md
```
app.py: Arquivo principal da aplicação Flask.
templates/index.html: Template HTML para a interface web.
static/style.css: Arquivo CSS para estilização.
requirements.txt: Lista de dependências do projeto.
README.md: Instruções e informações sobre o projeto.

### Uso
Abra a aplicação em seu navegador: http://127.0.0.1:5000/.
Digite o texto que deseja traduzir e selecione os idiomas de origem e destino.
Clique em "Traduzir" para ver o resultado.

### Contribuição
Faça um fork do repositório.
Crie uma nova branch: git checkout -b minha-nova-feature.
Faça suas alterações e commit: git commit -am 'Adiciona nova feature'.
Faça um push para a branch: git push origin minha-nova-feature.
Envie um Pull Request.

### Licença
Este projeto está licenciado sob a [MIT License.](https://opensource.org/license/mit)
