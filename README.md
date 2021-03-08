# URI-Online-Judge
  Resoluções do [URI Online Judge](https://www.urionlinejudge.com.br)<br/>
  ![](https://www.jornalbomdia.com.br/tb_noticias/4009/urii.png)<br/>

## NOTAS PARA CÓDIGOS EM HTML/JS
  A resposta é somento o que está dentro da tag **_<script>_**.<br/>
  ~~~javascript
  1. <script>...</script>
  ~~~
  Na entrada de dados trocar **_prompt()_** por **_lines.shift()_**.<br/>
  ~~~javascript
  1. var a = prompt() --> var a = lines.shift()
  ~~~
  Manter as 2 primeiras linhas que estão ao abrir o URI.
  ~~~javascript
  1. var input = require('fs').readFileSync('/dev/stdin', 'utf8');<br/>
  2. var lines = input.split('\n');
  ~~~
  
## OUTROS
  Deixe seu [comentário ou sujestão](https://github.com/DevPauloYuri/URI-Online-Judge/discussions)👍<br/>
  [@DevPauloYuri](https://github.com/DevPauloYuri)
