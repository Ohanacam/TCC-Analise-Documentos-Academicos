# Análise Automatizada de Documentos Acadêmicos

**Trabalho de Conclusão de Curso (TCC) – Engenharia de Computação | UNOESC**

Solução de automação para apoiar o coordenador de curso na análise de documentos do processo de **aproveitamento de disciplinas**, combinando **RPA** (Automação Robótica de Processos) e **Inteligência Artificial**.

--

## Sobre o projeto

A solução auxilia o coordenador na análise de **históricos escolares** e **ementas de disciplinas**, automatizando a extração de informações, a comparação entre conteúdos programáticos e a classificação das disciplinas quanto à possibilidade de aproveitamento.

**Objetivo:** reduzir atividades manuais e fornecer informações que apoiem a análise e a tomada de decisão do coordenador.

---

## Funcionalidades

- Leitura automatizada de históricos escolares e ementas.
- Extração de informações acadêmicas: nome da disciplina, carga horária e conteúdo programático.
- Análise dos dados com base em regras previamente definidas.
- Comparação de disciplinas por critérios de similaridade.
- Interface para consulta, revisão e validação dos resultados.
- Geração de relatório de aproveitamento de disciplinas.
- Envio dos resultados por e-mail.

### Classificação das disciplinas

| Status | Significado |
|---|---|
| **APROVADO** | Disciplina com possibilidade de aproveitamento. |
| **REPROVADO** | Disciplina sem possibilidade de aproveitamento. |
| **NECESSITA DE REVISÃO** | Disciplina que requer análise complementar do coordenador. |

---

## Tecnologias utilizadas

| Tecnologia | Aplicação |
|---|---|
| UiPath | Automação Robótica de Processos (RPA) |
| DU-OCR | Reconhecimento óptico de caracteres e extração de informações dos documentos |
| GPT-5.4 | Processamento e análise das informações com Inteligência Artificial |

---

## Arquitetura e funcionamento

| Etapa | Descrição |
|---|---|
| 1. Entrada de documentos | Recebimento do histórico escolar e das ementas das disciplinas. |
| 2. Extração de informações | Leitura dos documentos e identificação dos dados acadêmicos relevantes. |
| 3. Análise e comparação | Processamento das informações e comparação entre as disciplinas de origem e as da instituição. |
| 4. Classificação | Identificação das possibilidades de aproveitamento. |
| 5. Validação | Apresentação dos resultados para revisão e confirmação pelo coordenador. |
| 6. Finalização | Geração do relatório e envio do resultado da solicitação por e-mail. |

---

## Estrutura do repositório

```text
TCC-Analise-Documentos-Academicos/
├── Documentos/
│   ├── Resultados/        # Arquivos gerados durante os testes da aplicação
│   └── Testes/            # Documentos utilizados como entrada para os testes
├── Imagens/               # Capturas de tela da aplicação e das etapas do processamento
├── Videos/
│   └── demonstracao.md    # Link do vídeo de demonstração
└── README.md              # Apresentação do projeto, objetivo, tecnologias e acesso
```

---

## Demonstração e acesso

- 🎬 **Vídeo de demonstração:** [Assistir ao vídeo](enviar link)
- 🌐 **Acesso à aplicação:** [Acessar a aplicação](https://unoesctcc.uipath.host/analisadordocumentos)

---

## Testes para a banca avaliadora

Os documentos abaixo permitem que a banca execute testes na aplicação e acompanhe o processamento automatizado de uma solicitação de aproveitamento de disciplinas.

### Arquivos de entrada (`Documentos/Testes`)

| Arquivo | Descrição |
|---|---|
| `06_Historico_Escolar_Anonimo_da_Silva.pdf` | Histórico escolar do aluno, documento principal da análise. |
| `01_Ementa_Algoritmos_e_Logica_de_Programacao.pdf` | Ementa de Algoritmos e Lógica de Programação. |
| `02_Ementa_Modelagem_de_Processos_e_Sistemas.pdf` | Ementa de Modelagem de Processos e Sistemas. |
| `03_Ementa_Banco_de_Dados_Relacional.pdf` | Ementa de Banco de Dados Relacional. |
| `04_Ementa_Gestao_Financeira.pdf` | Ementa de Gestão Financeira. |
| `05_Ementa_Biologia_Geral.pdf` | Ementa de Biologia Geral. |

### Passo a passo

1. Baixe todos os documentos da pasta `Documentos/Testes`.
2. Acesse a aplicação pelo link da seção [Demonstração e acesso](#demonstração-e-acesso).
3. Envie o histórico escolar e as cinco ementas.
4. Execute o processamento automatizado.
5. Acompanhe as etapas de extração, comparação e classificação.
6. Consulte os resultados e valide as análises.
7. Ao finalizar, verifique a geração do relatório e o envio do resultado por e-mail.

> **Observação:** os documentos foram organizados para fins de demonstração e avaliação acadêmica da solução.

### Resultados de referência

Na pasta `Documentos/Resultados` está disponível um exemplo de **relatório final de aproveitamento de disciplinas** (DOCX e PDF), gerado pela aplicação. Ele serve como referência para a banca visualizar o formato e as informações apresentadas ao final do processamento.

---

## Resultados esperados

Espera-se que a solução otimize o processo de aproveitamento de disciplinas, reduzindo o esforço operacional na leitura e análise dos documentos acadêmicos, oferecendo maior organização das informações e suporte à tomada de decisão do coordenador.

---

## Informações acadêmicas

| | |
|---|---|
| **Curso** | Engenharia de Computação |
| **Instituição** | Universidade do Oeste de Santa Catarina – UNOESC |
| **Trabalho** | Trabalho de Conclusão de Curso (TCC) |
| **Autor** | Ohana Camargo dos Santos |
| **Orientador** | Cidinei Luiz Cassol |
| **Ano** | 2026 |