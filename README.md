<h1 align="center">Olá 👋, eu sou o Kellvin Correia</h1>
<h3 align="center">🚀 Desenvolvedor Full-Stack em Formação | Aluno Alpha Edtech</h3>

<p align="center">
  Profissional de tecnologia em transição de carreira, com uma bagagem sólida de quase 3 anos em Qualidade de Software (QA). Atualmente, estou imerso no programa de formação da <b>Alpha Edtech</b>, um treinamento intensivo de 18 meses focado em me tornar um desenvolvedor de alta performance, com conhecimentos em JavaScript, Python, Bancos de Dados e IA.
</p>

---

### 📫 Conecte-se Comigo

<div>
  <a href="https://linkedin.com/in/kellvin-correia-alves" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:kellvin.correia@gmail.com"><img src="https://img.shields.io/badge/Gmail-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
</div>

---

### 💻 O Que Estou Aprendendo na Formação Full-Stack

<p>Abaixo estão as tecnologias que estou estudando intensivamente no programa, além da minha experiência anterior.</p>

**Linguagens e Ecossistema**

![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![Node.JS](https://img.shields.io/badge/Node.js-%23339933.svg?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

**Frameworks e Bibliotecas (Front-end)**

![React](https://img.shields.io/badge/React-%2361DAFB.svg?style=for-the-badge&logo=react&logoColor=black)

**Bancos de Dados**

![MySQL](https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%234169E1.svg?style=for-the-badge&logo=postgresql&logoColor=white)

**Ferramentas e Boas Práticas**

![Git](https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)
![Metodologias Ágeis](https://img.shields.io/badge/Metodologias%20Ágeis-%23000000.svg?style=for-the-badge&logo=agile&logoColor=white)

---

### ⭐ Minha Bagagem Anterior (QA & Automação)

<p>Minha experiência de quase 3 anos como Analista de Qualidade me proporcionou uma visão crítica e estratégica sobre o desenvolvimento de software.</p>

![Cypress](https://img.shields.io/badge/Cypress-%2317202C.svg?style=for-the-badge&logo=cypress&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-%2343B02A.svg?style=for-the-badge&logo=selenium&logoColor=white)
![Appium](https://img.shields.io/badge/Appium-%23689F63.svg?style=for-the-badge&logo=appium&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-%23FF6C37.svg?style=for-the-badge&logo=postman&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-%23D24939.svg?style=for-the-badge&logo=jenkins&logoColor=white)
![Testes Manuais](https://img.shields.io/badge/Testes%20Manuais-%23E34F26.svg?style=for-the-badge&logo=book&logoColor=white)

---

# Resumo Git

<details>
  <summary><strong>Git - Conceitos básicos</strong></summary>

- Sistema de controle de versão distribuído.  
- Guarda histórico de alterações em commits com hash único.  
- Diferencia Working Tree, Index (Staging Area) e último commit.  

</details>

<details>
  <summary><strong>Git - Configuração inicial</strong></summary>

- `git config --global user.name "Seu Nome"`  
- `git config --global user.email "seu@email"`  
- `git config --global core.editor nano` (ou notepad, etc.)  
- `git config --list` para ver as configs.  

</details>

<details>
  <summary><strong>Git - Fluxo básico local</strong></summary>

- `git init` - cria repositório na pasta.  
- `git status` - mostra estado dos arquivos.  
- `git add <arquivo>` / `git add .` - manda pro Index.  
- `git commit -m "mensagem"` - cria commit.  
- `git log` / `git log --oneline` - lista commits.  
- `.gitignore` - define o que não será rastreado.  

</details>

<details>
  <summary><strong>Git - Estados de arquivo</strong></summary>

- Untracked: arquivo novo, ainda sem `git add`.  
- Staged (Changes to be committed): já foi `git add`.  
- Modified (Changes not staged): alterado depois do `git add`.  
- Clean: igual ao último commit.  

</details>

<details>
  <summary><strong>Git - Branches e HEAD</strong></summary>

- Branch é um ponteiro para um commit (`main`, `master`, `feature-x`).  
- HEAD aponta para a branch atual.  
- Commits avançam a branch que HEAD está selecionando.  

</details>

<details>
  <summary><strong>Git - Comandos de branch</strong></summary>

- `git branch` - lista branches.  
- `git branch <nome>` - cria branch.  
- `git checkout <nome>` - troca de branch.  
- `git checkout -b <nome>` - cria e troca de branch.  
- `git branch -d <nome>` - apaga branch local.  

</details>

<details>
  <summary><strong>Git - Merge e conflitos</strong></summary>

- `git merge <branch>` - mescla branch passada na atual.  
- Fast-forward: só anda o ponteiro.  
- Three-way: cria commit de merge.  
- Conflitos: editar regiões `<<<<<<<`, `=======`, `>>>>>>>`, depois `git add` e `git commit`.  

</details>

<details>
  <summary><strong>Git - Stash e correções</strong></summary>

- `git stash` - guarda mudanças locais e limpa Working Tree.  
- `git stash apply` / `git stash pop` - reaplica stash (pop apaga).  
- `git reset --hard <hash>` - volta branch e arquivos para um commit.  
- `git reset --mixed <hash>` - volta branch, mas mantém mudanças não commitadas.  

</details>

<details>
  <summary><strong>Git - Remoto / GitHub</strong></summary>

- `git remote add origin <url>` - adiciona remoto.  
- `git remote -v` - lista remotos.  
- `git push --set-upstream origin main` - primeiro push da branch.  
- `git push` - envia commits depois de configurado.  
- `git clone <url>` - clona repositório remoto.  
- `git fetch` - baixa novidades do remoto.  
- `git pull` - `fetch` + `merge` na branch atual.  

</details>

<details>
  <summary><strong>Git - Colaboração e Pull Request</strong></summary>

- Fluxo: criar branch → commits → push da branch → abrir Pull Request.  
- PR serve para revisão, comentários e aprovação antes do merge.  
- Depois do merge: `git checkout main` + `git pull` para atualizar localmente.  

</details>

---

# Resumo Redes

<details>
  <summary><strong>Redes - Conceitos básicos</strong></summary>

- Rede de computadores: dispositivos interligados para compartilhar dados e recursos.  
- Vantagens: compartilhamento de recursos, comunicação rápida, centralização de serviços.  

</details>

<details>
  <summary><strong>Tipos de rede (alcance)</strong></summary>

- LAN: pequena área (sala, prédio, campus).  
- MAN: área metropolitana (vários prédios / campus grande).  
- WAN: grandes distâncias, interliga várias LANs.  

</details>

<details>
  <summary><strong>Topologias de rede</strong></summary>

- Barramento (Bus): todos no mesmo meio compartilhado.  
- Estrela (Star): hosts ligados a um ponto central (switch/hub).  
- Anel (Ring): dispositivos em circuito fechado.  

</details>

<details>
  <summary><strong>Meios de transmissão</strong></summary>

- Par trançado (UTP/STP): cobre, muito usado em LAN.  
- Fibra óptica: alta capacidade, longa distância, imune a interferência.  
- Wireless (Wi‑Fi): rádio, usa access point.  

</details>

<details>
  <summary><strong>Equipamentos de rede</strong></summary>

- Repetidor: regenera sinal.  
- Hub: concentra e replica tráfico (camada física).  
- Switch: comuta por MAC (camada 2).  
- Bridge: separa domínios de colisão, também por MAC.  
- Roteador: encaminha por IP entre redes (camada 3).  
- Access Point: fornece Wi‑Fi para rede cabeada.  
- Modem: adapta sinal do provedor para a rede local.  

</details>

<details>
  <summary><strong>Modelos de camadas</strong></summary>

- OSI (7 camadas): Física, Enlace, Rede, Transporte, Sessão, Apresentação, Aplicação.  
- TCP/IP (4 camadas): Acesso à Rede, Internet, Transporte, Aplicação.  
- Encapsulamento: dados → segmento → pacote → quadro → bits.  

</details>

<details>
  <summary><strong>Protocolos principais</strong></summary>

- Aplicação: HTTP, HTTPS, FTP, SMTP, POP3, IMAP, DNS, SSH, Telnet.  
- Transporte: TCP (confiável), UDP (rápido, sem garantia).  
- Rede: IP, ICMP, ARP.  
- Enlace: Ethernet, Wi‑Fi, PPP, etc.  

</details>

<details>
  <summary><strong>Endereços e serviços</strong></summary>

- IP: identifica host (ex.: 192.168.0.10).  
- Máscara: define parte de rede/host (ex.: 255.255.255.0).  
- Gateway padrão: roteador para sair da rede local.  
- DNS: converte nomes em endereços IP.  

</details>

<details>
  <summary><strong>Arquiteturas lógicas</strong></summary>

- Cliente-servidor: servidores dedicados, clientes consomem serviços.  
- Ponto‑a‑ponto (P2P): nós se comunicam diretamente, podendo ser cliente e servidor.  

</details>

<details>
  <summary><strong>Noções de segurança em redes</strong></summary>

- Segmentação com VLANs para separar tráfego.  
- Firewalls filtrando pacotes entre redes.  
- Uso de HTTPS, SSH e VPN para criptografar dados em trânsito.  

</details>
