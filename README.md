# curso_aspnet_core_api

Passo a Passo para adicionar novas funcionalidade

---

## Api.Domain

>1 - Entities (Entidades)
>2 - Dtos
>3 - Interfaces
>4 - Models
	
## Api.Data

>1 - Mapping Entities (Mapear as Entidades)
>2 - MyContext (Atualizar)
>3 - Fazer Migrações
>4 - Atualizar o Banco de Dados
>5 - Implementations (Implementação da Classe BaseEntity)
>>5.1 - Api.Domain.Repository
>>5.2 - Api.Data.Implementations

## Data.Test
>>1 - Testes de todos os Métodos da BaseRepository	
>>2 - Testes de todos os Métodos da Implementations

---

## Api.CrossCutting
       1 - DtoToModelProfile
       2 - EntityToDtoProfile
       3 - ModelToEntityProfile
 	
## Api.Service
       1 - Criar Services

## Api.Service.Test
       1 - Testes do AutoMapper
       2 - Testes dos Services Com Mock de Service (Retornando repositorio Faker)	

---
	
## Api.CrossCutting
>>1 - Configure Repository
>>2 - Configure Service

## Api.Application

>>1 - Controller

## Api.Application.Tests

>>1 - Testes de Todos os Métodos e Retorno das Controllers

---

## Api.Integration.Tests
>>1 - Testar todas as Requisições		

