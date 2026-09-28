# Demonstração — Consulta da ECD no Receitanet BX

> Projeto de portfólio de **Victória Pedrosa**. **Demonstração** de consulta da ECD no Receitanet BX — versão com dados fictícios (nomes, CNPJs, e-mails e IDs internos substituídos).

## Problema de negócio
Consultar a ECD de cada empresa no Receitanet BX é repetitivo.

## Antes x depois
| | Antes | Depois |
|---|---|---|
| Como é feito | Consulta manual no programa. | Robô (reconhecimento de imagem) faz a consulta e registra erros. |

## Ganho
- Consultas em lote.

## Tecnologias
PyAutoGUI (RPA por imagem), Python, SQLite, openpyxl

## Arquivos
- `automacao_bx.py`
- `requirements.txt`

## Como rodar
1. `pip install -r requirements.txt`
2. Copie `.env.exemplo` para `.env` e preencha os caminhos.
3. Execute o script principal.

> As imagens de referência usadas pelo robô para clicar na tela (PyAutoGUI) não foram incluídas nesta versão.

## Autora
Victória Pedrosa — Product Owner do Time de IA, automação de processos contábeis e fiscais.
