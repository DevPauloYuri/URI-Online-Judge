# URI-Online-Judge
  Resoluções do [URI Online Judge](https://www.urionlinejudge.com.br)<br/>
  ![](https://www.jornalbomdia.com.br/tb_noticias/4009/urii.png)<br/>

## NOTAS PARA CÓDIGOS EM HTML/JS
  A resposta é somento o que está dentro da tag **_<script>_**.<br/>
  ~~~javascript
  <script>...</script>
  ~~~
  Na entrada de dados trocar **_prompt()_** por **_lines.shift()_**.<br/>
  ~~~javascript
  var a = prompt() --> var a = lines.shift()
  ~~~
  Manter as 2 primeiras linhas que estão ao abrir o URI.
  ~~~javascript
  var input = require('fs').readFileSync('/dev/stdin', 'utf8');<br/>
  var lines = input.split('\n');
  ~~~
  
## OUTROS
  Deixe seu comentário ou sujestão👍
