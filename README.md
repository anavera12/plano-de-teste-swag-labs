# Plano de Teste

**Swag Labs**

*versão 0.0*

## Histórico das alterações

   Data    | Versão |    Descrição   | Autor(a)
-----------|--------|----------------|-----------------
07/01/2025 |  0.0   | Release incial | Ana Clara


## 1 - Introdução

Este documento tem como objetivo apresentar a estratégia e o escopo dos testes automatizados a serem executados no site Sauce Demo (Swag Labs), utilizando o framework Cypress. A meta é garantir que as funcionalidades críticas — como autenticação, adição e remoção de itens no carrinho e fluxo de finalização de compra — estejam funcionando de acordo.

## 2 - Requisitos a Testar

### Casos de uso:

Identificador do caso de uso | Nome do caso de uso
-----------------------------|---------------------
 CU001                       |       Login
 CU002                       |       Gerenciamento de Carrinho

### Requisitos não-funcionais:

Identificador do requisito   | Nome do requisito
-----------------------------|---------------------
 RNF001                      |      Confiabilidade


## 3 - Tipos de teste

- Teste de interface de usuário;
- Teste funcional;
- CI/CD;
- Teste de integração

### 3.1 - Métodos da Classe 

Para teste de funcionalidade.
Aqui deve-se verificar se cada classe ou função principal (como as que lidam com login e carrinho) retorna o esperado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Validar o correto funcionamento das funções de login, adição e remoção de itens no carrinho
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade (x)
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Ana Clara
        </th>
    </tr>
</table>
<br/>

### 3.2 - Integração dos Componentes

Para teste de funcionalidade envolvendo a comunicação entre diferentes partes da aplicação.

É importante verificar se a aplicação integra corretamente: login -> seleção de produtos -> carrinho -> checkout.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Validar se todas as etapas (login, adição de itens, finalização de compra) funcionam de forma integrada.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração (x)
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Ana Clara
        </th>
    </tr>
</table>
<br/>

## 4 - Recursos

### 4.1 - Ambiente de teste - Software e Hardware

- Sistema Operacional: Windows
- Browsers: Google Chrome
- Node.js: para executar o Cypress
- Ferramenta de Versionamento: GitHub
- VsCode

### 4.2 - Ferramenta de teste

- Cypress
- Dotenv

## 5 - Cronograma

Tipo de teste      | Duração | data de início | data de término
-------------------|---------|----------------|-----------------
planejar teste     |1h       | 07/01/2025     | 07/01/2025
projetar teste     |2h       | 07/01/2025     | 07/01/2025
implementar teste  |         | dd/mm/aaaa     | dd/mm/aaaa
executar teste     |         | dd/mm/aaaa     | dd/mm/aaaa
avaliar teste      |         | dd/mm/aaaa     | dd/mm/aaaa
