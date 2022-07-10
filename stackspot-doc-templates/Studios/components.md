---
title: Componentes [Opcional]
description: Este documento é um modelo para documentar componentes.
weight: 4
---

[Esta é uma seção opcional: se sua stack criou componentes, então é necessário preencher este template.]


## **Nome do componente**
Insira um resumo do componente. Responda às perguntas: o que ele faz e como funciona.

Sugerimos um texto para você iniciar:

O **componente xx** padroniza métricas das aplicações Prometheus.


### **Como o **componente xx** funciona?**
Explique como esse componente funciona e adicione imagens da arquitetura para facilitar a compreensão, se aplicável.

O componente xxx funciona por meio de xxx.  
Veja o diagrama abaixo:

![](Adicione imagens/gifs/diagramas)

## **Uso**
### **Pré-requisitos**
Adicione os pré-requisitos que a pessoa usuária precisa ter antes de utilizar o componente.

Para utilizar esse componente, é necessário:
- [**GitHub**](www.github.com);

### **Versões**
- O componente xx oferece suporte apenas para aplicativos com a **versão net5.0**.

### **Como usar?**
Siga os passos abaixo para utilizar o componente:

**Passo 1.** Adicione o pacote [**NuGet StackSpot.Metrics**](https://www.nuget.org/packages/StackSpot.Metrics) ao seu projeto:

dotnet add xxxxxx

**Passo 2.** Adicione ao seu [**IServiceCollection**] via **services.ConfigureMetrics()** no Startup da aplicação:  

services xxxxxx