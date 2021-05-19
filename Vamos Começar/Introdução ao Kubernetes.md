# O que é Kubernetes e porque nós queremos isso?

## Recurso dos 100Dias

- [Vídeo a Anais Urlichs](https://www.youtube.com/watch?v=fCpv7xSEyEI)
- Adicione seus posts, videos etc relacionados a este tópico aqui!

## Recursos de Aprendizagem

Aqui vou colocar referências em português, caso queira as referências originais em inglês é só acessar o [site oficial](https://100daysofkubernetes.io/start/intro-to-k8s.html#learning-resources) do desafio. 

- [O que é Kubernetes](https://www.youtube.com/watch?v=mVL0nOM3AGo)
- [Arquitetura do Kubernetes](https://www.youtube.com/watch?v=bPFxwwSfSmk)
- [Orquestração de Containers](https://www.youtube.com/watch?v=fH_yuV2bm9E)

## Notas de Exemplo

<p>O Kubernetes é baseado no Borg e nas lições aprendidas pelo Google na operação dele por mais de 15 anos.</p>

<p>O Borg era utilizado pelo Google internamente para gerenciar sistemas.</p>

**O que é Kubernetes?**

<p>Kubernetes é um Framework de Orquestração de Containers de código aberto.</p>

<p>Na sua raiz, ele gerencia containers - para gerenciar aplicações que são feitas de containers - máquinas físicas, máquinas virtuais, ambientes hibridos...</p>

De acordo com o [kubernetes.io](https://kubernetes.io/), seu site oficial, o Kubernetes é:
</br>
<i>"Um sistema de código aberto para automatizar o desenvolvimento, dimencionamento, e gerenciamento de aplicações containerizadas."</i>

**Quais problemas ele resolve**
- Seguindo a tendência de Monolithic to Microservices (De monolítico para microserviços) - tradicionalmente, uma aplicação seria uma aplicação monolítica - que requer que o hardware (equipamento/parte física do sistema) seja escalonado com a aplicação. Em comparação, o Kubernetes implementa um grande numero de pequenos web servers (servidores web).
- Containers são os hosts perfeitos para pequenas aplicações autônomas.
- Aplicações compostas por centenas de contêineres - gerenciar esses containers com scripts pode ser bastante difícil e até impossível. 
- O Kubernetes nos ajuda com os seguintes pontos: conectar containers com multiplos hosts, escalá-los, implementar aplicações sem downtime (queda/tempo de inatividade), e descoberta de serviços, entre vários outros aspectos.

<p>Os benefícios de tranformar a sua aplicação monolítica em microsserviço, é que se torna muito mais fácil de manter. Por exemplo:</p>
<p>Ao invés de um grande servidor web Apache com vários deamons http  respondendo às requisições da página, lá poderiam ter vários servidores nginx, cada um respondendo.</p>
<p>Além disso, nos permite separar questões de interesse dentro da aplicação, ou seja, desacoplar a arquitetura com base nas responsabilidades.</p>
<p>Além do mais, o Kubernetes é uma parte essencial de:</p>

- Integração Contínua (CI)
- Entrega Contínua (CD)
