# guia-estudos-notebooklm-cybersec

## Contexto e Objetivos
Este é um pequeno guia de estudos criado com a ajuda do NotebookLM do Google, com o objetivo de melhorar a compreensão sobre os tipos mais comuns de cyberataques, como preveni-los, e o que fazer caso eles sejam bem-sucedidos. Ele foi otimizado para a compreensão de pessoas que não são da área, de maneira que consigam compreender não apenas os detalhes de cada ataque, mas a importância de preveni-los e detê-los em primeiro lugar.

## Curadoria de Fontes
https://www.coursera.org/articles/types-of-cyber-attacks
https://www.fortinet.com/resources/cyberglossary/types-of-cyber-attacks
https://www.crowdstrike.com/en-us/cybersecurity-101/cyberattacks/common-cyberattacks/
https://www.keepersecurity.com/blog/2023/08/30/the-most-common-types-of-cyberattacks/
https://www.fortinet.com/resources/cyberglossary/cybersecurity-statistics
https://www.fortinet.com/resources/cyberglossary/types-of-cyber-attacks

## Engenharia de Prompts e Cicatrizes

### Na conversa
- Quais são os tipos mais comuns e relevantes de ameaças cibernéticas, e como preveni-los?
- No caso de uma invasão bem-sucedida, como proceder?
- Crie um glossário com os principais conceitos aprendidos, criando grupos para cada tema, que serão localmente e globalmente sortidos em ordem alfabética

### Na geração da apresentação em slides
- Gere um resumo simples e profissional, de maneira que leigos consigam entender o que está sendo explicado e usar este material para explicar o tema a outros, não apenas em seus detalhes, mas em sua importância como um todo, tanto para os negócios como para a vida pessoal.

## Miniguia de Estudo
Link da apresentação ["The Digital Shield"](https://notebooklm.google.com/notebook/0ec9e9d4-5d5e-4004-a42c-6d4be5853196/artifact/8019ff65-24a0-49d2-829f-20b48d57eee3) aqui.
Link do [Notebook](https://notebooklm.google.com/notebook/0ec9e9d4-5d5e-4004-a42c-6d4be5853196)

### Glossário com os principais conceitos aprendidos
Este glossário organiza os principais conceitos de segurança cibernética encontrados nas fontes, divididos em temas ordenados alfabeticamente. Dentro de cada tema, os termos também seguem a ordem alfabética.

#### **1. Ameaças de Malware e Software Malicioso**

*   **Adware:** Um tipo de spyware que monitora a atividade online do usuário para determinar quais anúncios exibir, o que pode degradar o desempenho do dispositivo.
*   **Botnet:** Uma rede de computadores infectados por malware que são controlados remotamente por um "herdeiro de bots" para lançar ataques em massa.
*   **Cryptojacking:** O uso não autorizado dos recursos de um computador, geralmente através de malware, para minerar criptomoedas sem o consentimento do dono.
*   **Malware:** Termo geral para software malicioso (incluindo vírus, worms e spyware) projetado para infiltrar, danificar ou explorar sistemas.
*   **Ransomware:** Software que criptografa os dados da vítima e exige o pagamento de um resgate para fornecer a chave de descriptografia.
*   **Rootkits:** Conjunto de softwares projetados para dar ao invasor o controle total de um sistema, frequentemente criando um "backdoor" para acessos futuros.
*   **Trojan (Cavalo de Troia):** Programa que parece legítimo, mas contém código malicioso que abre brechas de segurança no sistema quando executado.
*   **Wiper Attack:** Um ataque focado em apagar ou corromper dados permanentemente em sistemas alvos, comum em contextos de conflitos geopolíticos.
*   **Worms:** Programas autorreplicáveis que se espalham por redes de computadores, explorando vulnerabilidades para danificar arquivos ou consumir recursos.

#### **2. Ataques de Rede e Conectividade**

*   **Ataque à Cadeia de Suprimentos:** Quando um criminoso explora vulnerabilidades em fornecedores terceiros para ganhar acesso à rede privada da organização principal.
*   **Ataque de Negação de Serviço (DoS/DDoS):** Tentativa de sobrecarregar um sistema com tráfego falso para torná-lo inacessível aos usuários legítimos.
*   **Birthday Attack:** Exploração de algoritmos de hash usados para verificar a autenticidade de mensagens, visando substituir uma mensagem legítima por uma falsa com o mesmo "hash".
*   **DNS Spoofing:** Alteração de registros do sistema de nomes de domínio (DNS) para redirecionar usuários de sites legítimos para sites fraudulentos.
*   **DNS Tunneling:** Técnica que utiliza consultas e respostas DNS para contornar medidas de segurança e transmitir dados ou códigos maliciosos.
*   **Eavesdropping (Intercepção):** Ato de interceptar tráfego de rede para coletar informações confidenciais, como senhas e números de cartões de crédito.
*   **Man-in-the-Middle (MITM):** Ataque onde o criminoso se posiciona entre duas partes para espionar, interceptar ou modificar as comunicações.
*   **Session Hijacking:** Ocorre quando um invasor assume uma sessão ativa entre um cliente e um servidor, substituindo o endereço IP do cliente pelo seu.

#### **3. Engenharia Social e Gestão de Identidade**

*   **Ataque de Identidade (Impersonation):** Quando um criminoso rouba dados pessoais para se passar por outra pessoa e obter acesso a sistemas ou realizar fraudes financeiras.
*   **Business Email Compromise (BEC):** Ataque onde o invasor assume a identidade de um usuário confiável para induzir funcionários a realizar pagamentos ou compartilhar dados sensíveis.
*   **Deepfake:** Falsificações geradas por inteligência artificial (vídeos, áudios ou imagens) que parecem extremamente reais, usadas para manipular a opinião pública ou cometer fraudes.
*   **Engenharia Social:** Táticas psicológicas usadas para manipular pessoas a revelarem informações confidenciais ou realizarem ações que comprometam a segurança.
*   **Phishing:** Uso de e-mails ou mensagens fraudulentas que parecem vir de fontes confiáveis para enganar vítimas e roubar dados.
*   **Pretexting:** Criação de um cenário fictício para ganhar a confiança de uma vítima e obter acesso a informações ou sistemas.
*   **Smishing:** Uma variante do phishing realizada através de mensagens de texto (SMS) fraudulentas.
*   **Spear Phishing:** Ataque de phishing altamente personalizado e direcionado a um indivíduo ou organização específica.
*   **Spoofing:** Técnica de disfarçar uma comunicação (e-mail, site, ID de chamada) para que pareça vir de uma fonte conhecida e confiável.
*   **Vishing:** Phishing realizado por meio de chamadas de voz ou mensagens de voz fraudulentas.
*   **Whaling:** Ataque de phishing direcionado especificamente a executivos de alto escalão (C-level) que possuem informações proprietárias valiosas.

#### **4. Métodos de Invasão Técnica**

*   **Ataque de Força Bruta (Brute Force):** Método de tentativa e erro para adivinhar senhas ou chaves de criptografia usando combinações sistemáticas.
*   **Backdoor:** Um ponto de entrada secreto criado em um sistema que permite aos invasores contornar a segurança normal e obter acesso remoto.
*   **Code Injection:** Ataque que consiste em inserir código malicioso em uma rede ou computador vulnerável para alterar seu curso de ação.
*   **Credential Stuffing:** Uso de listas de senhas e usuários vazados para tentar acessar contas em diferentes sites simultaneamente.
*   **Injeção de SQL (SQL Injection):** Inserção de comandos maliciosos em campos de entrada de sites para manipular bancos de dados e extrair dados.
*   **Password Spraying:** Teste de um pequeno número de senhas comuns contra muitas contas de usuários para evitar bloqueios por tentativas falhas.
*   **URL Interpretation:** Manipulação da sintaxe de endereços URL para ganhar privilégios de administrador ou acessar áreas restritas de um site.
*   **XSS (Cross-Site Scripting):** Inserção de scripts maliciosos em sites legítimos; quando o usuário clica no conteúdo, o script é executado no navegador dele.
*   **Zero-Day Attack:** Ataque que explora uma vulnerabilidade de software antes que o desenvolvedor tenha conhecimento dela ou crie uma correção.

#### **5. Práticas e Ferramentas de Segurança**

*   **Antivírus:** Software projetado para detectar, bloquear e remover vírus e malwares conhecidos antes que infectem o sistema.
*   **Autenticação de Múltiplos Fatores (MFA):** Medida que exige duas ou mais formas de verificação para conceder acesso a uma conta, aumentando a segurança além da senha.
*   **Backup:** Cópia de segurança de dados armazenada em local seguro (nuvem ou físico) para permitir a recuperação em caso de perda ou ataque.
*   **Criptografia:** Processo de codificação de informações para que apenas pessoas com a chave correta possam acessá-las.
*   **Firewall:** Ferramenta que monitora e controla o tráfego de rede, bloqueando atividades suspeitas com base em regras de segurança.
*   **Gerenciador de Senhas:** Ferramenta que armazena e protege credenciais de login de forma criptografada, ajudando na criação de senhas fortes e únicas.
*   **Zero Trust:** Modelo de segurança baseado no princípio de que nenhuma solicitação de acesso deve ser confiável por padrão, exigindo verificação contínua de todos.


## Observações
- Resolvi pegar conteúdo de fontes em inglês, pois elas geralmente são mais completas e explicativas. Porém, em alguns segmentos, há certos erros na tradução de alguns termos (como na tradução de "deception" para "decepção", cujo termo equivalente correto seria  "enganação").
- Alguns prompts a mais foram testados para ver que tipo de resoltado forneceriam. Resolvi pegar os melhores disponíveis. Busque a apresentação para um material mais polido, caso seja de sua preferência.
