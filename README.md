# Projeto_DIO_Multiple_Esclerosis
Projeto final para certificação DP-100 Microsoft Azure pela DIO

# 🧠 Assistente de Análise de Artigos: EMRR
## 📋 Descrição do Projeto
Este projeto foi desenvolvido como parte de um desafio da DIO (Digital Innovation One). O objetivo é criar um chatbot inteligente que utiliza a técnica de RAG (Retrieval-Augmented Generation) para responder perguntas baseadas em documentos específicos (PDFs).

Para este laboratório, utilizei artigos científicos sobre Esclerose Múltipla Remitente-Recorrente (EMRR). A escolha do tema é pessoal e motivada pelo diagnóstico do meu filho caçula, visando facilitar a correlação de informações entre diferentes textos médicos e acadêmicos.

## 🛠️ Tecnologias e Conceitos
Azure AI Foundry: Plataforma utilizada para gerenciar o projeto e os modelos de IA.
IA Generativa: Motor para criação de respostas contextuais e naturais.
Busca Vetorial (Embeddings): Técnica fundamental para indexar os PDFs e permitir que o sistema recupere as informações mais relevantes de forma eficiente.

## 🚀 Processo de Desenvolvimento

Curadoria de Conteúdo: Coleta de PDFs e artigos recentes sobre tratamentos e diagnósticos de EMRR.
Configuração de Infraestrutura: Criação de recursos no Azure (contornando restrições de região da assinatura Azure for Students).
Vetorização: Processamento dos documentos para transformar texto em dados numéricos (vetores).
Integração: Conexão do modelo de linguagem (ex: GPT-4o) à base de dados proprietária para gerar respostas fundamentadas.

## 💡 Insights e Aprendizados

RAG vs Conhecimento Geral: Diferente de um chat comum, o sistema aqui não "alucina" tanto, pois suas respostas estão presas ao que dizem os artigos carregados.
Estruturas de Dados na Prática: Pude observar como a busca por similaridade em espaços vetoriais é aplicada na vida real, um conceito que levarei para minhas aulas de Engenharia de Software.
Impacto Social: A tecnologia de IA pode ser uma aliada poderosa para famílias que lidam com condições crônicas, ajudando a sintetizar montanhas de informações complexas.
