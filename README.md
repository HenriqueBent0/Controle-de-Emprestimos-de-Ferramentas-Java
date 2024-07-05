# Sistema de Empréstimos de Ferramentas em Java

## 📖 Introdução
Este projeto é um sistema de empréstimos de ferramentas desenvolvido em Java, integrado com um banco de dados MySQL. O sistema permite gerenciar amigos, ferramentas, empréstimos com data específica e registra devoluções, enviando os registros para um histórico de empréstimos.

## 💻 Tecnologias Utilizadas
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

### Funcionalidades
- **Cadastro de Amigos:** Adicionar e gerenciar amigos no sistema.
- **Cadastro de Ferramentas:** Registrar novas ferramentas disponíveis para empréstimo.
- **Registro de Empréstimos:** Emprestar ferramentas para amigos, com data de empréstimo especificada.
- **Registro de Devoluções:** Devolver ferramentas emprestadas, movendo os registros para um histórico de empréstimos.

## Como Configurar e Executar
Para configurar e executar o projeto:
1. - Inicialize todas as telas do programa antes de usar suas funcionalidades.

2. **Configurar o Banco de Dados:**
   - Configure um servidor MySQL ou utilize um banco de dados local.
   - Execute o script SQL fornecido em `banco.sql` para criar o banco de dados e as tabelas necessárias (`tb_amigos`, `tb_ferramentas`, `tb_emprestimos`, `tb_devolucao`).
  
3. **Telas do Sistema:**

   Aqui estão as telas principais do sistema:

   <table>
     <tr>
       <td align="center">
         <img src="https://github.com/HenriqueBent0/Controle-de-Emprestimos-de-Ferramentas-Java/assets/166830118/86349174-f5aa-4354-921d-7a4f848743f8" alt="Menu" width="300" />
         <p><b>Menu</b></p>
       </td>
       <td align="center">
         <img src="https://github.com/HenriqueBent0/Controle-de-Emprestimos-de-Ferramentas-Java/assets/166830118/89e3530c-7ece-4971-8a3a-feb72f710721" alt="Cadastrar Amigo" width="300" />
         <p><b>Cadastrar Amigo</b></p>
       </td>
       <td align="center">
         <img src="https://github.com/HenriqueBent0/Controle-de-Emprestimos-de-Ferramentas-Java/assets/166830118/7b56aaee-83ac-4ac3-861d-9dd85ff9a8af" alt="Cadastro Ferramenta" width="300" />
         <p><b>Cadastro Ferramenta</b></p>
       </td>
     </tr>
     <tr>
       <td align="center">
         <img src="https://github.com/HenriqueBent0/Controle-de-Emprestimos-de-Ferramentas-Java/assets/166830118/7492a51d-0aa1-4fdf-be7c-36e278fbe062" alt="Gerenciador Amigos" width="300" />
         <p><b>Gerenciador Amigos</b></p>
       </td>
       <td align="center">
         <img src="https://github.com/HenriqueBent0/Controle-de-Emprestimos-de-Ferramentas-Java/assets/166830118/e96f90ef-8bff-4256-8fdb-acf532d0e5c1" alt="Gerenciador Ferramentas" width="300" />
         <p><b>Gerenciador Ferramentas</b></p>
       </td>
       <td align="center">
         <img src="https://github.com/HenriqueBent0/Controle-de-Emprestimos-de-Ferramentas-Java/assets/166830118/738ccf0b-2df1-489e-820f-2fb9a3a934f7" alt="Relatório de Empréstimo" width="300" />
         <p><b>Relatório de Empréstimo</b></p>
       </td>
     </tr>
     <tr>
       <td colspan="3" align="center">
         <img src="https://github.com/HenriqueBent0/Controle-de-Emprestimos-de-Ferramentas-Java/assets/166830118/3fef6ff8-2e9c-44ad-8ee8-19f7a6a3dd91" alt="Histórico de Empréstimos" width="600" />
         <p><b>Histórico de Empréstimos</b></p>
       </td>
     </tr>
   </table>
