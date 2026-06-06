# Análise Baseada em Eventos  
## Avaliação do Impacto da Mudança de Fonte no Comportamento dos Usuários

## Objetivo do Projeto
O objetivo deste projeto é avaliar se uma alteração visual simples — a mudança da fonte utilizada no aplicativo — produz impacto mensurável no comportamento dos usuários.  
A análise foi conduzida utilizando dados de eventos, funis de conversão e testes estatísticos A/A e A/B.

---

## Estrutura do Experimento
O experimento envolveu três grupos:

- **Grupo 246 (Controle A)**
- **Grupo 247 (Controle A)**
- **Grupo 248 (Experimental B)** — recebeu a nova fonte

A análise foi dividida em duas etapas:

1. **Teste A/A** → validar se os grupos de controle são estatisticamente idênticos  
2. **Teste A/B** → comparar o grupo experimental com os controles

---

## Análise do Funil de Conversão

A análise do funil revelou:

- A maior perda ocorre **logo na entrada**, entre a tela inicial e a tela de ofertas  
- **38% dos usuários abandonam o fluxo nessa etapa**
- As etapas seguintes apresentam **taxas de conversão muito altas**
- Isso indica que, **uma vez que o usuário se engaja**, o fluxo funciona bem

**Conclusão do funil:**  
O principal ponto de melhoria está na **tela inicial**, não na etapa de compra.

---

## Teste A/A — Validação dos Grupos de Controle

O teste A/A comparou os grupos **246** e **247**.

**Resultado:**  
- Os grupos são **estatisticamente idênticos** em todos os eventos  
- Não há diferenças significativas em navegação, engajamento ou conversão  
- A aleatorização foi bem-sucedida  
- O experimento **não sofre de viés estrutural**

Isso valida a integridade do experimento.

---

## Teste A/B — Avaliação da Mudança de Fonte

O grupo experimental **248** foi comparado:

- Individualmente com cada grupo de controle  
- Com os controles combinados (246 + 247)

**Resultado:**  
- Todos os p‑valores ficaram **muito acima** dos níveis usuais de significância  
- Nenhuma métrica apresentou diferença estatística  
- Nenhum evento mostrou tendência de impacto  
- Mesmo com muitos testes, **nenhum resultado se aproximou de significância**

**Conclusão:**  
A mudança de fonte **não influenciou**:

- Navegação  
- Engajamento  
- Conversão  
- Comportamento geral dos usuários  

A alteração estética é **totalmente neutra**.

---

## Conclusão Geral do Projeto

O comportamento dos usuários é **estável**, e a mudança visual testada **não produziu impacto mensurável**.  
O funil mostra que:

- A maior queda ocorre na **tela inicial**  
- O restante do fluxo funciona muito bem  
- Melhorias devem se concentrar no **início da jornada**

O experimento é robusto, bem estruturado e estatisticamente válido.

---

## Recomendações

### **1. Não implementar a mudança de fonte como melhoria**
Ela não altera o comportamento dos usuários.

### **2. Focar na tela inicial**
É onde ocorre a maior perda (38%).  
Possíveis ações:
- Testes de layout  
- Clareza da proposta de valor  
- Redução de fricção inicial  

### **3. Manter o processo de experimentação**
O teste A/A mostrou que o sistema de aleatorização funciona perfeitamente.

### **4. Priorizar testes com maior potencial de impacto**
Mudanças estéticas simples raramente alteram comportamento.  
Priorizar:
- Conteúdo  
- Ofertas  
- Estrutura do fluxo  
- Incentivos iniciais  

---

## Tecnologias Utilizadas
- Python  
- Pandas / NumPy  
- Estatística (z-test de proporções)  
- Análise de eventos  
- Jupyter Notebook  

---

## Estrutura do Repositório
