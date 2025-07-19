1. Use registry modules in configuration

Terraform은 Root Module과 Child Module(다른 구성에 의해 호출되는 모듈)로 구성

테라폼 레지스트리 https://registry.terraform.io/ 에서 모듈을 제공, 모듈은 source, version 으로 구성 

다양한 source 유형에서의 설치를 지원한다. : Local Paths, Terraform Registry, Github, Bitbucket, S3 bucket 등 https://developer.hashicorp.com/terraform/language/modules/sources

```bash
`kubectl get pods` 
