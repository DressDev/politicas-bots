# **Política de Privacidade do Bot LojaPIX**

**Última atualização:** 17/08/2026

A sua privacidade é importante para nós. Esta Política de Privacidade explica como o bot **LojaPIX** ("nós", "nosso" ou "bot") coleta, usa, armazena e protege as suas informações quando você utiliza os nossos serviços dentro da plataforma Discord.

Ao adicionar e utilizar o LojaPIX em seu servidor, você concorda com as práticas descritas neste documento.

## **1\. Informações que Coletamos**

Para garantir o funcionamento correto do sistema de e-commerce automatizado, coletamos apenas os dados estritamente necessários. O bot coleta e armazena os seguintes dados:

### **1.1 Dados de Servidores (Guildas)**

* **ID e Nome do Servidor:** Para identificar onde o bot está operando e vincular catálogos e produtos.  
* **ID e Nome do Dono do Servidor (Owner):** Para vincular e gerenciar a assinatura premium do bot e enviar notificações administrativas.  
* **Configurações Locais:** Chaves PIX cadastradas pelos administradores (nome, chave e cidade do recebedor), IDs de canais (ex: canal de feedback) e IDs de cargos (ex: Cargo Cliente e Cargo Administrador).  
* **Catálogo e Estoque:** Dados dos produtos criados, descrições, preços e o conteúdo digital a ser entregue (entregáveis).

### **1.2 Dados de Usuários (Clientes)**

* **ID do Usuário:** Quando um usuário inicia um pedido, armazenamos seu ID do Discord para vincular a compra, criar a thread (carrinho de compras), enviar cobranças automáticas e entregar o produto via Mensagem Direta (DM).  
* **Metadados de Interação:** Registramos a data e hora em que um usuário enviou mensagens dentro de uma thread (carrinho) específica criada pelo bot, a fim de calcular inatividade e enviar lembretes de pagamento (sistema de "carrinho abandonado").

*Nota:* O bot **não** lê ou armazena o conteúdo das mensagens dos usuários enviadas no servidor, exceto para identificar a atividade dentro das threads exclusivas de pedidos para fins de suporte e lembrete.

## **2\. Como Usamos as Informações**

As informações coletadas são utilizadas exclusivamente para os seguintes propósitos:

* **Processamento de Pedidos:** Gerar cobranças via PIX Dinâmico/Estático e confirmar o pagamento.  
* **Entrega de Produtos:** Enviar o conteúdo digital (chaves, links, acessos) via Mensagens Diretas e aplicar automaticamente o "Cargo Cliente" configurado no servidor.  
* **Notificações e Lembretes:** Enviar mensagens automatizadas alertando sobre pedidos pendentes de pagamento ou status da assinatura do dono do servidor.  
* **Dashboard e Relatórios:** Gerar estatísticas de faturamento e taxas de conversão visíveis apenas para os administradores do servidor.

## **3\. Armazenamento e Retenção de Dados**

Nós valorizamos a segurança dos seus dados e os armazenamos localmente em um banco de dados restrito (data.json).

* **Retenção de Dados de Servidores Inativos:** Caso a assinatura premium do servidor expire e o servidor fique inativo por mais de **30 dias**, todos os dados do servidor (incluindo configurações, chaves PIX, histórico de pedidos e estoque de produtos) serão **automaticamente e permanentemente excluídos** do nosso banco de dados.  
* **Pedidos Cancelados/Concluídos:** Dados transitórios de lembretes são apagados imediatamente após o fechamento ou conclusão de um pedido. O histórico da transação é mantido apenas para o Dashboard do lojista.

## **4\. Compartilhamento de Dados**

**Nós não vendemos, alugamos ou compartilhamos seus dados com terceiros.** Todos os dados coletados são usados única e exclusivamente para o funcionamento interno do LojaPIX dentro do ecossistema do Discord. Nenhuma informação de clientes ou de estoque é repassada a outras plataformas.

## **5\. Seus Direitos e Controle**

Como usuário ou dono de servidor, você tem total controle sobre seus dados:

* **Exclusão de Dados (Dono do Servidor):** Você pode solicitar a remoção imediata de todos os dados da sua loja simplesmente removendo o bot do seu servidor e contatando nosso suporte, ou aguardando a exclusão automática após 30 dias do fim da assinatura.  
* **Exclusão de Dados (Cliente):** Clientes que desejam anonimizar seu histórico de compras devem entrar em contato com os administradores do respectivo servidor em que a compra foi realizada.  
* **Desativar Lembretes:** O usuário pode cancelar o pedido pendente a qualquer momento, o que encerrará automaticamente os alertas e lembretes de pagamento na thread.

## **6\. Mudanças nesta Política**

Podemos atualizar esta Política de Privacidade periodicamente para refletir novas funcionalidades do bot ou mudanças nas diretrizes do Discord. Notificaremos os donos de servidores através de nossos canais de comunicação (como o servidor de suporte) caso alterações significativas sejam feitas.

## **7\. Contato e Suporte**

Se você tiver dúvidas sobre esta Política de Privacidade, solicitações sobre seus dados, ou precisar de suporte técnico, entre em contato conosco através do nosso Servidor Oficial de Suporte no Discord:

**🔗 Link de Suporte:** [https://discord.gg/aMDzWmH](https://discord.gg/aMDzWmH)