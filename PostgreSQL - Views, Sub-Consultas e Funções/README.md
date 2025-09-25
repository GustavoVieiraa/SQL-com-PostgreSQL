<div align="center">
  <table>
    <tr>
      <td align="center">
        <!-- Link para o Certificado -->
        <a href="https://cursos.alura.com.br/certificate/2e37df8b-83a7-4165-9981-c1ef899ffe2b">
          <img loading="lazy" width="128px" src="https://www.alura.com.br/assets/api/cursos/postgresql-views-sub-consultas-funcoes.svg" />
        </a>
        <h4>Curso</h4>
      </td>
      <td align="center">
        <!-- Link para o Certificado -->
        <a href="https://cursos.alura.com.br/certificate/2e37df8b-83a7-4165-9981-c1ef899ffe2b">
          <img loading="lazy" width="128px" src="https://static.vecteezy.com/system/resources/previews/028/293/920/original/trophy-icon-3d-rendering-illustration-png.png" />
        </a>
        <h4>Certificado</h4>
      </td>
    </tr>
  </table>
  <h1>PostgreSQL: Views, Sub-Consultas e Funções</h1>
</div>
<p align="right">
  <img loading="lazy" src="https://img.shields.io/badge/CARGA_HORARIA-6_HORAS-orange?style=for-the-badge"/>
  <img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO!&color=GREEN&style=for-the-badge"/>
</p>

<div>
  <h2>Conhecimentos adquiridos em SQL (Views, Sub-Consultas e Funções):</h2>
  <ul>
    <li><h3>Compreensão de chaves estrangeiras, definição formal e diferentes tipos de relacionamentos entre tabelas.</h3></li>
    <li><h3>Execução de práticas de preparação de dados e análise de diferentes sintaxes SQL.</h3></li>
    <li><h3>Construção de consultas complexas utilizando sub-consultas e queries aninhadas.</h3></li>
    <li><h3>Utilização de operadores como <code>IN</code> em sub-consultas para refinar resultados.</h3></li>
    <li><h3>Aplicação de funções de string, data, matemáticas e conversões de dados em consultas.</h3></li>
    <li><h3>Criação e manipulação de views, entendendo suas características e aplicações práticas.</h3></li>
    <li><h3>Elaboração de relatórios com consultas avançadas, sub-consultas e agrupamentos.</h3></li>
    <li><h3>Compreensão sobre a importância da documentação oficial para aprofundar o uso de funções SQL.</h3></li>
  </ul>
</div>

<div>
  <h2>Comandos e recursos SQL aprendidos:</h2>

  <div>
    <h3>Relacionamentos e Chaves Estrangeiras</h3>
    <ul>
      <li><code>FOREIGN KEY (coluna) REFERENCES outra_tabela(coluna);</code>: Define relacionamento entre tabelas.</li>
      <li><code>ON DELETE CASCADE</code> / <code>ON UPDATE CASCADE</code>: Mantém integridade referencial em operações.</li>
    </ul>
  </div>

  <div>
    <h3>Sub-Consultas</h3>
    <ul>
      <li><code>SELECT * FROM tabela WHERE coluna IN (SELECT coluna FROM outra_tabela);</code>: Uso do operador IN com sub-consulta.</li>
      <li><code>SELECT col1, (SELECT AVG(col2) FROM outra_tabela) FROM tabela;</code>: Sub-consulta aninhada.</li>
    </ul>
  </div>

  <div>
    <h3>Funções</h3>
    <ul>
      <li><code>UPPER(coluna)</code> / <code>LOWER(coluna)</code>: Manipulação de strings.</li>
      <li><code>LENGTH(coluna)</code>: Tamanho de strings.</li>
      <li><code>NOW()</code>: Data e hora atuais.</li>
      <li><code>AGE(data)</code>: Diferença entre datas.</li>
      <li><code>ROUND(numero, casas)</code>: Arredondamento de valores numéricos.</li>
      <li><code>CAST(coluna AS tipo)</code>: Conversão de dados.</li>
    </ul>
  </div>

  <div>
    <h3>Views</h3>
    <ul>
      <li><code>CREATE VIEW nome_view AS SELECT ...;</code>: Cria uma view.</li>
      <li><code>SELECT * FROM nome_view;</code>: Consulta os dados da view.</li>
      <li><code>DROP VIEW nome_view;</code>: Remove uma view existente.</li>
    </ul>
  </div>
</div>
