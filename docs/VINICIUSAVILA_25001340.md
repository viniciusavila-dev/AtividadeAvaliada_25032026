# Avaliação — Engenharia de Software
**Sistema Integrado de Gestão de Farmácia — MVP Definido pelo Estudante**

Aluno: Vinícius Rosas de Ávila  
RA: 25001340  
Data: 25/03/2026  

---


# 1. Definição do MVP

Meu MVP cobre o processo de venda de produtos na farmácia desde a identificação do cliente até a emissão do comprovante, incluindo consulta de produtos, verificação de estoque, cadastro rápido de cliente, validação de receita para medicamentos controlados, registro de venda à vista ou a prazo e atualização automática do estoque.

- **Dentro do MVP**
- Identificar cliente
- Cadastrar cliente rapidamente
- Consultar produto
- Verificar estoque
- Registrar venda
- Validar receita médica quando necessário
- Finalizar venda
- Emitir comprovante
- Registrar contas a receber em vendas a prazo
- Atualizar estoque automaticamente após a venda

  
- **Fora do MVP**
- Processo completo de compras com fornecedores
- Transferência entre unidades
- Contas a pagar
- Relatórios gerenciais completos
- Gestão avançada de usuários e permissões
- Controle de perdas e devoluções
- Indicadores estratégicos da matriz




- Essas escolhas foram feitas porque o processo de venda é o mais crítico para o funcionamento diário da farmácia. Ele impacta diretamente o atendimento ao cliente, o controle de estoque e a geração de receitas. Assim, o MVP prioriza a operação principal do negócio e entrega valor imediato com menor complexidade de implementação.

---

# 2. Regras de Negócio (mínimo: 5)
Liste e descreva **cada RN** de forma clara.

**RN01 —** Produtos sem estoque disponível não podem ser vendidos.

**RN02 —** Medicamentos controlados só podem ser vendidos mediante validação de receita por um farmacêutico.

**RN03 —** Toda venda finalizada deve atualizar automaticamente o estoque da unidade.

**RN04 —** Vendas a prazo devem gerar automaticamente um lançamento em contas a receber com vencimento e status inicial “Aberta”.

**RN05 —** O sistema deve permitir cadastro rápido de cliente durante a venda quando ele ainda não estiver registrado.

**RN06 —** O comprovante da venda deve ser emitido obrigatoriamente ao final da operação.

**RN07 —** Apenas gerentes podem alterar cadastro de produtos e preços.

**RN08 —** O sistema deve alertar quando o estoque de um produto atingir ou ficar abaixo do nível mínimo.


---

# 3. Requisitos Funcionais (mínimo: 8)
Liste os requisitos funcionais do seu MVP.

**RF01 —** O sistema deve permitir identificar clientes pelo nome, CPF ou código.

**RF02 —** O sistema deve permitir cadastrar clientes durante o atendimento.

**RF03 —** O sistema deve permitir pesquisar produtos por nome, código de barras ou fabricante.

**RF04 —** O sistema deve verificar a disponibilidade de estoque antes de adicionar o produto à venda.

**RF05 —** O sistema deve registrar vendas com um ou mais itens.

**RF06 —** O sistema deve permitir classificar a venda como à vista ou a prazo.

**RF07 —** O sistema deve gerar automaticamente contas a receber em vendas a prazo.

**RF08 —** O sistema deve emitir comprovante ao final da venda.

**RF09 —** O sistema deve atualizar automaticamente o estoque após a conclusão da venda.

**RF10 —** O sistema deve solicitar validação de receita para medicamentos controlados.

---

# 4. Requisitos Não Funcionais (mínimo: 4)
Liste os RNFs do sistema conforme seu MVP.

**RNF01 —** O sistema deve responder às consultas de produtos em até 3 segundos.

**RNF02 —** O sistema deve garantir autenticação de usuários por login e senha.

**RNF03 —** O sistema deve manter registro das operações realizadas para auditoria.

**RNF04 —** O sistema deve estar disponível durante o horário de funcionamento da farmácia com alta confiabilidade.

**RNF05 —** O sistema deve possuir interface simples e intuitiva para uso no balcão.

(Adicione mais se quiser.)

---

# 5. Casos de Uso (mínimo: 10)
### Inserir **diagrama de casos de uso geral**, demonstrando claramente:
- os 10 casos
- relação entre eles e atores
- pelo menos 3 includes
- pelo menos 3 extends

---

# 6. Documentação dos Casos de Uso
Para **cada caso de uso**, utilize o template abaixo:
---

## **UCXX — Nome do Caso de Uso**
**Ator(es):**  
**Descrição:**  
**Pré-condições:**  
**Pós-condições:**  

### Fluxo Principal
1.  
2.  
3.  
4.  

### Fluxos Alternativos / Exceções
- FA01 —  
- FA02 —  

### Relacionamentos
- **Include:** (listar quando aplicável)  
- **Extend:** (listar quando aplicável)  

### Inserir o diagrama de atividades do Caso de Uso, demonstrando tudo o fluxo princial e alternativos/exceções.

---

> Repita essa estrutura para **todos os seus casos de uso** (mínimo 10).


