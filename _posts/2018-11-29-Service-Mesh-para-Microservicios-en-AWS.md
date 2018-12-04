---
layout: post
title:  "Service Mesh para microservicios en AWS"
author: AdES
date:   2018-11-29 10:45
excerpt: "AWS anuncia su servicio para monitorear y controlar microservicios en la nube mediante una 'malla de servicios' (Service Mesh)"
featured: true
external_image: true
image:  https://d1.awsstatic.com/r2018/a/Product-Page-Diagram_Lattice_After.de0ef7327c19197e473f7bf59f4687cea53f01f3.png
---

Como ya lo hemos venido platicando, gestionar los microservicios se vuelve complicado, cada vez que se van introduciendo nuevos servicios los puntos de falla son más difíciles de identificar y hacer "troubleshooting".

Amazon acaba de anunciar el acceso público a su nuevo servicio de **AWS App Mesh**, el cual facilita la ejecución de los microservicios dando visibilidad y control del tráfico para cada microservicio de manera individual en toda tu solución.

De la misma manera que [Istio](https://istio.io/), **AWS App Mesh** utiliza [Envoy Proxy](https://www.envoyproxy.io/), el cual permite la ejecución de una arquitectura de microservicios distribuida y provee una manera uniforme para asegurar, conectar y monitorear los microservicios.
