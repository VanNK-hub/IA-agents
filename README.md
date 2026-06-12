Agente de Vendas Inteligente - Reativação B2B

Visão Geral
O Agente de Vendas Inteligente é uma solução autônoma de IA projetada para otimizar o ciclo de vida do cliente B2B. O sistema identifica proativamente lojistas inativos em bases de dados legadas, orquestra abordagens personalizadas via WhatsApp e negocia benefícios exclusivos (como programas de Cashback) para reativar parcerias comerciais de forma escalável.

Funcionalidades Principais

* Triagem Inteligente: Algoritmos de análise de dados que segmentam clientes inativos com base em recência, frequência e valor monetário (RFM).
* Abordagem Humanizada: Utilização de LLMs avançadas para manter conversas contextuais, empáticas e alinhadas ao tom de voz da marca.
* Integração Dinâmica: Conexão em tempo real com catálogos de produtos via API para oferecer recomendações baseadas no histórico de compras do lojista.
* Transbordo Estratégico: Sistema de detecção de intenção de compra que realiza o handoff automático para a equipe de vendas humana quando o lead atinge o estágio de conversão.

Stack Tecnológico

* Orquestração de Fluxo: Botpress / Typebot
* Processamento de Linguagem Natural: GPT-4 (OpenAI API)
* Integração de Dados: RESTful APIs (Node.js/Python middleware)
* Infraestrutura: Cloud-native (AWS/GCP)

Guia de Configuração

1. System Prompt
Configure o comportamento do agente no painel do Botpress/Typebot utilizando a seguinte diretriz:
"Você é um consultor de vendas B2B especializado em reativação de parcerias. Seu objetivo é ser cordial, direto e focado em benefícios. Utilize o histórico de compras fornecido para personalizar a oferta de Cashback."

2. Variáveis de Ambiente
Certifique-se de configurar as seguintes chaves no seu arquivo .env ou nas configurações do projeto:
- OPENAI_API_KEY: Chave de acesso à API da OpenAI.
- CRM_API_ENDPOINT: URL do seu banco de dados de clientes.
- WHATSAPP_WEBHOOK_URL: Endpoint para recebimento de mensagens.

Contribuição
Este projeto é mantido para fins de demonstração técnica. Pull requests são bem-vindos para melhorias em prompts de sistema e otimização de latência de API.
