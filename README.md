<h1>Alternando-JDK-no-Ubuntu</h1>
<p>Muitas vezes é preciso ter várias versões do JDK instaladas no sistema operacional. E de acordo com a necessidade alternar entre uma ou outra versão.</p>
<h2>COMO FUNCIONOU??</h2>
<p>No terminal digite o comando <strong>sudo update-alternatives --list java</strong> e veja quais JDK podem ser selecionadas</p>
<p>Faça o <a href="https://www.java.com/pt_BR/">download</a> e instale a versão desejada.</p>
<p>O comando update-alternatives -- install /usr/bin/java java /LocalDoSeuNovoJDK/bin/java numeroDaSeleção - <em>essa é a ordem para seleção das JDK sendo que o número 0 será a JDK inicializada automaticamente</em></p>
<p>No terminal digite o comando <strong>sudo update-alternatives --config java</strong> e escolha a versão do JDK</p>