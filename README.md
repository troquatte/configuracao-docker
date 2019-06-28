<h1>Meus Comandos para usar Docker</h1>
<p>Meu repositório docker para não esquecer comandos uteis do dia a dia.</p>

<ul>
  <li>docker ps: Lista os contaners em funcionamento</li>
  <li>docker ps -a: Lista os contaners em funcionando e não.</li>
  <li>docker start {IMAGE NAMES}: Starta o Docker</li>
  <li>docker logs {IMAGE NAMES}: Logs de erro Docker</li>
</ul>

<h2>Ferramentas</h2>

<h3>Postgress</h3>
Terminal: docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
