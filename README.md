# Engenharia Social e Phishing: Conceitos e Desafio de Cibersegurança

### O que é Engenharia Social?

A engenharia social é uma técnica de manipulação psicológica usada por cibercriminosos para induzir vítimas a revelar informações confidenciais, como senhas, números de cartão de crédito ou dados bancários. Em vez de atacar diretamente os sistemas ou infraestruturas de segurança, a engenharia social explora a confiança humana e a falta de cautela.

As táticas de engenharia social podem envolver diversos métodos, como:

- **Vishing (Voice Phishing):** Uso de chamadas telefônicas para enganar as vítimas.
- **Baiting:** Oferecer algo de valor (como um arquivo ou programa) para atrair a vítima a clicar em links maliciosos.
- **Pretexting:** Criar um cenário falso para coletar informações sensíveis.

### E o que é Phishing?

Phishing é uma forma específica de engenharia social, onde os criminosos criam websites falsos ou enviam e-mails fraudulentos com o objetivo de enganar as vítimas e coletar informações pessoais. O termo "phishing" vem da ideia de "pescar" vítimas, usando iscas como e-mails falsos, links e páginas de login fraudulentas.

Um ataque de phishing típico envolve a criação de uma réplica de uma página legítima, como o login do Facebook, e a tentativa de enganar a vítima para que insira suas credenciais no site falso. Esses ataques podem ser realizados por e-mail, mensagens instantâneas ou através de redes sociais.

### Desafio de Clonagem de Página de Login do Facebook

Para completar este desafio de cibersegurança no Bootcamp, a tarefa foi clonar uma página de login do Facebook para entender como os ataques de phishing funcionam. A criação de uma página de login falsa, no entanto, foi feita com a finalidade de aprendizado e conscientização sobre os riscos de segurança na internet.

### Como foi feito o processo de clonagem da página de login do Facebook?

Neste projeto, utilizamos o **Setoolkit** e o **Kali Linux** para fazer a clonagem da página de login do Facebook. O processo foi realizado seguindo os seguintes passos:

1. **SetoolKit:**
   - Inicializamos o Setoolkit no Kali Linux para realizar a clonagem da página.
   
2. **Website Attack Vectors:**
   - Selecionamos a opção "Website Attack Vectors" dentro do Setoolkit para iniciar o ataque.
   
3. **Credential Harvester Attack Method:**
   - Optamos pela opção "Credential Harvester Attack Method" para capturar credenciais da vítima.

4. **Site Cloner:**
   - Selecionamos a opção "Site Cloner", que permite clonar uma página da web, neste caso, a página de login do Facebook.

5. **Configuração do servidor:**
   - Escolhemos o servidor que vai rodar o ataque, neste caso, utilizando o IP da minha máquina: `192.168.1.104`.

6. **URL da página de login:**
   - Inserimos a URL em HTTP da página que desejamos clonar (login do Facebook).

Esse processo permitiu a criação de uma réplica da página de login do Facebook, com o objetivo de estudar como os ataques de phishing funcionam e como proteger os usuários contra essas ameaças.

### Considerações Importantes

Embora o desafio tenha envolvido a clonagem de uma página de login, é importante ressaltar que ataques de phishing são ilegais e antiéticos. A intenção do desafio foi puramente educacional, e o conhecimento adquirido deve ser utilizado para a proteção contra esses tipos de ataques.

### Como se Proteger contra Phishing?

- **Verifique a URL:** Certifique-se de que a URL do site seja legítima e tenha o prefixo "https://", que indica uma conexão segura.
- **Desconfie de e-mails suspeitos:** Não clique em links ou abra anexos de remetentes desconhecidos.
- **Use autenticação de dois fatores (2FA):** Adicionar uma camada extra de segurança ajuda a proteger suas contas.
- **Mantenha seu software atualizado:** Garanta que seu navegador e sistema operacional estejam sempre atualizados para proteger contra vulnerabilidades.

### Por que esse estudo é importante?

Estudar engenharia social e phishing é crucial para entender as ameaças que os usuários enfrentam diariamente na internet. Esses tipos de ataques estão entre as principais técnicas utilizadas por cibercriminosos para comprometer dados e sistemas. Ao aprender como esses ataques funcionam, é possível implementar medidas de segurança mais eficazes, tanto para prevenir a exploração de vulnerabilidades quanto para educar os usuários sobre como se proteger.

Além disso, com o aumento das tecnologias e da interconectividade, ataques de phishing estão se tornando cada vez mais sofisticados. Ao entender e praticar a identificação desses ataques, profissionais de segurança da informação podem melhorar suas habilidades e contribuir para ambientes digitais mais seguros, protegendo dados pessoais e corporativos.
