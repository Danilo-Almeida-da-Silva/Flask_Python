# API Livros Doados VnW

Essa é uma API simples feita com Flask e SQLite para fins de estudo da escola Vai Na Web, ela permite cadastrar, listar e doar Livros.

## Como roda o projeto da API?

1. Faça o clone do reposítorio:

```Bash
git clone <Link_do_reposítorio>
cd Nome_do_projeto
```

2. criar um ambiente virtual (Obrigatório):

**Windows**

```bash
python -m venv venv
source venv/Scripts/activate
```

**Linux/Mac**

```bash
python3 -m venv venv
source venv/bin/activate
```

3. Instale as dependências:

```bash
pip install -r requerements.txt
```

4. Inicie o servidor:

```bash
python app.py
```

> A API estará disponível em http://127.0.0.1:5000/

## Endpoints

### Post /doar

Endpoint para cadastro das informações dos livros doados.

**Envio (JSON)**

```json
{
  "titulo": "Ainda estou devendo aqui",
  "categoria": "Drama/Finanças",
  "autor": "Fernando Polia",
  "image_url": "https://exemplo.com"
}
```
