# Hackers do Bem Red Team: Estudo de Casos

Este repositório contém o estudo de casos desenvolvido como parte da conclusão do curso de Cibersegurança do programa governamental "Hackers do Bem". A especialização escolhida foi Red Team, com foco em testes de penetração e simulação de ataques cibernéticos para identificar vulnerabilidades e melhorar a segurança de sistemas. O material inclui análises práticas e metodologias utilizadas durante a formação, voltadas para a proteção contra ameaças digitais.

Mais informações sobre o programa: https://hackersdobem.org.br/



# BYFRANKE CYBER SECURITY 
**Cyber Threat Intelligence / Pentest / Threat Hunting**

Cliente: VENDE TUDO LTDA

Responsável: RNP

Tempo: 10 hrs

Data: 09/09 até o dia 22/09/2023

Custo: 1 Certificado

**A VENDE TUDO LTDA** é uma empresa de varejo que opera tanto em lojas físicas quanto no e-commerce em todo o território brasileiro, oferecendo uma ampla variedade de produtos para o consumidor final. O objetivo deste teste de penetração é avaliar a segurança das principais plataformas digitais da VENDE TUDO LTDA, incluindo o portal de vendas online, o sistema de gestão de lojas e a infraestrutura de TI associada. Este teste visa identificar vulnerabilidades que possam ser exploradas por atacantes e fornecer recomendações para mitigação dos riscos.



**Tipo de Pentest:**

[ ] White Box

[x] Black Box



**Escopo**

O teste de penetração cobrirá os seguintes elementos da infraestrutura da VENDE TUDO LTDA:
**• Portal de Vendas Online:** Utilizado por clientes para compras, consultas de produtos e pagamentos.

**• Infraestrutura de TI:** Inclui os servidores internos e a rede corporativa, que dão suporte às operações de e-commerce e gestão interna.

Dada a criticidade dos sistemas envolvidos, será realizado um teste de penetração web no portal de vendas e um teste de intrusão na rede interna para avaliar a segurança dos sistemas de back-end e da infraestrutura de TI.



**Incluídos no Escopo:**

**• Portal de Vendas Online:** Testes de SQL Injection, Cross-Site Scripting (XSS), controle de sessão e autenticação.

**• Sistema de Gestão de Lojas:** Avaliação de controle de acesso, vulnerabilidades de APIs e autenticação de usuários.

**• Infraestrutura de TI:** Varredura de vulnerabilidades em servidores críticos, análise da VPN corporativa e segmentação da rede.



**Exclusões:**

• Sistemas de terceiros (plataformas de pagamento externas).

• Dispositivos e sistemas dos clientes que utilizam os serviços da VENDE TUDO LTDA.


  
**Responsabilidade:**

• O teste de penetração será conduzido pela equipe de segurança designada, mas a responsabilidade pela implementação de correções e melhorias após a identificação das vulnerabilidades é exclusiva da empresa contratante.



**Comunicação com os Envolvidos**

As principais partes envolvidas no teste de penetração são:

**Diretor de TI:** José Pereira, responsável pela aprovação do escopo e acompanhamento do teste.

**Gerente de Segurança da Informação:** Carla Lima, responsável pela coordenação das atividades de segurança.

**Equipe Jurídica:** Apoio na elaboração do NDA e do contrato de prestação de serviços.



# Plano de Teste de Penetração

O plano inclui:

**Reconhecimento:** Coleta de informações sobre a infraestrutura e sistemas da empresa.

**Escaneamento de Vulnerabilidades:** Uso de ferramentas como OWASP ZAP.

**Exploração:** Tentativas controladas de exploração das vulnerabilidades encontradas.

**Relatório:** Documentação detalhada dos achados e recomendações de mitigação.



**ACORDO DE NÃO DIVULGAÇÃO (NDA)**

Partes:

**Divulgadora:** VENDE TUDO LTDA, CNPJ [XXX.XXX.XXX/0001-XX], com sede em [vendetudo.com].

**Receptora:** [Nome da Empresa de Segurança Cibernética ou Consultor], CNPJ [XXX.XXX.XXX/0001-XX], com sede em [github.com/byfranke].


**Definição de Informações Confidenciais:**

Este Acordo de Não Divulgação refere-se a todas as informações confidenciais, técnicas, comerciais, operacionais, códigos-fonte, credenciais, relatórios e qualquer outro dado sensível que venha a ser compartilhado entre as partes durante o teste de penetração ou outro tipo de serviço prestado pela Receptora.

**Obrigações da Receptora:**

A Receptora concorda em:

• Manter todas as Informações Confidenciais em sigilo absoluto.

• Usar as Informações Confidenciais exclusivamente para os fins do serviço contratado pela Divulgadora.

• Não divulgar nenhuma Informação Confidencial a terceiros sem autorização prévia por escrito da Divulgadora.


**Exceções:**

As obrigações acima não se aplicam a informações que:

• Se tornem públicas sem violação deste Acordo.

• Já eram conhecidas pela Receptora antes de serem divulgadas pela Divulgadora.

• Foram legalmente obtidas de terceiros sem restrição de divulgação.



**Resolução de Disputas:**

Qualquer disputa decorrente deste Acordo será resolvida sob a jurisdição dos tribunais de Belo Horizonte - MG.

**Assinaturas:**

**Divulgadora**

VENDE TUDO LTDA

Nome: ________________________

Cargo: ________________________

Assinatura: ____________________

Data: _________________________


**Receptora**

BYFRANKE

Nome: ________________________

Cargo: ________________________

Assinatura: ____________________

Data: _________________________


# Relatório de Vulnerabilidades e Evidências

Durante a análise do site vendetudo.com, foram identificadas vulnerabilidades críticas que podem ser exploradas por agentes mal-intencionados, comprometendo a integridade e a segurança dos dados da empresa.

**Vulnerabilidades Identificadas:**

Vulnerabilidade: CVE-2023-51385 Score: 6.5 Fonte: https://vulners.com/cve/CVE-2023-51385

Vulnerabilidade: CVE-2023-48795 Score: 5.9 Fonte: https://vulners.com/cve/CVE-2023-48795

Vulnerabilidade: CVE-2023-51384 Score: 5.5 Fonte: https://vulners.com/cve/CVE-2023-51384

Vulnerabilidade: CVE-2024-40898 Score: 7.5 Fonte: https://vulners.com/cve/CVE-2024-40898

Vulnerabilidade: CVE-2024-6387  Score: 8.1 Fonte: https://vulners.com/cve/CVE-2024-6387

Vulnerabilidade: CVE-2023-38408 Score: 9.8 Fonte: https://vulners.com/cve/CVE-2023-38408

Vulnerabilidade: CVE-2023-28531 Score: 9.8 Fonte: https://vulners.com/cve/CVE-2023-28531

Vulnerabilidade: CVE-2024-40898 Score: 7.5 Fonte: https://vulners.com/cve/CVE-2024-40898

Vulnerabilidade: CVE-2024-40725 Score: 5.3 Fonte: https://vulners.com/cve/CVE-2024-40725

**Principais Descobertas**

Exposição de Arquivos Sensíveis: O arquivo robots.txt do site revela diretórios críticos, como "backups" e ".git", que contêm informações confidenciais. No diretório de backups, foi encontrado um arquivo de banco de    dados com informações sensíveis de clientes, incluindo nomes, CPFs e dados de cartão de crédito.

Falha de Segurança no Painel Administrativo: Um arquivo acessível (admin.php.txt) contém um hash MD5 da senha de administrador, o qual foi facilmente quebrado devido à fraqueza da senha. Com isso, foi possível acessar o painel administrativo.

Ausência de Proteção contra Ataques de Força Bruta: O mecanismo de autenticação do painel não implementa proteções adequadas contra ataques de força bruta, o que pode comprometer a segurança das contas de administrador.

Execução de Comandos Arbitrários: O painel administrativo permite o upload de arquivos sem a devida validação, possibilitando o envio de scripts maliciosos. Também foi identificado o uso de uma função Exec sem qualquer tipo de filtragem, permitindo a execução de comandos no servidor.

Evidência: Um exemplo prático foi o upload do arquivo malicioso shell.php, que nos permitiu a execução remota de comandos no servidor.

![Screenshot 2025-01-15 at 17 29 46](https://github.com/user-attachments/assets/b689630e-3445-4738-a237-d916d2b602b6)


**Exposição de Diretórios Sensíveis:**

Durante a análise, o arquivo robots.txt do domínio vendetudo.com revelou diretórios que contêm informações críticas, como os diretórios "backups" e ".git". Esses diretórios armazenam dados confidenciais, incluindo conversas de administradores e, no diretório de backups, um arquivo de banco de dados exposto com informações sensíveis dos clientes, como nomes, CPFs e detalhes de cartões de crédito.

![Screenshot 2025-01-15 at 17 30 53](https://github.com/user-attachments/assets/7f7c6590-d807-4815-807d-51df52e4c0f2)

![Screenshot 2025-01-15 at 17 31 41](https://github.com/user-attachments/assets/bf1abacf-357e-4691-8664-bea556802167)

![Screenshot 2025-01-15 at 17 31 51](https://github.com/user-attachments/assets/b9ee6dbb-f1b3-4ce7-9a35-38a86a3dc4c4)

![Screenshot 2025-01-15 at 17 32 09](https://github.com/user-attachments/assets/0a069f23-e31e-4e22-992f-6d77013f0b12)

*Dados fictícios*

**Exposição de Credenciais de Acesso:**

No diretório /backups/, foi identificado o arquivo /admin.php.txt, que contém um hash MD5 da senha do painel administrativo. Devido à simplicidade da senha, o hash foi facilmente quebrado utilizando ferramentas online, permitindo o acesso ao painel de administração do sistema.


![Screenshot 2025-01-15 at 17 33 27](https://github.com/user-attachments/assets/856f26e0-dedb-499d-8d33-600748b2e9a5)

![Screenshot 2025-01-15 at 17 33 40](https://github.com/user-attachments/assets/3d1f6016-29c2-469e-9c13-74d84a0430af)


**Vulnerabilidades no Mecanismo de Autenticação:**

Após obter acesso ao painel administrativo utilizando a senha comprometida, foram identificadas outras vulnerabilidades no método de autenticação. Especificamente, não há implementações de mecanismos de proteção contra ataques de força bruta, o que pode permitir tentativas ilimitadas de login sem qualquer mitigação.

![Screenshot 2025-01-15 at 17 39 23](https://github.com/user-attachments/assets/1e1f2cad-2749-4b38-8b80-f806cd483c5e)

![Screenshot 2025-01-15 at 17 39 36](https://github.com/user-attachments/assets/020d3c12-8dab-403a-bc1e-210899ef44dc)

**Falta de Validação no Upload de Arquivos:**

Durante a análise do painel administrativo, foi constatado que não há mecanismos de validação para os arquivos enviados ao servidor. Essa ausência de controles permite o upload de arquivos maliciosos, como scripts PHP, que podem ser executados diretamente no servidor, representando um risco significativo à segurança da aplicação.

![Screenshot 2025-01-15 at 17 41 02](https://github.com/user-attachments/assets/6adc4545-8a9b-40f4-8fbc-6217a39999c0)

*note o arquivo shell.php*

**Execução Remota de Comandos:**

Ao explorar o painel administrativo, identificamos a função Exec, que não possui filtros ou restrições adequadas. Isso permite a execução de comandos diretamente no servidor, representando uma grave vulnerabilidade. Durante o teste, foi possível enviar um comando que nos concedeu controle remoto do servidor.

![Screenshot 2025-01-15 at 17 41 52](https://github.com/user-attachments/assets/dd456427-a171-4931-a4a2-ddd34be62826)

![Screenshot 2025-01-15 at 17 42 03](https://github.com/user-attachments/assets/39837bb1-5574-4f64-95aa-bd71d588bae8)

![Screenshot 2025-01-15 at 17 42 10](https://github.com/user-attachments/assets/ced468a5-7790-48ad-af4b-c6cfa013c624)

![Screenshot 2025-01-15 at 17 42 16](https://github.com/user-attachments/assets/ffee7a5f-6e3f-458e-a848-ddb4f4d3ceab)

![Screenshot 2025-01-15 at 17 42 32](https://github.com/user-attachments/assets/ccbb3997-7738-45e1-856b-394306a39873)

![Screenshot 2025-01-15 at 17 42 43](https://github.com/user-attachments/assets/6ddcc51b-0595-491b-980e-1ffabcb0c00f)


**Recomendações:**

• Revisar as permissões do arquivo robots.txt para ocultar diretórios sensíveis.

• Implementar mecanismos de proteção contra ataques de força bruta, como o uso de CAPTCHA e limites de tentativas de login.

• Fortalecer a política de senhas e utilizar métodos de hashing mais seguros, como bcrypt ou Argon2.

• Adicionar validações robustas para uploads de arquivos e limitar a execução de comandos no servidor.
