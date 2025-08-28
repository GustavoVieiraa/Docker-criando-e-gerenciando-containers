<div align="center">
  <table>
    <tr>
      <td align="center">
        <!-- Link para o Certificado -->
        <a href="https://cursos.alura.com.br/certificate/gustavo-vieira17/docker-criando-gerenciando-containers">
          <img loading="lazy" width="128px" src="https://www.alura.com.br/assets/api/cursos/docker-criando-gerenciando-containers.svg" />
        </a>
        <h4>Curso</h4>
      </td>
      <td align="center">
        <!-- Link para o Certificado -->
        <a href="https://cursos.alura.com.br/certificate/gustavo-vieira17/docker-criando-gerenciando-containers">
          <img loading="lazy" width="128px" src="https://static.vecteezy.com/system/resources/previews/028/293/920/original/trophy-icon-3d-rendering-illustration-png.png" />
        </a>
        <h4>Certificado</h4>
      </td>
    </tr>
  </table>
  <h1>Docker: criando e gerenciando containers 📘</h1>
</div>
<p align="right">
  <img loading="lazy" src="https://img.shields.io/badge/CARGA_HORARIA-10_HORAS-blue?style=for-the-badge"/>
  <img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO!&color=GREEN&style=for-the-badge"/>
</p>

<div>
  <h2>Conhecimentos adquiridos em Docker:</h2>
  <ul>
    <li><h3>Compreensão de containers e sua arquitetura, incluindo conflitos e versionamento.</h3></li>
    <li><h3>Instalação e configuração do Docker em Windows e Linux, preparando ambientes para desenvolvimento.</h3></li>
    <li><h3>Uso dos primeiros comandos básicos: docker run, docker exec, mapeamento de portas e Docker Hub.</h3></li>
    <li><h3>Criação e gerenciamento de imagens, Dockerfile, ARG vs ENV e publicação no Docker Hub.</h3></li>
    <li><h3>Persistência de dados com bind mounts, volumes e tmpfs, compreendendo vantagens e limitações.</h3></li>
    <li><h3>Comunicação entre containers utilizando redes bridge, host e none, integrando aplicações e bancos.</h3></li>
    <li><h3>Orquestração de containers com Docker Compose, definição de serviços e parâmetros, coordenando ambientes multi-container.</h3></li>
    <li><h3>Noções sobre carreira em DevOps e aplicação prática de Docker em projetos reais.</h3></li>
  </ul>

  <div>
  <h2>Comandos Docker aprendidos:</h2>

  <div>
    <h3>Gerenciamento de Containers</h3>
    <ul>
      <li><code>docker ps</code>: Mostra os containers em execução.</li>
      <li><code>docker ps -a</code> ou <code>docker container ls -a</code>: Mostra todos os containers, incluindo os finalizados.</li>
      <li><code>docker run ubuntu sleep 1d</code>: Mantém o container Ubuntu ativo por um dia.</li>
      <li><code>docker stop [container]</code>: Interrompe a execução de um container.</li>
      <li><code>docker start [container]</code>: Reinicia um container parado.</li>
      <li><code>docker exec -it [container] bash</code>: Interage com o container em tempo real.</li>
      <li><code>docker pause [container]</code> / <code>docker unpause [container]</code>: Pausa e retoma a execução de um container, mantendo seu estado.</li>
      <li><code>docker rm [container]</code>: Remove um container.</li>
      <li><code>docker stop $(docker container ls -q)</code>: Para todos os containers em execução.</li>
      <li><code>docker run -it [imagem] bash</code>: Inicia um container com terminal interativo.</li>
    </ul>
  </div>

  <div>
    <h3>Gerenciamento de Imagens</h3>
    <ul>
      <li><code>docker build -t nome/imagem:tag .</code>: Constrói uma imagem Docker.</li>
      <li><code>docker run -p host_port:container_port -d nome/imagem:tag</code>: Executa um container mapeando portas em modo detached.</li>
    </ul>
  </div>

  <div>
    <h3>Persistência de Dados</h3>
    <ul>
      <li><code>docker run -it -v /caminho/no/host:/caminho/no/container ubuntu bash</code>: Mapeia volumes do host para o container.</li>
      <li><code>docker run -it --mount type=bind,source=/caminho/no/host,target=/caminho/no/container ubuntu bash</code>: Mapeamento semântico de volumes (recomendado).</li>
    </ul>
  </div>

  <div>
    <h3>Nomes e Redes de Containers</h3>
    <ul>
      <li><code>docker run --name meu-container [imagem]</code>: Define um nome personalizado para o container.</li>
      <li><code>docker network create --driver bridge minha-bridge</code>: Cria uma rede bridge personalizada.</li>
      <li><code>docker run --network minha-bridge [imagem]</code>: Conecta um container a uma rede específica.</li>
    </ul>
  </div>
</div>

</div>
