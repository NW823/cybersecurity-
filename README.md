# 🛡️ Técnicas de Ataques Hackers — Guia Educacional
Project cybersecurity, Hacking, learning

Este repositório tem como objetivo documentar e explicar, de forma **educacional**, diferentes técnicas utilizadas em ataques cibernéticos. O conteúdo aqui presente é voltado para **profissionais de segurança da informação**, **pesquisadores**, **estudantes** e demais interessados em entender como funcionam os principais vetores de ataque, com o intuito de **fortalecer defesas e promover a conscientização digital**.
Todos os dados foram tirados do curso de segurança da informação do **dicionario da informática**, preparatório para concursos

> ⚠️ **AVISO LEGAL**  
> Este repositório é estritamente para fins **educacionais** e de **pesquisa em segurança cibernética**. Não apoiamos nem incentivamos o uso das informações aqui contidas para atividades ilegais ou antiéticas.

## 🔍 Conteúdo

### 🦠 Malware
-**Spyware**: Programa espião, pode ser usado de forma legítima ou malicionsa, ele é um tipo de malware que monitora as atividades de um sistema e envia informações para o hacker 

-**Keylogger**: um tipo de Spyware que captura teclas digitadas no teclado (Um sistema de defesa contra o keylogger é o teclado virtual).

-**Screenlogger**: um tipo de Spyware que armazena o que é clicado no mouse, tirando print e mandando ao atacante. 

-**Rootkits**: Ocultação de processos maliciosos, inserindo um malware que o sistema não detecta como malware. O sistema identifica como um se fosse o administrador executando funções, sendo que dentro do rootkit tem varias verramentas poderosas de hacking. 

-**Ransomware**: infecta o computador da vitima tendo acessos a todos os dados, o sistema é criptografado impedindo da vitima acessar o próprio sistema e é cobrado um resgate daquele sistema ou conta. 

-**Ransonware Crypto**: impede que acesse seus dados e depois cobra transferência de bitcoin como moeda de troca para devolução da conta 

-**Ransonware Locker**: impede que o usúario tenha acesso ao seu próprio computador, depois é cobrado para devolver o acesso ao próprio computador

obs: as vezes o ransonware é feito com chantagem e persuasão para chegar a um outro intermediário ex: algum conseguir um dado de um funcionario da empresa e pedir para passar alguma informação valiosa da empresa através de chantagem, e mesmo que seja a minima informação, pode fazer muita diferença 

-**Bot**: Programa malicioso que dispõe de mêcanismo de comunicação com o invasor permitindo ser controlado remotamente, também chamado de zumbi, pois ele busca falhas de um computador e vai se copiando criando redes botnet, essas redes podem ser utilizadas para ataques:. 
-DDoS ou DoS, Envio de SPAM e Furto de dados. 

![image](https://github.com/user-attachments/assets/d22feb1b-9689-450d-8b3d-81fb913a04bf)

-**Scareware**: Engana o usuário com alertas falsos para instalar softwares maliciosos, ex: "Você está com vírus, para remover baixe tal arquivo..."
![image](https://github.com/user-attachments/assets/ca92c36d-152e-4cd6-91c5-175be5ee7d13)


-**PUP (Potentially Unwanted Program)**:Softwares que embora não seja malicioso, realizam ações indesejadas como exibir anúncios ou alterar configurações do sistema. 

-**Shareware**: Softwares que se dizem gratuitos ou de demonstração, mas embutem funções ocultas ou comportamentos indesejados.

-**Backdoor**: Deixa portas vulneraveis no computador da vítima, a fim de facilitar a invasão do hacker, permitindo acesso remoto não autorizado a um sistema. 

-**Trojan (Cavalo de Troia)**: Disfarçado de software legítimo, abre portas para outros malwares. Pode instalar programas malicioso, ou abrir uma backdoor para invasão de um hacker 
-Trojan Downloader: instala um código malicioso vindo da internet 
-Trojan Dropper: instala outros códigos maliciosos embutidos no próprio código trojan 
-Trojan Backdoor: Abre portas facilitando a invasão de outros hackeres ou o próprio hacker, basicamente abre as portas facilitando a sua entrada. 
-Trojan DoS: Instala ferramenta de negação de serviços 
-Trojan Destrutivo: Altera/Apaga arquivos e diretórios, formata o disco rígido, deixando o PC fora de operação 
-Trojan Clicker: Redireciona a navegação de usuário a sites específicos para propaganda ou quantidade de acesos. 
-Trojan Proxy: Instala um servidor de proxy, possibilitando que o computador, seja utilizado para navegação anônima e para envio de SPAM 

### 🎭 Engenharia Social
-**Phishing**: Site, mensagem, email falso que simula um verdadeiro - usam a engenharia social para enganar e roubar dados pessoais. 

-**Pharming**: Um tipo de Phishing que acaba redirecionando a navegação do usuário para sites falsos usando serviço de DNS. 

-**Whaling**: Ataque que o criminoso se disfarça de um participante de alto escalão para atingir outras pessoas. 

-**Advance Fee Fraud**: A Fraude de Taxa Antecipada é um tipo de fraude em que os indivíduos são solicitados a pagar uma taxa antecipadamente em troca de um pagamento maior prometido, que nunca se materializa. Fraude que o golpista induz a pessoa a oferecer informações confidenciais ou pagamento com a promessa de receber beneficio no futuro. 

-**Clickjacking**: Técnica que engana o usuário para clicar em algo que aparenta ser inofensivo. Ele cria uma camada invisivel entre a interface do usuario e o sistema web; ele cria uma camada, uma cópia imperceptivel conseguindo todos os dados. O sistema não vão para o sistema de verificação do banco; eles vão para conta do hacker. 

-**Typosquatting**: Registro de domínios com erros de digitação comuns para capturar acessos e aplicar golpes.

### 🌐 Ataques em Rede
-**Man-in-the-Middle**: Dados trocados entre duas partes são interceptadas e possívelmente alterados ou registrados pelo atacante sem que as vitimas se apercebam. Como um telefone sem fio. 

-**Sniffing**: Captura de pacotes de dados em redes. Técnica utilizada para monitorar e analisar o tráfego de dados que circula em uma rede de computadores.

-**Spoofing (IP, ARP, DNS)**: Conhecida como técnica do mascaramento, falsificação de identidades digitais na rede. Envolve golpistas que fingem ser outra pessoa para roubar dados ou dinheiro ou espalhar malware.

-**KRACK**: Exploração da falha no protocolo WPA2 em redes Wi-Fi.Eles conseguem ler os dados criptografados. 

-**Ataque de Zero Clique**: Executado sem interação do usuário, geralmente via rede (MMS, Wi-Fi, etc.).

### 🧠 Exploração de Vulnerabilidades

-**SQL Injection**: Injeção de comandos em campos de banco de dados.

-**Cross-site Scripting (XSS)**: Execução de scripts maliciosos em sites vulneráveis.

-**Buffer Overflow**: Estouro de memória para execução arbitrária de código.

-**Zero-Day**: Exploração de falhas ainda desconhecidas pelos desenvolvedores exploits.

-**Jailbreak**: Remoção de restrições de sistemas operacionais, tornando-os vulneráveis.

-**Força Bruta**: Tentativas repetidas de senhas até encontrar a correta.

### 🎯 Ameaças Persistentes Avançadas (APT)

-**APT (Advanced Persistent Threat)**: Infiltração prolongada e sigilosa em redes corporativas ou governamentais, visando espionagem, roubo de dados ou sabotagem. Básicamente são ataques complexos perigosos, ele ferra o seu servidor e é o pesadelo de qualquer empresa. São ataques complexos e perigosos, não é fácil de fazer. 


