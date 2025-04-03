<table border="1" align="center">
  <tr>
    <th>Descrição</th>
    <th>Comando</th>
  </tr>
  <tr>
    <td>Inicializa o Git</td>
    <td><code>git init</code></td>
  </tr>
  <tr>
    <td>Adicionar mudanças</td>
    <td><code>git add .</code></td>
  </tr>
  <tr>
    <td>Mudar o nome da branch atual</td>
    <td><code>git branch -M main</code></td>
  </tr>
  <tr>
    <td>Commitar mudanças</td>
    <td><code>git commit -m "Initial Commit"</code></td>
  </tr>
  <tr>
    <td>Adicionar um repositório remoto</td>
    <td><code>git remote add origin https://&lt;repo&gt;.git</code></td>
  </tr>
  <tr>
    <td>Fazer push do commit atual</td>
    <td><code>git push -u origin main</code></td>
  </tr>
  <tr>
    <td>Forçar e sobrescrever um commit (cuidado!)</td>
    <td><code>git push --force origin main</code></td>
  </tr>
  <tr>
    <td>Apagar histórico</td>
    <td><code>history -c && history -w</code></td>
  </tr>
  <tr>
    <td>Criar uma branch</td>
    <td><code>git branch branch_new</code></td>
  </tr>
  <tr>
    <td>Alternar de branch</td>
    <td><code>git checkout (ou switch) branch_new</code></td>
  </tr>
  <tr>
    <td>Mostrar todos os commits</td>
    <td><code>git log</code></td>
  </tr>
  <tr>
    <td>Mostrar todas as branches</td>
    <td><code>git branch</code></td>
  </tr>
  <tr>
    <td>Ver alterações antes do commit</td>
    <td><code>git status</code></td>
  </tr>
  <tr>
    <td>Ver diferenças nos arquivos antes de adicionar</td>
    <td><code>git diff</code></td>
  </tr>
  <tr>
    <td>Clonar um repositório</td>
    <td><code>git clone https://&lt;repo&gt;.git</code></td>
  </tr>
  <tr>
    <td>Restaurar um arquivo modificado antes do commit</td>
    <td><code>git checkout -- arquivo.txt</code></td>
  </tr>
  <tr>
    <td>Excluir uma branch local</td>
    <td><code>git branch -d branch_new</code></td>
  </tr>
  <tr>
    <td>Excluir uma branch remota</td>
    <td><code>git push origin --delete branch_name</code></td>
  </tr>
  <tr>
    <td>Fazer um commit sem precisar adicionar (git add .)</td>
    <td><code>git commit -am "Mensagem do commit"</code></td>
  </tr>
  <tr>
    <td>Resetar para um commit anterior (cuidado!)</td>
    <td><code>git reset --hard &lt;commit_hash&gt;</code></td>
  </tr>
  <tr>
    <td>Baixar atualizações do repositório remoto sem aplicar</td>
    <td><code>git fetch</code></td>
  </tr>
  <tr>
    <td>Puxar as últimas atualizações e aplicar no código local</td>
    <td><code>git pull origin main</code></td>
  </tr>
</table>
