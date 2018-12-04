---
layout: post
title:  "¿Por qué estás fallando en microservicios?"
author: AdES
date:   2018-11-29 06:46
excerpt: "¿Te estás enfrentando a varios problemas debido a que cuando existe una falla no puedes identificar fácilmente su origen? En este artículo encontrarás una solución."
featured: true
external_image: true
image:  https://istio.io/docs/concepts/what-is-istio/arch.svg
---

Lograste migrar tu solución monolítica o implementaste una solución con una arquitectura distribuida de microservicios distribuida, pero ahora te estás enfrentando a varios problemas debido a que cuando existe una falla no puedes identificar fácilmente su origen. O tal vez encontraste una solución implementado lógica en tú código para monitorear y controlar los microservicios, pero cuando haces un cambio necesitas desplegar nuevamente todos tus microservicios.

Gracias al patrón de diseño "Sidecar", una arquitectura de [Service Mesh](https://www.nginx.com/blog/what-is-a-service-mesh/) te permitirá monitorear el tráfico, controlar el acceso entre microservicios, descubrir y asegurar tus microservicios, todo esto, sin necesidad de realizar cambios en el código. La arquitectura de **Service Mesh** habilita técnicas DevOps como despliegue [canary release](https://martinfowler.com/bliki/CanaryRelease.html), [circuit breaker](https://martinfowler.com/bliki/CircuitBreaker.html), inyección de fallas, entre otras.

Puedes probar con [AWS App Mesh](https://aws.amazon.com/es/app-mesh/) o si eres más intrépido  y buscas algo más a la medida u "on premise", instalar [Istio](https://istio.io/docs/setup/kubernetes/) es otra opción que puedes evaluar. Los dos están basados en [Envoy Proxy](https://www.envoyproxy.io/).
