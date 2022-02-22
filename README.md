# Kubernetes-KEDA-AzureEventHubs-DotNet6_VotacaoTecnologias
Objetos para Deployment de um Worker Service (processamento de votos sobre tecnologias) no Kubernetes utilizando KEDA, Helm, Azure Event Hubs e .NET 6.

Worker Service para consumo de **eventos do Azure Event Hubs** (imagem **renatogroffe/workerquestaoeventhub-dotnet6**) - é justamente esta aplicação que será escalada via **KEDA**:

**https://github.com/renatogroffe/DotNet6-Worker-AzureEventHubs-SqlServer-Dapper-Processor_Questoes**

Projeto que serviu de base para o **envio de eventos ao Azure Event Hubs** (imagem **renatogroffe/sitequestaoeventhub-dotnet6**):

**https://github.com/renatogroffe/ASPNETCore6-MVC-AzureEventHubs_SiteQuestao**

No arquivo **keda-instalacao&sdot;sh** estão as instruções para instalação do KEDA **(Kubernetes Event-driven Autoscaling)** em um **cluster Kubernetes**.
