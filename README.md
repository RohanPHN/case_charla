# Desafio Técnico Charla

Este projeto é a solução para o desafio técnico da vaga de **Jr AI Engineer** na startup Charla. O objetivo é extrair informações estruturadas de Notas Fiscais de Serviço (PDFs) utilizando a biblioteca `PydanticAI` e um agente de IA construído sob o Gemini 2.5 Flash.

**Obs: comentários adicionais sobre a resolução do projeto estão contidos no arquivo** `Desafio_Charla_PauloRohan.ipynb`.

## Requisitos

Certifique-se de ter os seguintes itens instalados e configurados:

- Python 3.8 ou superior
- Bibliotecas necessárias (instaladas via `pip`):
  - `pydantic`
  - `pydantic-ai`
  - `google-auth`
- Credenciais de conta de serviço do Google Cloud (arquivo JSON fornecido no desafio).

## Configuração do Ambiente

1. Clone este repositório para sua máquina local:
   ```bash
   git clone https://github.com/RohanPHN/case_charla
   ```

2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```

3. Coloque o arquivo de credenciais do Google Cloud na pasta `dados/` e atualize o caminho no notebook, se necessário.

## Como Rodar o Projeto

1. Abra o arquivo `Desafio_Charla_PauloRohan.ipynb` em um ambiente Jupyter Notebook ou VS Code.
2. Certifique-se de que os arquivos PDF estão na pasta `dados/`.
3. Execute as células do notebook na ordem para:
   - Configurar o ambiente.
   - Ler os PDFs.
   - Extrair e validar os dados estruturados.

## Estrutura do Projeto

- `Desafio_Charla_PauloRohan.ipynb`: Notebook principal contendo o código e explicações.
- `dados/`: Pasta contendo os arquivos de Notas Fiscais de Serviço em PDF e credenciais. **Por motivos de segurança, os arquivos PDF não estão incluídos neste repositório, pois contêm dados pessoais.** Para testar o código, substitua os arquivos nesta pasta por PDFs de exemplo.

## Contato

rohanphn@gmail.com