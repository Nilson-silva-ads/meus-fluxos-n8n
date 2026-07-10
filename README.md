# 🤖 Meus Fluxos e Automações - n8n

Este repositório contém uma coleção de fluxos de automação de processos desenvolvidos na plataforma **n8n**. O objetivo principal é centralizar a lógica das automações, manter um histórico de versões e servir como portfólio técnico.

## 🚀 Como funciona o backup?
Os arquivos `.json` deste repositório são atualizados de forma **100% automatizada**. Desenvolvi um fluxo interno no n8n que roda diariamente (via Cron/Schedule Trigger), busca todos os fluxos ativos na minha instância local e realiza o commit/push direto para cá utilizando a API do GitHub.

---

## 📂 Automações Inclusas

### 1. Sistema de Triagem e Processo Seletivo (RH)
* **Descrição:** Automatiza a captação de candidatos, validação de dados e envio de e-mails de confirmação.
* **Ferramentas Integradas:** n8n, Formulários Web, E-mail.
* **Principais recursos utilizados:** Nós de decisão (If), manipulação de JSON e chaves de API.

*(Dica: se quiser, você pode adicionar outros projetos aqui na lista, como bots de WhatsApp, integração com planilhas, etc.)*

---

## 🛠️ Como replicar um fluxo no seu n8n
Caso queira testar ou utilizar qualquer um dos fluxos salvos aqui:
1. Abra o arquivo `.json` do fluxo desejado aqui no GitHub e copie todo o código.
2. Acesse a sua instância do n8n.
3. Crie um novo fluxo vazio.
4. Utilize o atalho `Ctrl + V` (ou clique no menu de 3 pontinhos no canto superior direito e selecione **Import from File/Paste**).
5. **Atenção:** Será necessário configurar as suas próprias credenciais (chaves de API, logins) nos nós, pois por motivos de segurança, o n8n não exporta dados sensíveis.

---
Desenvolvido com 💜 focado em engenharia de processos e eficiência.
