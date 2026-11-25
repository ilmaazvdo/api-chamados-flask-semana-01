# API de Chamados com Flask

**Estudante:** Ilma Rodrigues Vieira Azevedo

## Objetivo

Projeto desenvolvido para a atividade 1 da disciplina ADS0021. O objetivo é criar a estrutura inicial de uma API de chamados de suporte com Flask, reproduzindo o desenvolvimento apresentado na aula.

Neste momento, a API não implementa cadastro de chamados nem banco de dados.

## Pré-requisitos

- Python 3.12 ou superior
- `uv` instalado

## Instalar as dependências

Execute na raiz do projeto:

```bash
uv sync --locked
```

## Executar a aplicação

Para executar localmente:

```bash
uv run flask --app app run --host=0.0.0.0 --port=5000
```

No Codespaces, use exatamente:

```bash
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## Acessar a rota inicial

Com a aplicação em execução, acesse:

- http://localhost:5000/

Resposta esperada, com status HTTP `200`:

```json
{
  "mensagem": "API de chamados em funcionamento"
}
```

Também pode ser verificada no terminal:

```bash
curl -i http://localhost:5000/
```
