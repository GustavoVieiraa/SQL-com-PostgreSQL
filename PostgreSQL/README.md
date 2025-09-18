<div align="center">
  <table>
    <tr>
      <td align="center">
        <!-- Link para o Certificado -->
        <a href="https://cursos.alura.com.br/certificate/e227e017-9934-4596-8ea1-67cb97568e1d">
          <img loading="lazy" width="128px" src="https://www.alura.com.br/assets/api/cursos/introducao-postgresql-primeiros-passos.svg" />
        </a>
        <h4>Curso</h4>
      </td>
      <td align="center">
        <!-- Link para o Certificado -->
        <a href="https://cursos.alura.com.br/certificate/e227e017-9934-4596-8ea1-67cb97568e1d">
          <img loading="lazy" width="128px" src="https://static.vecteezy.com/system/resources/previews/028/293/920/original/trophy-icon-3d-rendering-illustration-png.png" />
        </a>
        <h4>Certificado</h4>
      </td>
    </tr>
  </table>
  <h1>PostgreSQL</h1>
</div>
<p align="right">
  <img loading="lazy" src="https://img.shields.io/badge/CARGA_HORARIA-8_HORAS-orange?style=for-the-badge"/>
  <img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO!&color=GREEN&style=for-the-badge"/>
</p>

<div>
  <h2>Conhecimentos adquiridos em SQL:</h2>
  <ul>
    <li><h3>Configuração do ambiente de banco de dados e entendimento das versões utilizadas.</h3></li>
    <li><h3>Criação e exclusão de bancos de dados, entendendo sua estrutura e ciclo de vida.</h3></li>
    <li><h3>Definição e criação de tabelas, incluindo tabelas de exemplo como "empresa".</h3></li>
    <li><h3>Execução de operações CRUD (Create, Read, Update, Delete) em registros, com exemplos práticos como inclusão de professores, alteração de percentuais e exclusão de produtos.</h3></li>
    <li><h3>Consultas com filtros, selecionando colunas específicas, aplicando condições em campos de texto, numéricos, datas e booleanos, além do uso de operadores lógicos (AND/OR).</h3></li>
    <li><h3>Trabalho com relacionamentos entre tabelas, criação de chaves primárias e estrangeiras, e execução de consultas envolvendo múltiplas tabelas.</h3></li>
    <li><h3>Utilização de diferentes tipos de JOINs (INNER, LEFT, RIGHT, FULL e CROSS) para integração de dados relacionados.</h3></li>
    <li><h3>Aplicação de operações com CASCADE em exclusões e atualizações, mantendo a integridade referencial entre tabelas.</h3></li>
    <li><h3>Consultas avançadas com ordenação, limitação de resultados, uso de funções de agregação (COUNT, SUM, AVG, MAX, MIN) e agrupamento de dados.</h3></li>
    <li><h3>Filtragem em consultas agrupadas, permitindo análises como relatórios e apuração de resultados.</h3></li>
    <li><h3>Compreensão sobre carreira em SQL e sua aplicação prática em diferentes áreas da tecnologia.</h3></li>
  </ul>
</div>

<div>
  <h2>Comandos SQL aprendidos:</h2>

  <div>
    <h3>Gerenciamento de Banco de Dados</h3>
    <ul>
      <li><code>CREATE DATABASE nome_banco;</code>: Cria um novo banco de dados.</li>
      <li><code>DROP DATABASE nome_banco;</code>: Exclui um banco de dados existente.</li>
      <li><code>\c nome_banco</code>: Seleciona o banco de dados (PostgreSQL).</li>
    </ul>
  </div>

  <div>
    <h3>Gerenciamento de Tabelas</h3>
    <ul>
      <li><code>CREATE TABLE nome_tabela (...);</code>: Cria uma nova tabela com colunas e tipos definidos.</li>
      <li><code>DROP TABLE nome_tabela;</code>: Exclui uma tabela existente.</li>
      <li><code>ALTER TABLE nome_tabela ADD COLUMN coluna tipo;</code>: Adiciona uma nova coluna.</li>
      <li><code>ALTER TABLE nome_tabela DROP COLUMN coluna;</code>: Remove uma coluna.</li>
    </ul>
  </div>

  <div>
    <h3>Operações CRUD</h3>
    <ul>
      <li><code>INSERT INTO tabela (col1, col2) VALUES (valor1, valor2);</code>: Insere um novo registro.</li>
      <li><code>SELECT * FROM tabela;</code>: Retorna todos os registros de uma tabela.</li>
      <li><code>SELECT col1, col2 FROM tabela;</code>: Retorna apenas colunas específicas.</li>
      <li><code>UPDATE tabela SET coluna = valor WHERE condição;</code>: Atualiza registros existentes.</li>
      <li><code>DELETE FROM tabela WHERE condição;</code>: Exclui registros específicos.</li>
    </ul>
  </div>

  <div>
    <h3>Consultas com Filtros</h3>
    <ul>
      <li><code>SELECT * FROM tabela WHERE coluna = 'valor';</code>: Filtro por valor exato.</li>
      <li><code>SELECT * FROM tabela WHERE coluna LIKE '%texto%';</code>: Pesquisa parcial em texto.</li>
      <li><code>SELECT * FROM tabela WHERE coluna > 100;</code>: Filtro por valor numérico.</li>
      <li><code>SELECT * FROM tabela WHERE data BETWEEN '2025-01-01' AND '2025-12-31';</code>: Filtro por intervalo de datas.</li>
      <li><code>SELECT * FROM tabela WHERE ativo = TRUE;</code>: Filtro booleano.</li>
      <li><code>SELECT * FROM tabela WHERE col1 = 'A' AND col2 > 10;</code>: Uso de operadores lógicos.</li>
      <li><code>SELECT * FROM tabela WHERE col1 = 'A' OR col2 = 'B';</code>: Combinação de condições.</li>
    </ul>
  </div>

  <div>
    <h3>Relacionamentos e JOINS</h3>
    <ul>
      <li><code>PRIMARY KEY</code>: Define a chave primária de uma tabela.</li>
      <li><code>FOREIGN KEY</code>: Define a chave estrangeira, criando relacionamento entre tabelas.</li>
      <li><code>INNER JOIN</code>: Retorna registros que existem em ambas as tabelas.</li>
      <li><code>LEFT JOIN</code>: Retorna todos os registros da tabela da esquerda e os correspondentes da direita.</li>
      <li><code>RIGHT JOIN</code>: Retorna todos os registros da tabela da direita e os correspondentes da esquerda.</li>
      <li><code>FULL JOIN</code>: Retorna todos os registros quando há correspondência em uma das tabelas.</li>
      <li><code>CROSS JOIN</code>: Retorna todas as combinações possíveis entre duas tabelas.</li>
    </ul>
  </div>

  <div>
    <h3>Cascade em Relacionamentos</h3>
    <ul>
      <li><code>ON DELETE CASCADE</code>: Exclui automaticamente registros relacionados.</li>
      <li><code>ON UPDATE CASCADE</code>: Atualiza automaticamente registros relacionados.</li>
    </ul>
  </div>

  <div>
    <h3>Consultas Avançadas</h3>
    <ul>
      <li><code>SELECT * FROM tabela ORDER BY coluna ASC/DESC;</code>: Ordena os resultados.</li>
      <li><code>SELECT * FROM tabela LIMIT 10;</code>: Limita o número de registros retornados.</li>
      <li><code>SELECT COUNT(*) FROM tabela;</code>: Conta o número de registros.</li>
      <li><code>SELECT AVG(coluna) FROM tabela;</code>: Calcula a média de valores.</li>
      <li><code>SELECT SUM(coluna) FROM tabela;</code>: Soma valores de uma coluna.</li>
      <li><code>SELECT MIN(coluna), MAX(coluna) FROM tabela;</code>: Retorna o menor e maior valor.</li>
      <li><code>SELECT coluna, COUNT(*) FROM tabela GROUP BY coluna;</code>: Agrupa resultados por uma coluna.</li>
      <li><code>SELECT coluna, COUNT(*) FROM tabela GROUP BY coluna HAVING COUNT(*) > 1;</code>: Filtra agrupamentos.</li>
    </ul>
  </div>
</div>
