# Instrumento de Avaliação — Projeto de Interface Web

## 1. Identificação

| Campo | Informação |
| --- | --- |
| Estudantes | Lucas R. e Davi |
| Turma | Matutino |
| Projeto | NutriViva |
| Docente responsável | Breno Antonio Kunsch |
| Data da avaliação | 19/10/2026 |
| Pontuação máxima | **5,0 pontos** |
| Pontuação obtida | **2,5 pontos** |

## 2. Objetivo da avaliação

Avaliar o atendimento aos requisitos do projeto, considerando a presença e a organização dos conteúdos obrigatórios, a estrutura HTML, o funcionamento dos links e botões e a aplicação do CSS em conformidade com a identidade visual proposta.

Este documento registra as ocorrências informadas pelo docente e as respectivas pontuações atribuídas ao projeto.

## 3. Condições e delimitação da avaliação

A interface foi analisada em uma área de visualização com dimensões equivalentes às de uma tela de celular.

**Os aspectos relacionados à responsividade, incluindo o dimensionamento e a adaptação do menu à tela de celular, foram desconsiderados na avaliação**, uma vez que esse conteúdo ainda não havia sido apresentado à turma.

Limitações decorrentes exclusivamente da ausência de técnicas de responsividade não geraram descontos. Permaneceram sujeitos à avaliação a apresentação dos conteúdos, o funcionamento dos elementos e a aplicação dos estilos previstos na atividade.

## 4. Distribuição da pontuação

| Código | Critério | Pontuação máxima | Pontuação obtida | Desconto |
| --- | --- | ---: | ---: | ---: |
| C1 | Presença e organização das seções e dos textos obrigatórios | 2,0 | 1,5 | 0,5 |
| C2 | Estrutura HTML e funcionamento dos links | 1,5 | 1,0 | 0,5 |
| C3 | Aplicação do CSS e consistência da identidade visual | 1,5 | 0,0 | 1,5 |
| **Total** | **Atendimento aos requisitos** | **5,0** | **2,5** | **2,5** |

## 5. Detalhamento dos critérios

### 5.1. C1 — Presença e organização das seções e dos textos obrigatórios

**Pontuação máxima:** 2,0 pontos.  
**Pontuação obtida:** 1,5 ponto.  
**Desconto aplicado:** 0,5 ponto.

#### Aspectos considerados

- Presença das seções e dos textos exigidos no enunciado.
- Organização dos conteúdos nas respectivas seções.
- Apresentação dos conteúdos da página, considerando a ocorrência de imagens sem carregamento.

#### Ocorrência registrada

As imagens do projeto não são carregadas corretamente na página final, comprometendo a apresentação do conteúdo visual.

#### Justificativa da pontuação

Foi aplicado desconto de 0,5 ponto pela falha na apresentação das imagens. A ocorrência registrada se refere ao carregamento desses recursos; não fundamenta uma afirmação de ausência de textos obrigatórios.

#### Orientações para adequação

- Verificar se os arquivos de imagem estão presentes nos diretórios referenciados pelo projeto.
- Conferir a correspondência entre os nomes e as extensões dos arquivos e os caminhos utilizados no código, inclusive letras maiúsculas e minúsculas.
- Revisar as referências às imagens no HTML e, quando existentes, no CSS.
- Após os ajustes, verificar se as imagens são exibidas na página final.

**Observação técnica:** a falha de carregamento foi informada, mas sua causa específica não foi confirmada. Nomes, caminhos e diretórios devem ser verificados antes de atribuir a falha a um deles.

### 5.2. C2 — Estrutura HTML e funcionamento dos links

**Pontuação máxima:** 1,5 ponto.  
**Pontuação obtida:** 1,0 ponto.  
**Desconto aplicado:** 0,5 ponto.

#### Aspectos considerados

- Estrutura HTML compatível com as seções e os conteúdos solicitados.
- Direcionamento dos links aos destinos previstos na atividade.
- Execução das ações esperadas ao acionar os botões.

#### Ocorrência registrada

Os botões não executam a ação esperada quando são acionados.

#### Justificativa da pontuação

Foi aplicado desconto de 0,5 ponto pela ausência de funcionamento dos botões, considerando as ações previstas na atividade.

#### Orientações para adequação

- Revisar os destinos dos links e as ações previstas para cada botão.
- Conferir as referências às páginas ou às seções de destino, quando aplicáveis.
- Implementar as correções com recursos compatíveis com o conteúdo trabalhado em aula.
- Acionar cada elemento após os ajustes e verificar se o comportamento corresponde ao solicitado.

### 5.3. C3 — Aplicação do CSS e consistência da identidade visual

**Pontuação máxima:** 1,5 ponto.  
**Pontuação obtida:** 0,0 ponto.  
**Desconto aplicado:** 1,5 ponto.

#### Aspectos considerados

- Carregamento e aplicação da folha de estilos principal.
- Aplicação do CSS aos elementos previstos no projeto.
- Coerência da paleta de cores com o logotipo.
- Consistência visual e legibilidade dos conteúdos.

#### Ocorrência registrada

O arquivo principal de estilização, em CSS, não é carregado. Conforme a verificação informada pelo docente, o console do navegador apresenta diversos erros de carregamento de recursos, incluindo o da folha de estilos principal.

#### Justificativa da pontuação

Foi atribuído 0,0 ponto ao critério em razão da falha no carregamento da folha de estilos principal, que impede a aplicação dos estilos nela definidos. A justificativa desta nota está vinculada ao carregamento do CSS; não foi registrada uma constatação específica de conflito entre a paleta de cores e o logotipo.

#### Orientações para adequação

- Abrir as ferramentas de desenvolvedor do navegador, utilizando a tecla `F12` ou a opção **Inspecionar**.
- Consultar o console e a aba de rede para identificar os recursos que não foram carregados.
- Conferir o caminho informado no atributo `href` do elemento `<link>` responsável pela folha de estilos.
- Verificar a presença do arquivo CSS no diretório indicado, bem como a correspondência de seu nome e extensão.
- Corrigir as referências identificadas como incorretas e recarregar a página.
- Após restabelecer o carregamento, conferir a aplicação dos estilos e a apresentação da identidade visual.

## 6. Quadro consolidado das observações

| Item | Constatação registrada | Critério relacionado | Adequação indicada |
| --- | --- | --- | --- |
| 1 | As imagens não são carregadas corretamente na página final. | C1 | Verificar a presença dos arquivos e suas referências no código. |
| 2 | Os botões não executam a ação esperada ao serem acionados. | C2 | Revisar os destinos e implementar as ações previstas na atividade. |
| 3 | A folha de estilos principal não é carregada; há erros de carregamento de recursos no console, incluindo o CSS. | C3 | Conferir o arquivo e sua referência no HTML, corrigindo os caminhos quando necessário. |

## 7. Registro da avaliação

### 7.1. Evidências e justificativas

| Critério | Evidência informada | Justificativa da pontuação | Nota |
| --- | --- | --- | ---: |
| C1 — Conteúdo e organização | Imagens sem carregamento correto na página final. | Comprometimento da apresentação do conteúdo visual. | 1,5 / 2,0 |
| C2 — HTML e funcionamento dos links | Botões sem execução da ação esperada. | Atendimento parcial ao funcionamento previsto para os elementos de interação. | 1,0 / 1,5 |
| C3 — CSS e identidade visual | Falha no carregamento da folha de estilos principal, registrada entre os erros do console. | Os estilos definidos no arquivo principal não são aplicados. | 0,0 / 1,5 |

### 7.2. Apuração da pontuação

**Pontuação final = C1 + C2 + C3**

**1,5 + 1,0 + 0,0 = 2,5 pontos.**

Cada pontuação respeita o limite do respectivo critério. A falha de carregamento das imagens foi considerada apenas em C1, evitando desconto duplicado pela mesma ocorrência.

**Pontuação final obtida: 2,5 / 5,0 pontos.**

### 7.3. Parecer descritivo

O projeto **NutriViva**, desenvolvido por **Lucas R. e Davi**, obteve **2,5 pontos de um total de 5,0 pontos**. As ocorrências registradas foram o carregamento incorreto das imagens, a ausência de funcionamento dos botões e a falha no carregamento da folha de estilos principal.

As correções devem contemplar a verificação dos arquivos e de suas referências, o funcionamento das ações previstas nos botões e o restabelecimento da aplicação do CSS. Após os ajustes, é necessário conferir a apresentação da página e testar os elementos de navegação e interação.

O dimensionamento do menu e os demais aspectos decorrentes exclusivamente da responsividade não integraram a penalização, considerando que esse conteúdo ainda não havia sido apresentado à turma.

---

**Docente responsável:** Breno Antonio Kunsch  
**Data da avaliação:** 19/10/2026
