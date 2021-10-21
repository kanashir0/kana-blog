---
date: 2021-10-20 22:30:00
layout: post
categories: GCP Workflows Cloud

title: "Guia inicial sobre o Cloud Workflows"
---

Neste artigo você vai descobrir o que é o Cloud Workflows, como criar seu primeiro workflow com ele, e também aprender alguns conceitos básicos. Então bora lá!

# Sumário
* Introdução
* Conceitos básicos
* Cloud Composer vs Cloud Workflows
* Meu primeiro workflow
* O que mais posso fazer?
* Exemplos de casos de uso
* Preços

# Introdução

De uma forma bem simples e direta, o Cloud Workflows é uma ferramenta **totalmente gerenciada** e **_serverless_** (sem servidor), que te permite conectar "coisas". Mas que tipo de coisas? Praticamente tudo que possua uma API pública. Você pode conectar várias funções hospedadas em Cloud Functions, ou então misturar elas com serviços que rodam no Cloud Run, APIs do GCP (Google Cloud Platform) ou até APIs externas (com ou sem autenticação).

# Conceitos básicos

Se você já é familiarizado com arquivos `JSON` ou `YAML`, vai se sentir em casa com o Workflows. Os pipelines são criados utilizando um desses dois tipos de arquivo. Neste artigo vamos usar o tipo `YAML` mas sinta-se a vontade para usar qual você preferir.












