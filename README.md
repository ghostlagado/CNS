# CNS — Consulta Facilitada

<p align="center">
  <img src="src/img/icon.ico" alt="Ícone do CNS" width="110">
</p>

<p align="center">
  <strong>Consulte dados do GPS Vista com mais agilidade e sem precisar escrever SQL.</strong>
</p>

<p align="center">
  Aplicativo desktop para facilitar consultas operacionais ao banco de dados, utilizando filtros e exibindo os resultados em uma tabela dinâmica.
</p>

<p align="center">
  <img src="src/img/animation.gif" alt="Demonstração do CNS" />
</p>

---

## Visão geral

O **CNS (Consulta Facilitada)** foi desenvolvido para simplificar consultas que não estão disponíveis diretamente, ou que são demoradas de realizar, pela interface do GPS Vista.

Em vez de exigir conhecimento de SQL ou acesso manual ao banco de dados, o aplicativo permite informar filtros, executar a consulta e visualizar os resultados em uma tabela.

### Principais recursos

- **Filtros de consulta:** período, contrato (CR) e serviço.
- **Tabela dinâmica:** resultados apresentados conforme os filtros selecionados.
- **Exportação para Excel:** facilite a análise e o compartilhamento dos dados.
- **Controle de visualização:** limpe os filtros ou a tabela e ajuste o número de linhas exibidas.
- **Conexão ao banco de dados:** acesso conforme as credenciais e a infraestrutura autorizada.

## Download

| Plataforma | Disponibilidade |
| --- | --- |
| Windows | [Baixar o instalador](InstaladorCNS.exe) |
| Android | Ainda não disponível |

> **Observação:** o instalador do Windows está armazenado neste repositório. Verifique as políticas internas antes de executar o aplicativo.

## Requisitos de conexão

O CNS precisa de acesso à rede corporativa para se conectar ao banco de dados.

- **VPN:** conecte-se à VPN corporativa antes de iniciar o acesso.
- **Credenciais:** utilize as credenciais autorizadas para o banco de dados.
- **Permissões:** solicite a configuração de acesso ao responsável pela infraestrutura ou ao suporte interno, caso necessário.

> **Importante:** não tente contornar as regras de acesso à rede ou do banco de dados. Se a VPN não estiver configurada, entre em contato com o suporte responsável.

## Como utilizar

### 1. Conecte-se ao banco de dados

Abra o aplicativo e informe os dados de conexão solicitados. A conexão depende da VPN e das permissões da sua conta.

![Tela de login](https://github.com/foxtec198/CNS/assets/64221923/6e27c457-c528-4fca-a1cb-1d25f64fec2c)

O aplicativo informa se a tentativa de conexão foi bem-sucedida.

| Conexão realizada | Falha na conexão |
| --- | --- |
| ![Login realizado](https://github.com/foxtec198/CNS/assets/64221923/51058cad-1b7a-4314-b420-f191988c4036) | ![Falha no login](https://github.com/foxtec198/CNS/assets/64221923/afbca5fe-3e59-48fc-9b09-622686322f76) |

### 2. Defina os filtros

Na tela principal, preencha os filtros disponíveis:

- **Período:** data inicial e data final.
- **Contrato:** CR que deseja consultar.
- **Serviço:** serviço relacionado à consulta.

![Tela principal](https://github.com/foxtec198/CNS/assets/64221923/6f0e0c54-00b5-4e0e-9675-d3d25456acb6)

### 3. Execute e analise a consulta

Clique em **Consultar** para processar os filtros e carregar os resultados na tabela.

![Processamento dos filtros](https://github.com/foxtec198/CNS/assets/64221923/38555d22-1c20-4b42-914a-6382b0b1fa07)

![Tabela de resultados](https://github.com/foxtec198/CNS/assets/64221923/fc101b8b-dbe1-47b6-a9e6-99368905e6ca)

Na tela principal, você também pode:

- **Limpar filtros:** remover os critérios selecionados.
- **Limpar tabela:** remover os resultados exibidos.
- **Exportar para Excel:** salvar os dados consultados.
- **Número de linhas:** controlar a quantidade de linhas exibidas.

## Solução de problemas

**Não consigo conectar ao banco de dados**
- Confirme se a VPN corporativa está conectada.
- Verifique os dados de conexão e as permissões da conta.
- Se o problema persistir, contate o suporte responsável.

**A consulta não retorna os dados esperados**
- Confira o período informado.
- Verifique o CR e o serviço selecionados.
- Execute novamente após corrigir os filtros.

## Tecnologias

Este repositório contém o aplicativo CNS e seus recursos de interface. Consulte os arquivos do projeto para identificar as dependências e os procedimentos de desenvolvimento compatíveis com a versão atual.

## Autor

Desenvolvido por **Guilherme Breve** em 2023.

---

<p align="center">
  <sub>CNS — Consulta Facilitada · Ferramenta de apoio a consultas operacionais</sub>
</p>
