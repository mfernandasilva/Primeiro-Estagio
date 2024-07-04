# Especificação de Projeto 

O desenvolvimento da plataforma "Primeiro Estágio" é motivado pela crescente necessidade de soluções que facilitem a conexão entre estudantes em busca de oportunidades de estágio e empresas que oferecem essas vagas. Para garantir que a plataforma atenda às necessidades de seus usuários, serão utilizadas técnicas como entrevistas com estudantes e empresas, pesquisas de mercado e a criação de personas para entender profundamente as expectativas e desafios enfrentados pelos usuários.

## Personas 

<figure style="display: flex; align-items: flex-start;">
  <img src="./img/ana.jpg" alt="Image description" width="180" height="200" style="margin-right: 20px;">
  <figcaption> <b>Ana Patricia</b>:<br><br>
Ana Patricia tem 21 anos e está cursando Administração na Universidade Federal de Minas Gerais. Ela está no 4º período e está procurando um estágio para ganhar experiência prática na área de finanças e marketing. Ana é uma estudante dedicada e busca uma oportunidade que lhe permita aplicar seus conhecimentos teóricos em um ambiente de trabalho real. Ela deseja encontrar uma plataforma que facilite a busca por estágios relevantes, permitindo-lhe filtrar vagas por área de interesse e localização. Além disso, Ana valoriza a transparência e deseja receber feedback sobre suas candidaturas para melhorar suas chances de sucesso. Seus principais desafios incluem competir com outros estudantes pela mesma vaga e garantir que suas habilidades sejam claramente comunicadas aos potenciais empregadores.<br><br>
  </figcaption>
</figure>

<hr>

<figure style="display: flex; align-items: flex-start;">
  <img src="./img/joao.jpg" alt="Image description" width="180" height="200" style="margin-right: 20px;">
  <figcaption> <b>João Flores</b>:<br><br>
João Flores tem 19 anos e está concluindo o curso técnico em Informática no Instituto Tecnológico. Ele está interessado em estágios que lhe proporcionem experiência prática em desenvolvimento de software e suporte técnico. João é apaixonado por tecnologia e está buscando uma plataforma que o ajude a encontrar estágios que complementem sua formação técnica. Ele valoriza oportunidades que ofereçam aprendizado contínuo e a chance de trabalhar em projetos desafiadores. João enfrenta desafios ao encontrar empresas que ofereçam estágios alinhados com suas habilidades específicas e em demonstrar suas capacidades técnicas de forma eficaz durante o processo de seleção.<br><br>
  </figcaption>
</figure>

<br>

<figure style="display: flex; align-items: flex-start;">
  <img src="./img/maria.jpg" alt="Image description" width="180" height="200" style="margin-right: 20px;">
  <figcaption> <b>Maria Milito</b>:<br><br>
Maria Milito tem 35 anos e é gerente de RH em uma empresa de médio porte no setor de tecnologia. Ela é responsável por recrutar novos talentos para diversos projetos da empresa. Maria busca uma plataforma que simplifique o processo de publicação de vagas de estágio e atraia candidatos qualificados. Ela valoriza ferramentas que permitam avaliar candidatos com base em competências técnicas e comportamentais específicas. Além disso, Maria deseja gerenciar o processo seletivo de maneira organizada, proporcionando uma experiência positiva tanto para os candidatos quanto para a empresa. Seus desafios incluem atrair estudantes com o perfil adequado para as vagas de estágio e selecionar candidatos que se alinhem à cultura organizacional da empresa.<br><br>
  </figcaption>
</figure>

<br>

<figure style="display: flex; align-items: flex-start;">
  <img src="./img/carlos.jpg" alt="Image description" width="180" height="200" style="margin-right: 20px;">
  <figcaption> <b>Carlos Gilberto</b>:<br><br>
Carlos tem 30 anos e é fundador de uma startup de tecnologia em fase inicial. Ele está procurando estagiários para ajudar no desenvolvimento de novos produtos e no crescimento da empresa. Carlos valoriza estagiários que tragam novas ideias e energia para a startup, contribuindo com inovação e trabalho em equipe. Ele busca uma plataforma que o ajude a atrair talentos promissores e oferecer uma experiência de estágio enriquecedora, que inclua aprendizado prático e oportunidades de crescimento profissional. Os desafios de Carlos incluem competir com empresas maiores na atração de talentos e garantir que a experiência de estágio na startup seja atrativa o suficiente para reter talentos valiosos.<br><br>
  </figcaption>
</figure>

## Histórias de usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
| Ana | Quero poder buscar vagas de estágio por área de interesse, como finanças e marketing. | Para encontrar oportunidades que correspondam aos meus interesses profissionais. | 
| Ana | Quero receber notificações sobre o status das minhas candidaturas e feedbacks detalhados dos processos seletivos. | Para melhorar minhas habilidades de entrevista e aumentar minhas chances de sucesso profissional. | 
| João | Quero encontrar estágios que me permitam aplicar meus conhecimentos técnicos em desenvolvimento de software e suporte técnico. | Para adquirir experiência prática relevante para minha carreira. | 
| João | Quero ter acesso a recursos educacionais e cursos complementares oferecidos pelas empresas através da plataforma. | Para continuar aprendendo e desenvolvendo minhas habilidades técnicas durante meu estágio. | 
| Maria | Quero publicar vagas de estágio de forma rápida e eficiente. | Para atrair candidatos qualificados que estejam alinhados com as necessidades da minha empresa. | 
| Maria | Quero poder avaliar candidatos com base em competências técnicas específicas, como conhecimentos em software de gestão financeira, através de ferramentas de filtragem e análise de currículos integradas à plataforma. | Para avaliar a eficácia das campanhas de recrutamento, medir o número de candidatos qualificados e otimizar o processo de seleção de estágio da minha empresa. | 
| Carlos | Quero encontrar estagiários criativos e inovadores. | Para contribuir com novas ideias e soluções para os desafios da minha startup, para impulsionar o crescimento e a inovação da empresa. | 
| Carlos | Quero oferecer aos estagiários a oportunidade de participar ativamente de projetos estratégicos da startup. | Para trabalhar ao lado da equipe fundadora para desenvolver habilidades práticas e ganhar experiência valiosa no ambiente dinâmico de uma startup em crescimento. | 

# Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

## Requisitos Funcionais


|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
| RF-001 (Cadastro de Usuários) | A aplicação deve permitir que novos usuários se cadastrem na plataforma, distinguindo entre dois tipos principais de usuários: empresas e estagiários. Durante o processo de cadastro, os usuários serão solicitados a fornecer informações básicas, como nome completo, endereço de e-mail e senha. Além disso, será necessário que escolham o tipo de perfil a ser criado, seja como empresa que oferece estágios ou como estagiário em busca de oportunidades. | ALTA | 
| RF-002 (Login e Recuperação de Senha) | A aplicação deve permitir usuários registrados na plataforma devem poder fazer login de maneira segura utilizando seu endereço de e-mail e senha cadastrados. Caso esqueçam a senha, deverá ser oferecida a opção de recuperação por e-mail. | ALTA | 
| RF-003 ( Personalização de Perfil) | A aplicação deve permitir que cada usuário, seja empresa ou estagiário, tenha a capacidade de personalizar seu perfil na plataforma. Isso inclui a possibilidade de adicionar uma foto de perfil, informações de contato atualizadas, descrição da empresa (para empresas) ou histórico educacional e experiências relevantes (para estagiários). | ALTA | 
| RF-004 (Preenchimento de Currículo Online) | A aplicação deve permitir que os usuários estagiários(a) tenham a facilidade de preencher seus currículos diretamente na plataforma. O formulário de currículo incluirá campos estruturados para inserção de informações como formação acadêmica, experiências profissionais anteriores (se houver), habilidades técnicas e idiomas dominados. | ALTA | 
| RF-005 ( Gerenciamento de Vagas por Empresas:) | A aplicação deve permitir que os usuários empresas cadastradas poderão criar, editar e excluir vagas de estágio na plataforma. Durante a criação de uma vaga, as empresas poderão inserir detalhes como título da vaga, descrição detalhada das responsabilidades, requisitos específicos (como habilidades técnicas desejadas e qualificações necessárias), benefícios oferecidos, salário (se aplicável) e localização da vaga. | ALTA | 
| RF-006 (Candidatura a Vagas de Estágio) | A aplicação deve permitir que os usuários estagiários poderão se candidatar a vagas de estágio diretamente pela plataforma. Cada vaga de estágio listada incluirá um botão de candidatura visível, permitindo aos estagiários enviar seu currículo. | ALTA | 
| RF-007 (Acompanhamento de Candidaturas) | A aplicação deve permitir que os usuários Empresas tenham a capacidade de acompanhar o status das candidaturas recebidas para suas vagas de estágio. Um painel administrativo fornecerá um resumo das candidaturas recebidas para cada vaga, incluindo informações detalhadas sobre cada candidato, status da candidatura (pendente, em análise, selecionado, etc.) e ações a serem tomadas (como agendar entrevistas ou fornecer feedback). | ALTA | 
| RF-008 (Notificações de Status:) | A aplicação deve permitir que sejam enviadas notificações automáticas para estagiários e empresas sobre o status das candidaturas. Isso inclui confirmações de recebimento de candidatura, atualizações sobre o progresso da seleção (como convites para entrevistas) e feedbacks finais sobre a candidatura. As notificações serão enviadas via e-mail e/ou dentro da própria plataforma, garantindo que os usuários estejam sempre informados e atualizados sobre suas atividades na plataforma. | ALTA | 

## Requisitos não Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RNF-001| O sistema deve ser responsivo, de modo a ser adequadamente exibido em dispositivos móveis | MÉDIA |
|RNF-002| O sistema deve ser implementado na linguagem de programação JavaScript. | ALTA |
|RNF-003| O sistema deve manter o tempo máximo de resposta para qualquer interação do usuário na aplicação abaixo de 15 segundos | MÉDIA |
|RNF-004| O sistema deve ser capaz de suportar até 250 usuários navegando simultaneamente, mantendo um tempo de resposta satisfatório e sem degradação significativa de desempenho | MÉDIA |
|RNF-005| O sistema deve garantir a segurança dos dados dos usuários, protegendo as informações pessoais e confidenciais armazenadas na aplicação | ALTA |

# Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.


# Diagrama de Casos de Uso

