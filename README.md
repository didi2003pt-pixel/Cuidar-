# Cuidar+ Família

**Cuidar+ Família** é uma aplicação mobile-first/PWA focada na coordenação familiar de cuidados a pessoas idosas ou dependentes em Portugal.

A app não pretende substituir médicos, o SNS 24, o 112 ou qualquer profissional de saúde. O objetivo é resolver um problema prático: ajudar famílias a organizar medicação, consultas, documentos, sintomas, tarefas e responsabilidades sem depender de grupos de WhatsApp confusos, papéis perdidos ou chamadas constantes.

## Objetivo

Criar um centro de comando simples para famílias que cuidam de pais idosos ou pessoas dependentes.

A proposta central é:

> O SNS organiza a relação do utente com o sistema de saúde.  
> Cuidar+ Família organiza a vida da família à volta dos cuidados.

## Funcionalidades do MVP

- Dashboard diário com estado geral da pessoa cuidada
- Perfil da pessoa cuidada
- Plano de medicação com confirmação de toma
- Histórico simples de medicação
- Alertas visuais para medicação pendente
- Calendário de consultas e exames
- Checklist pré-consulta
- Pasta digital de documentos
- Gestão de familiares e permissões
- Tarefas atribuídas por familiar
- Registo rápido de sintomas e eventos
- Botão de emergência familiar
- Interface mobile-first
- Suporte PWA básico com manifest e service worker

## Ecrãs incluídos

- Onboarding
- Hoje
- Medicação
- Calendário
- Documentos
- Família
- Sintomas
- Emergência

## Diferenciação

Esta app não é uma app médica nem uma app “para idosos”.  
É uma app para a família que cuida.

O idoso pode interagir, no futuro, através de mecanismos simples como SMS, WhatsApp, chamada, link de confirmação ou uma interface extremamente simplificada.

## Tecnologias

- HTML
- CSS
- JavaScript
- Progressive Web App
- Service Worker
- Manifest Web App

## Estado do projeto

Protótipo funcional estático com dados simulados.

Este MVP serve para validar:

- se famílias percebem o valor em menos de 5 minutos;
- se a confirmação de medicação é útil;
- se o dashboard diário reduz ansiedade;
- se a gestão de tarefas evita confusão familiar;
- se existe disposição para pagar por coordenação familiar de cuidados.

## Roadmap

### Fase 1 — MVP

- Dashboard familiar
- Medicação com confirmação
- Calendário de saúde
- Documentos
- Família e permissões
- Sintomas simples
- Emergência básica

### Fase 2

- Backend real
- Autenticação
- Base de dados
- Upload seguro de documentos
- Notificações push
- SMS/WhatsApp
- Relatórios PDF
- Gestão de cuidadores

### Fase 3

- Integração com farmácias
- Integração com clínicas/cuidados domiciliários
- Planos B2B
- Resumos administrativos com IA
- Voz
- Wearables

## Aviso importante

A Cuidar+ Família não diagnostica, não prescreve, não recomenda alterações de medicação e não substitui acompanhamento médico, SNS 24 ou 112.

Qualquer informação introduzida na app deve ser validada pela família, cuidadores ou profissionais de saúde competentes.

## Como correr localmente

```bash
python3 -m http.server 8080
