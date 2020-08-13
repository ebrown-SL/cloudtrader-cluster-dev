# Introduction

This folder contains the configuration used for the ingress controller.

## Description

`cloudtrader-ingress.yaml` contains the configuration for the [NGINX ingress controller](https://kubernetes.github.io/ingress-nginx/).

`cluster-issuer.yaml` is used by [cert-manager](https://cert-manager.io/) to issue a HTTPS certificate via [Let's Encrypt](https://letsencrypt.org/).
