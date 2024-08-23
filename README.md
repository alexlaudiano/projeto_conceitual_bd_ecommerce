<h1 align="center">Projeto Conceitual de Banco de Dados - E-COMMERCE</h1>

<p align="center">
    <img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=green&style=for-the-badge"/>
    <img src="http://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge"/>
</p>

<div align="center">

### Tópicos

:small_blue_diamond: [Descrição do Projeto](#descrição-do-projeto)
:small_blue_diamond: [Narrativa](#narrativa)
:small_blue_diamond: [Refinamentos do Esquema](#refinamentos-do-esquema)
:small_blue_diamond: [Tecnologias Utilizadas](#tecnologias-utilizadas)
:small_blue_diamond: [Contribuição](#contribuição)
:small_blue_diamond: [Realizado por](#realizado-por)
:small_blue_diamond: [Licença](#licença)

</div>

## Descrição do Projeto
Este documento apresenta a modelagem conceitual de um sistema de e-commerce que abrange as áreas principais de produtos, clientes, pedidos e seus respectivos refinamentos para garantir um funcionamento eficiente e organizado.

## Narrativa

### Produto
* **Plataforma de Venda**: Todos os produtos são vendidos exclusivamente através de uma única plataforma online.
* **Vendedores**: Embora os produtos sejam vendidos por uma única plataforma, eles podem ser oferecidos por diferentes vendedores (terceiros).
* **Fornecedores**: Cada produto listado na plataforma possui um fornecedor associado.
* **Pedidos**: Um pedido pode conter um ou mais produtos.

### Cliente
* **Cadastro**: O cliente pode se cadastrar na plataforma utilizando seu CPF (Pessoa Física) ou CNPJ (Pessoa Jurídica).
* **Endereço**: O endereço cadastrado pelo cliente será utilizado para calcular o valor do frete.
* **Compras**: Um cliente pode realizar múltiplos pedidos na plataforma. Além disso, ele possui um período de carência para solicitar a devolução de produtos comprados.

### Pedido
* **Criação do Pedido**: Os pedidos são criados pelos clientes, contendo informações essenciais sobre a compra, o endereço de entrega e o status da entrega.
* **Composição do Pedido**: Cada pedido pode conter um ou mais produtos.
* **Cancelamento**: Os pedidos podem ser cancelados antes do envio ou durante o processo de entrega, dependendo das políticas da empresa.

## Refinamentos do Esquema
* **Conta de Cliente**: Um cliente pode registrar uma conta como Pessoa Física (PF) ou Pessoa Jurídica (PJ), mas não pode possuir ambas as informações em um único cadastro.
* **Formas de Pagamento**: O sistema permite que um cliente cadastre mais de uma forma de pagamento, proporcionando flexibilidade na hora de realizar uma compra.
* **Entrega**: A entrega dos pedidos inclui o acompanhamento do status e a disponibilização de um código de rastreamento, permitindo ao cliente monitorar o progresso de sua entrega.

## Imagens do Modelo 

![cenario_ecommerce](https://github.com/user-attachments/assets/acd72be7-5059-4a34-89b1-52d029175fe0)
---
### Refinamento do Esquema

![cenario_ecommerce_refinado](https://github.com/user-attachments/assets/58caadce-0974-446d-a062-7813bf6e190c)


## Tecnologias Utilizadas

* MySQL Workbench

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Para isso, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch com a sua feature: `git checkout -b minha-feature`
3. Commit suas mudanças: `git commit -m 'Minha nova feature'`
4. Faça um push para a branch: `git push origin minha-feature`
5. Abra um Pull Request

## Realizado por

* Alex Laudiano

Para mais informações, entre em contato:

[![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-373737?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/laudiano/)
[![Gmail Badge](https://img.shields.io/badge/Gmail-373737?style=flat&logo=Gmail&logoColor=white)](mailto:laudiano@gmail.com)
[![Instagram Badge](https://img.shields.io/badge/-Instagram-373737?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/laudianoalex/?hl=pt-br)

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
