# curso_aspnet_core_api

Passo a Passo para adicionar novas funcionalidade

---

## Api.Domain

- Entities (Entidades)
- Dtos
- Interfaces
- Models
	
## Api.Data

- Mapping Entities (Mapear as Entidades)
- MyContext (Atualizar)
- Fazer Migrações
- Atualizar o Banco de Dados
- Implementations (Implementação da Classe BaseEntity)
    - Api.Domain.Repository
    - Api.Data.Implementations

## Data.Test
- Testes de todos os Métodos da BaseRepository	
- Testes de todos os Métodos da Implementations

---

## Api.CrossCutting

- DtoToModelProfile
- EntityToDtoProfile
- ModelToEntityProfile
 	
## Api.Service

- Criar Services

## Api.Service.Test
- Testes do AutoMapper
- Testes dos Services Com Mock de Service (Retornando repositorio Faker)	

---
	
## Api.CrossCutting
- Configure Repository
- Configure Service

## Api.Application

- Controller

## Api.Application.Tests

- Testes de Todos os Métodos e Retorno das Controllers

---

## Api.Integration.Tests
- Testar todas as Requisições		

