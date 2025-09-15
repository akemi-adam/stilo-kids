
# Documento Lista de User Stories

Documento construído a partido do **Modelo BSI - Doc 004 - Lista de User Stories** que pode ser encontrado no
link: https://docs.google.com/document/d/1Ns2J9KTpLgNOpCZjXJXw_RSCSijTJhUx4zgFhYecEJg/edit?usp=sharing

## Descrição

Este documento descreve os User Stories criados a partir da Lista de Requisitos no [Documento 001 - Documento de Visão](doc-visao.md). Este documento também pode ser adaptado para descrever Casos de Uso. Modelo de documento baseado nas características do processo easYProcess (YP).

## Histórico de revisões

| Data       | Versão  | Descrição                          | Autor                          |
| :--------- | :-----: | :--------------------------------: | :----------------------------- |




### User Story US02 - Manter Fornecedor

<table>
  <tr>
    <th colspan="2" style="text-align:left;background:#e0e0e0;padding:8px;">📌 User Story - US02</th>
  </tr>
  <tr>
    <td style="width:25%;padding:6px;"><strong>Título</strong>Manter Fornecedor</td>
    <td style="padding:6px;">O sistema de manter um cadastro de fornecedores. Um fornecedor tem os atirbutos: id e name, além de ter relação com as tabelas de endereços e telefones. Ambas as relações são de 1:N (Um fornecedor tem vários endereços/telefones). A tabela de telefones tem os atributos: id, number, supplier_id. Já a tabela de endereços tem os atributos: id, city, street, neighborhood, number, supplier_id. O usuário poderá cadastrar, editar, excluir, listar ou detalhar um fornecedor.</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Identificação</strong></td>
    <td style="padding:6px;">US01 - Manter Fornecedor</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Story</strong></td>
    <td style="padding:6px;">
      Como <em>proprietária da loja</em>, quero <em>realizar as operações de manter um fornecedor</em>, para <em>ter um controle e histórico sobre os fornecedores da loja</em>.
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Requisitos Relacionados</strong></td>
    <td style="padding:6px;">RF01</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Critérios de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>O sistema deve exibir mensagem de sucesso após cadastro correto.</li>
        <li>O sistema deve validar campos obrigatórios e exibir mensagens de erro.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Testes de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>TA01.01 - Cadastro bem sucedido com todos os dados válidos redireciona para uma mensagem de cadastro feito com sucesso.</li>
        <li>TA01.02 - Realizar o cadastro com algum campo inválido (vazio, valor não aceito, etc) retorna uma mensagem de erro e não efetua o cadastro.</li>
        <li>TA01.03 - Edição bem sucedida com todos os dados válidos redireciona para uma mensagem de atualização feita com sucesso.</li>
        <li>TA01.04 - Realizar a edição com algum campo inválido (vazio, valor não aceito, etc) retorna uma mensagem de erro e não efetua a edição.</li>
        <li>TA01.05 - Listar os fornecedores retornará a lista de todos os fornecedores cadastrados no sistema.</li>
        <li>TA01.06 - Listar os fornecedores e não encontrar nenhum, será retornada uma mensagem de fornecedores não encontrados.</li>
        <li>TA01.07 - Buscar um fornecedor retorna os dados desse fornecedor em específico.</li>
        <li>TA01.08 - Buscar um fornecedor inexistente retorna uma mensagem de fornecedor não encontrado.</li>
        <li>TA01.09 - Deletar um fornecedor retorna uma mensagem de fornecedor deletado com sucesso.</li>
        <li>TA01.10 - Deletar um fornecedor inexistente retorna uma mensagem de erro.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Estimativa</strong></td>
    <td style="padding:6px;">5h</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tempo Real Gasto</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tamanho Funcional</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Prioridade</strong></td>
    <td style="padding:6px;">Essencial</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Responsáveis</strong></td>
    <td style="padding:6px;">
      <ul>
        <li><strong>Analista:</strong> Elder</li>
        <li><strong>Desenvolvedor:</strong> Felipe</li>
        <li><strong>Revisor:</strong> Mosiah</li>
        <li><strong>Testador:</strong> Pedro Vitor</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Protótipo</strong></td>
    <td style="padding:6px;">
    </td>
  </tr>
</table>
