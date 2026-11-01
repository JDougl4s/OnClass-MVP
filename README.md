[readme_md.md](https://github.com/user-attachments/files/34239253/readme_md.md)
# 📱 ONClass - MVP (Controle de Presença Inteligente)

> **Transformando o controle de presença em uma barreira intransponível contra fraudes acadêmicas.**

Este repositório contém o **MVP (Produto Mínimo Viável)** do projeto ONClass, desenvolvido como Prova de Conceito (PoC) para a disciplina de Projeto Integrador do curso de Análise e Desenvolvimento de Sistemas (Faculdade INBEC).

## 🎯 O Problema

Sistemas tradicionais de presença baseados em links estáticos ou QR Codes impressos são frágeis e facilmente burláveis no ambiente acadêmico (gerando um risco de até 40% de fraude).

* Compartilhamento livre de links em grupos de mensagens.

* Presenças fraudulentas assinadas remotamente.

* Total ausência de comprovação física ou geográfica real do aluno.

## 💡 A Solução (Funcionalidades do MVP)

O ONClass restaura a integridade das métricas de comparecimento através de um sistema de validação em múltiplas camadas:

* ⏱️ **O Ciclo dos 10 Segundos (QR Code Dinâmico):** O código projetado em sala expira e regenera-se automaticamente a cada 10 segundos. Imagens fotográficas ou capturas de tela enviadas por WhatsApp tornam-se completamente inválidas logo após o registro.

* 👨‍🏫 **Painel do Docente:** Gerador dinâmico de chamadas, controle total da sessão em tempo real e registro auditável (logs de IP e hashes).

* 🎓 **Portal do Estudante:** Autenticação segura cruzando dados de matrícula para garantir a identidade de quem registra a presença.

## 🚀 Como este MVP foi construído (Validação Ágil com IA)

Para validar a ideia, a regra de negócio dos 10 segundos e a mecânica de funcionamento rapidamente, este MVP foi construído com forte utilização de **Inteligência Artificial Generativa (Gemini e ChatGPT)**.

Atuei na **orquestração e engenharia de prompts** para arquitetar e gerar a aplicação utilizando a seguinte stack de prototipação:

* **Front-end:** React e Tailwind CSS (para uma interface visual limpa e responsiva).

* **Back-end e Banco de Dados:** Express (Node.js) e Supabase (para validação rápida da lógica de hashes e tokens em tempo real).

*Nota: Estas tecnologias foram utilizadas exclusivamente para a validação rápida da Prova de Conceito (PoC), com foco em visão de produto e entrega de valor.*

## 🎥 Demonstração Prática

Assista ao vídeo abaixo para observar a regra de negócio principal em ação:

[![Demonstração do MVP ONClass](https://img.youtube.com/vi/5PrMSyF7QGU/0.jpg)](https://youtu.be/5PrMSyF7QGU)

*(Clique na imagem acima para assistir à demonstração no YouTube)*

No vídeo, é possível conferir:

1. O professor inicia a chamada e o sistema gera o QR Code com o hash dinâmico.

2. O aluno insere o token válido dentro da janela de 10 segundos ➡️ **Sucesso! Presença confirmada.**

3. O aluno tenta utilizar um token após a renovação do cronômetro ➡️ **Falha na Validação: Token expirado.**

## 🔄 Próximos Passos (Roadmap da Equipe)

A fase de validação individual do MVP foi concluída com sucesso.

**Status atual:** O projeto entrará agora em fase de **reestruturação arquitetural**. Juntamente com a equipe do Projeto Integrador, iremos refatorar o sistema e definir a stack definitiva (com foco em robustez, escalabilidade e back-end estruturado) para a entrega final da disciplina.

### 👥 Equipe do Projeto

* Brena Carvalho

* Emily Oliveira

* João Douglas

*Projeto acadêmico desenvolvido para fins de estudo e validação de software.*
