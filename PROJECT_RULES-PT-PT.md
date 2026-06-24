# PROJECT_RULES.md

> Menos código. Mais impacto.

## Missão

Construir software simples, sustentável e fácil de evoluir.

O objetivo não é escrever mais código.

O objetivo é resolver problemas com a menor complexidade possível.

---

# Mentalidade

Antes de implementar qualquer solução:

* Entenda o problema.
* Entenda o contexto.
* Entenda as regras de negócio.
* Entenda a arquitetura existente.

Nunca comece codificando.

Comece entendendo.

---

# Ordem de Decisão

Antes de criar algo novo siga esta ordem:

1. Isso realmente precisa existir?
2. Já existe no projeto?
3. Posso reutilizar algo existente?
4. A linguagem já resolve?
5. O framework já resolve?
6. Uma dependência já resolve?
7. Dá para simplificar?
8. Só então implemente.

---

# Reutilização

Prefira sempre:

* Reutilizar
* Adaptar
* Estender

Antes de:

* Criar
* Duplicar
* Reescrever

---

# Dependências

Cada dependência adiciona:

* Custo
* Complexidade
* Risco
* Manutenção

Antes de instalar uma dependência pergunte:

> Posso resolver isso sem ela?

---

# YAGNI

You Aren't Gonna Need It.

Não implemente:

* Funcionalidades futuras
* Abstrações especulativas
* Sistemas genéricos sem necessidade real
* Otimizações prematuras

Construa apenas o necessário.

---

# KISS

Keep It Simple.

Prefira:

* Código explícito
* Fluxos simples
* Estruturas pequenas
* Componentes previsíveis

Evite:

* Camadas desnecessárias
* Abstrações excessivas
* Complexidade acidental

---

# Funções

Toda função deve:

* Ter uma responsabilidade clara
* Ser fácil de entender
* Ser fácil de testar

Se estiver difícil de explicar, provavelmente está complexa demais.

---

# Nomenclatura

Nomes devem revelar intenção.

Ruim:

```js
a()
b()
data2()
```

Bom:

```js
calculateInvoice()
getUserProfile()
sendNotification()
```

---

# Comentários

Não explique código óbvio.

Comente apenas:

* Regras de negócio
* Decisões arquiteturais
* Restrições importantes
* Workarounds temporários

---

# Segurança

Nunca confie na entrada do usuário.

Valide sempre:

* Inputs
* APIs
* Arquivos
* Parâmetros
* Dados externos

Segurança não é opcional.

---

# Acessibilidade

Toda interface deve considerar:

* Navegação por teclado
* Leitores de tela
* Contraste adequado
* Labels corretos

Acessibilidade faz parte da qualidade.

---

# Performance

Não otimize por suposição.

Primeiro:

* Meça
* Identifique gargalos
* Comprove o problema

Depois:

* Otimize

---

# Banco de Dados

Antes de criar:

* Tabelas
* Colunas
* Índices

Verifique se algo existente pode ser reutilizado.

Evite duplicação.

---

# APIs

APIs devem ser:

* Consistentes
* Previsíveis
* Versionáveis
* Bem documentadas

Não quebre consumidores sem motivo.

---

# Testes

Valide:

* Fluxo principal
* Casos de erro
* Casos extremos
* Regras de negócio

Não assuma que funciona.

Verifique.

---

# Documentação

Toda mudança relevante deve explicar:

* O problema
* A solução
* O impacto
* Dependências adicionadas
* Mudanças arquiteturais

---

# Checklist Antes de Codificar

* Entendi o problema?
* Entendi o contexto?
* Entendi a arquitetura?
* Isso realmente precisa existir?
* Já existe algo semelhante?
* Posso reutilizar?
* Posso simplificar?
* Posso evitar dependências?

Se alguma resposta for "não sei":

Pare.

Investigue primeiro.

---

# Checklist Antes de Finalizar

* Resolve o problema?
* Está simples?
* Está legível?
* Está seguro?
* Está acessível?
* Está documentado?
* Está fácil de manter?

---

# Regra de Ouro

A melhor solução não é a que usa menos linhas.

A melhor solução é a mais simples que resolve o problema corretamente e continua fácil de manter daqui a um ano.

---

# Pergunta Final

Se você remover metade deste código, o sistema continua funcionando?

Se sim, considere remover.
