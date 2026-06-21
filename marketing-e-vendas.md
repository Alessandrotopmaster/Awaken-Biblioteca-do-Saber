# Estratégia Comercial Unificada do Ecossistema
## Funil Baseado em Retenção, Remarketing Circular e Cadastro Único (SSO)

O fluxo de vendas da **Flow Business** cruza o comportamento de consumo de vídeo do usuário para automatizar ofertas contextuais da Awaken, Biosoul ou e-commerces integrados (Amazon, Shopee e Mercado Livre).

---

## 🛤️ O Funil de Vendas Interconectado

1. **Atração (Feed Vertical):** O usuário assiste a vídeos verticais criados por afiliados consumindo produtos ou demonstrando truques de sua profissão.
2. **Conversão (Dois Cliques):** Links dinâmicos anexados aos vídeos direcionam para checkouts rápidos de infoprodutos da Awaken, produtos próprios Biosoul ou links de afiliados dos grandes e-commerces.
3. **Automação de Réguas de Comunicação (Sandro Rhilmanelly):**
   * *Gatilho Estresse/Noturno:* Usuários com alto consumo de tela tarde da noite recebem e-mails sobre saúde mental ➔ Direcionamento para *Biosoul Equilíbrio Natural*.
   * *Gatilho Produtividade:* Foco em vídeos operacionais e métricas de negócios aciona e-mails de aceleração ➔ Direcionamento para e-books *Awaken* e suplementos *Energies*.

---

## 🎯 Remarketing e Tráfego Pago Circular
As campanhas pagas atuam de forma circular usando o pixel e as APIs de conversão integradas:
* **Público de Retenção:** Usuários que assistiram a mais de 75% de vídeos sobre um tema recebem anúncios direcionados da solução educacional correspondente.
* **Público de Carrinho Abandonado:** Checkouts não finalizados geram remarketing dinâmico imediato nas redes sociais, utilizando criativos de alta qualidade visual e aspecto cinematográfico.

---

## 🛠️ Engenharia de Cadastro Único (Single Sign-On)
O ecossistema elimina as barreiras de conversão centralizando o perfil do usuário:
* A mesma conta usada para consumir conteúdo acessa as aulas adquiridas e gerencia a carteira de afiliados.
* O afiliado monitora os ganhos da Biosoul, Awaken, Amazon, Shopee e Mercado Livre em uma única tela.
* Dados de faturamento e entrega salvos no perfil eliminam passos redundantes no checkout.

---

### 💻 TRECHO DE CÓDIGO 1: Estrutura do Usuário Unificado no Ecossistema (JSON)
```json
{
  "usuarioId": "flow_usr_99823",
  "nome": "Cliente Exemplo",
  "perfilAtivo": { "assistindoVideos": true, "afiliadoAtivo": true },
  "carteiraComissoes": { "saldoBiosoul": 1500.00, "saldoAwaken": 850.00, "saldoMarketplaces": 3400.00 },
  "produtosAdquiridos": { "awakenEbooks": ["eletrica_01"], "biosoulAtivos": ["caps_energy_focus"] }
}
