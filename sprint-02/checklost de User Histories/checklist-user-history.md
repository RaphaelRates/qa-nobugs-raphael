# 📋 Checklist de Validação para Histórias de Usuário

Checklist baseada na metodologia **INVEST** e **Example Mapping** para validação de histórias de usuário em processos ágeis.

---

## 📌 Seção 1 – Validação do Formato INVEST

### ✅ Independente
- [ ] A história é independente (não depende de outras para existir)?
- [ ] Pode ser priorizada ou planejada de forma isolada, sem comprometer outras histórias?
- [ ] Se for removida da sprint, outras histórias continuam coerentes e viáveis?
- [ ] A história depende de alguma funcionalidade anterior para funcionar corretamente?

### ✅ Negociável
- [ ] O escopo desta história está aberto a diálogo e adaptação, ou está sendo tratado como uma exigência fechada?
- [ ] O time compreende os limites e flexibilidades da proposta?
- [ ] Há espaço para questionamento de premissas, caso algo se mostre tecnicamente inviável ou ineficaz para o usuário?

### ✅ Valor
- [ ] O resultado desta história gera impacto mensurável ou perceptível para o usuário final?
- [ ] Atende diretamente a alguma meta de negócio, como aumento de conversão, satisfação, retenção ou eficiência?
- [ ] Caso esta funcionalidade não fosse entregue, alguém sentiria falta dela?

### ✅ Estimável
- [ ] O time técnico consegue estimar a complexidade ou o esforço com razoável confiança?
- [ ] Há informações suficientes para embasar a estimativa (por exemplo, regras, fluxos, dados de entrada e saída)?
- [ ] Se não é estimável, o que está impedindo isso? Conceito mal definido? Termos ambíguos? Falta de exemplos?

### ✅ Pequena
- [ ] Esta história pode ser implementada, testada e validada dentro de uma única iteração (sprint)?
- [ ] Existe apenas um objetivo funcional principal, ou a história está tentando resolver múltiplos problemas ao mesmo tempo?
- [ ] A funcionalidade pode ser dividida em partes menores sem perder valor de negócio?

### ✅ Testável
- [ ] Existe ao menos um cenário positivo e um cenário negativo que definem se a história será considerada “pronta”?
- [ ] Esta funcionalidade pode ser automatizada em testes de aceitação ou integração?
- [ ] Os resultados esperados são mensuráveis ou estão vagos (“algo mais rápido”, “melhor aparência”)?

---

## 🟨 Seção 2 – Definição da História de Usuário (Cartões Amarelos)

- [ ] A formulação segue a estrutura consagrada da história de usuário?  
    - "Como [persona], quero [intenção/ação], para que [objetivo/valor alcançado]"
- [ ] Essa estrutura assegura clareza de papel, desejo funcional e propósito de valor?
- [ ] A história explicita o valor de negócio ou a transformação desejada na experiência do usuário?
- [ ] A narrativa está livre de termos técnicos excessivos ou ambíguos que possam comprometer o entendimento interdisciplinar?
- [ ] A persona descrita é realista, contextualizada e representativa do público-alvo?
- [ ] Há variações da história mapeadas para diferentes fluxos, exceções ou papéis de usuário?
- [ ] A ação descrita é singular e focalizada, ou a história tenta encapsular múltiplas funcionalidades simultaneamente?
- [ ] Existe alinhamento entre o comportamento descrito e os objetivos estratégicos do produto ou serviço?
- [ ] A linguagem utilizada está no tempo presente e evita condicionalidades ambíguas?
- [ ] A história representa um incremento real de valor ou é apenas uma etapa intermediária de implementação?
- [ ] A formulação permite inferir claramente quais comportamentos ou critérios serão validados com testes?
- [ ] A história está centrada no valor de negócio ou necessidade do usuário?
- [ ] Há variações da história, se necessário, para diferentes contextos de uso?

---

## 📘 Seção 3 – Definição de Regras de Negócio (Cartões Azuis)

- [ ] As regras explícitas estão descritas de forma clara?
- [ ] Há validações de entrada definidas (ex: campos obrigatórios, formatos, senhas)?
- [ ] Existem restrições ou limites de uso bem especificados?
- [ ] Regras de segurança e autenticação foram consideradas?
- [ ] A unicidade de dados foi validada? (ex: IDs únicos, e-mails não duplicados)
- [ ] Há menção a fluxos de moderação, aprovação ou rejeição?

---

## 📗 Seção 4 – Exemplos Concretos (Cartões Verdes)

Para cada regra de negócio:

- [ ] Existe pelo menos um exemplo positivo (fluxo ideal)?
- [ ] Existe pelo menos um exemplo negativo (fluxo alternativo ou erro)?
- [ ] Os exemplos seguem a estrutura:  
    - **Contexto** (estado inicial do usuário ou do sistema)  
    - **Ação do Usuário** (interação que ele realiza)  
    - **Resultado Esperado** (resposta do sistema)?
- [ ] Os exemplos ajudam a esclarecer ambiguidades da história?
- [ ] Os exemplos são realistas e testáveis?

---

## 📕 Seção 5 – Identificação de Dúvidas ou Riscos (Cartões Vermelhos)

- [ ] Há perguntas em aberto que devem ser esclarecidas com stakeholders?
- [ ] Há regras mal definidas, ambíguas ou ausentes?
- [ ] Existem riscos técnicos, legais ou operacionais associados à história?
- [ ] Foi registrado tudo que possa intervir no andamento?

---

## 🧩 Seção 6 – Preparo para Discussão com os “3 Amigos”

- [ ] **🧠 P.O. (negócio)**: a história entrega valor?
- [ ] **🛠️ Dev (técnico)**: é viável e clara para implementar?
- [ ] **🧪 Tester (validação)**: pode ser verificada com testes?
- [ ] A história está pronta para ser discutida em uma sessão de 30 minutos, se necessário?

---

## 🛠️ Seção 7 – Prontidão para Desenvolvimento

- [ ] Todos os cartões estão definidos: amarelos, azuis, verdes e vermelhos?
- [ ] Os critérios de aceitação podem ser derivados diretamente dos exemplos?
- [ ] Há testes automatizáveis claramente deriváveis dos exemplos?
- [ ] A história está pronta para ser movida para a próxima sprint ou iteração?

---
