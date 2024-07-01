# DreamHouse Project

Bem-vindo ao repositório do projeto DreamHouse! Este projeto é uma aplicação Salesforce desenvolvida utilizando Apex. O objetivo do projeto é gerenciar listagens de imóveis, agentes e clientes para uma agência imobiliária fictícia chamada DreamHouse.

## Índice

- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Contribuindo](#contribuindo)
- [Contato](#contato)

## Visão Geral

O projeto DreamHouse é uma aplicação completa que demonstra o poder do Salesforce e do Apex para criar soluções personalizadas. A aplicação inclui gerenciamento de imóveis, clientes e agentes, além de funcionalidades avançadas como automações e relatórios.

## Funcionalidades

- **Gerenciamento de Imóveis**: Criação, atualização e exclusão de listagens de imóveis.
- **Gerenciamento de Agentes**: Atribuição de agentes a imóveis e gerenciamento de suas informações.
- **Gerenciamento de Clientes**: Registro e acompanhamento de clientes interessados nos imóveis.
- **Automação de Processos**: Uso de Apex Triggers e Classes para automatizar processos de negócios.
- **Relatórios e Dashboards**: Criação de relatórios e dashboards para visualização dos dados.

## Requisitos

- Conta no Salesforce com permissões de desenvolvedor.
- Conhecimento básico de Apex e desenvolvimento no Salesforce.

## Instalação

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/dreamhouse.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd dreamhouse
    ```

3. Autentique-se no Salesforce CLI:
    ```bash
    sfdx force:auth:web:login
    ```

4. Crie uma nova organização:
    ```bash
    sfdx force:org:create -s -f config/project-scratch-def.json
    ```

5. Instale os pacotes dependentes:
    ```bash
    sfdx force:source:push
    ```

6. Atribua a permissão de acesso:
    ```bash
    sfdx force:user:permset:assign -n DreamHousePermissionSet
    ```

7. Abra a organização no navegador:
    ```bash
    sfdx force:org:open
    ```

## Uso

Após a instalação, você pode começar a usar a aplicação DreamHouse diretamente na sua organização Salesforce. Navegue pelas abas disponíveis para gerenciar imóveis, agentes e clientes.

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.

1. Fork este repositório.
2. Crie uma branch com a sua feature:
    ```bash
    git checkout -b minha-feature
    ```
3. Faça commit das suas alterações:
    ```bash
    git commit -m 'Adiciona minha feature'
    ```
4. Envie para a branch principal:
    ```bash
    git push origin minha-feature
    ```
5. Abra um Pull Request.

## Contato

Para mais informações, entre em contato através do email: [dev.alvarojordao@gmail.com](mailto:dev.alvarojordao@gmail.com).

---

Obrigado por utilizar a DreamHouse!

