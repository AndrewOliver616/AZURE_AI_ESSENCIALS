# AZURE_AI_ESSENCIALS
Resumos e Anotações dos Projetos do Bootcamp

Resumo - Projeto Tradutor de Artigos Técnicos com AzureAI

*Antes transformar um texto em voz (áudio) é necessário traduzir e posteriormente usar a API REST para produzir voz.

Etapas: Detectar idioma -> Traduzir -> Transliterar, se for o caso.


Coding:

Resource Group: DIO - Translator

AI Services - Translator * Utilizar princing free (até 2 M caracteres)
Azure OpenAI

Custo do Translator Azure R$ 54,00 por milhão de caracteres excedentes, cota de 2 milhões free.
Custo Open GPT-4o-MINI R$ 5,00 por 1 milhão de tokens (cada token tem 4 caracteres entrada/saída)

Camada de recursos

No Colab - Importar requests e docx Document

Subscription_key: Chave do recurso do Azure
Endpoint do Translator:
Location: Posição do Data center (EASTUS)
Target_language:'pt-b'
Headers da requisição
