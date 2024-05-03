# Case Técnico - H:Data // Matheus Tenório

## Descrição do projeto:

### Setup:
Crie um ambiente virtual
```bash
python -m venv venv
```

Ative o ambiente virtual
```bash
source venv/bin/activate
```

Instale as dependências
```bash
pip install -r requirements.txt
```

### Case 1:

- **Objetivo 1:** Coletar informações da base de dados
- **Objetivo 2:** Trabalhar o Enriquecimento dos dados da aba principal com os dados complementares
  em abas e planilhas adicionais
- **Objetivo 3:** Gerar um arquivo de saída com os dados enriquecidos
- **Objetivo 4:** Exportar os dados enriquecidos para um DW

O case 1 solucionado pode ser encontrado [aqui](./analysis/case-1.ipynb).

Dentro do prazo dado (6 horas) não foi possível realizar o bônus, eis uma possibilidade de solução:

1. Ler a planilha de mapeamento de colunas e usá-la como input para o script de enriquecimento e exportação.

### Case 2:
- **Objetivo 1:** Realizar uma interpretação dos dados recebidos e da qualidade dos campos identificados como principais.
- **Objetivo 2:** Relacionar os dados recebidos de modo a qualificar a informação da base principal a partir de informações complementares.
- **Objetivo 3:** Compreender a jornada do paciente de tal forma que:
  - A. Seja identitificado quais etapas podem ser monitoradas por meio da base de dados enviada;
  - B. Seja identificada a ordem prioritária do fluxo de atendimento da unidade e dos possíveis desvios de fluxo de atendimento.
  - C. Seja tangibilizada a jornada do paciente, explicitando os tempos de espera entre as diversas etapas envolvidas no fluxo de atendimento.
- **Objetivo 4:** Exportar os dados enriquecidos como base única.

O que foi possível solucionar do case 2 dentro do tempo previsto ( Objetivos 1, 3A e 3B) pode ser encontrado [aqui](./analysis/case-2.ipynb).

Agradeço ao tempo dos que se dispuseram a avaliar o que foi desenvolvido nesse repositório.
