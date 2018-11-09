# Projeto FHM - Centro Nacional de Desporto e Segurança - Natureza Aventura & Turismo

# Avaliador

Quando um **avaliador** já se encontra registado na plataforma, é necessário iniciar sessão na plataforma para aceder aos conteúdos e ações disponíveis.

![](Login-83c2f668-4502-4ea8-9411-21bc0b4af47b.png)

Após a sessão ter sido iniciada com sucesso, o **avaliador** terá acesso aos seguintes pontos:

- navegação dentro da plataforma de acordo com as permissões atribuídas;
- *dashboard* com estatísticas relacionadas com as provas de **avaliação**/**aplicando**;
- ação de registo de novo **aplicado** sempre disponível no cabeçalho da plataforma;
- menu relativo ao utilizador;

![](AvaliadorDashboard-06c8e24a-b181-4ef9-9c0d-c4bbef149e8e.png)

No menu "Provas de avaliação" o **avaliador** tem disponível as provas de avaliação:

- O click na prova irá listar os **aplicandos** para avaliação;
- O botão "novo" serve para uma nova avaliação rápida, onde será escolhida a avaliação de acordo com as provas disponíveis:
    - Competência aquática percepcionada;
    - Avaliação de risco;
    - Competência aquática real;

![](AvaliadorProvasdeavaliacao-5145a964-04d2-46e8-b503-d59a4d7da82a.png)

Após seleção de uma prova de avaliação, são listados os vários **aplicandos** inseridos pelo **avaliador** disponíveis para avaliação. 

Para avaliar um aplicando, caso este ainda não o tenha sido na prova referida, basta carregar no botão "Começar avaliação".

![](AvaliadorProvasdeavaliacaoProva-37861fe4-3761-44ba-a6e1-4e1b646653db.png)

Quando uma avaliação é concluída, esta fica fica inserida no estado de **pendente**, que está inserido nos seguintes estados da avaliação:

- `Incompleto` (a prova foi iniciada, mas por algum motivo não chegou ao fim);
- `Pendente` (a prova foi concluída, mas não submetida / apta para revisão);
- `Submetida` (a prova foi submetida para avaliação automática do *score* do avaliando);

A partir do menu de navegação é possível consultar a área de relatórios gerados aos **aplicandos** após as avaliações terem sido concluídas com sucesso:

![](AvaliadorAplicandoInfo-ef5bf677-dec3-42e3-b9b7-981c296d5ba1.png)

Na parte superior do cabeçalho, o botão "Registar aplicado" permite adicionar o registo de um novo **aplicando** na plataforma, onde é necessário o preenchimento obrigatório dos seguintes campos:

- `Nome` | `Data de nascimento` | `Número de contribuinte` (não identificado no protótipo);

![](AvaliadorRegistoAplicando-f6e81a63-a1a3-4dd9-aad5-0c6be549f95d.png)

# Aplicando

Após a conclusão do registo de um aplicado por parte do **avaliador**, este recebe um email de apresentação, com um link para a plataforma, onde são representados os seguintes cenários:

**O aplicando forneceu um email:**

- o acesso é feito a partir do email do **aplicando**;
- é gerada uma *password* automaticamente para acesso temporário descrita no email (esta pode e deve ser alterada posteriormente pelo aplicando):

![](Email-2af8e20c-1047-421d-9365-df6933e16f03.png)

![](Login-1c079725-4bfd-4938-a44c-a4501903903b.png)

**O aplicando apenas forneceu os dados obrigatórios:**

- é possível o aplicando aceder à área privada da plataforma através do **nif;**
- os dados requeridos são inseridos posteriormente ao inicio de sessão na plataforma;
- após a inserção de um **email**, é enviado um email de apresentação/confirmação para validação da conta;

![](AplicandoInserirdados-0ba1d515-f701-402f-a10a-c91a81fecffb.png)

Após a inserção e/ou atualização dos dados por parte do **aplicado**, são disponibilizadas as seguintes operações:

- Atalho para preenchimento de um questionário*;
- Consulta de relatórios adjacentes às avaliações feitas;
- Obter/consultar um certificado da avaliação;

*está descrito "formulário" no protótipo ao invés de questionário

![](AplicandoDashboard-3a4acb53-aac2-4d94-b20a-862aaccdb1b6.png)

- Caso o **aplicando** não tenha concluído o preenchimento de um questionário, será apresentada respectiva informação na *menu* de questionários;

    ![](AplicandoDashboardQuestionarios-f64b78b9-23c3-4deb-b8d2-5d253733590f.png)

O **aplicando** pode responder a um questionário, onde este é dividido por vários temas/áreas:

Dados sócio-geo-demográficos (caso ainda não preenchidos)

- competência aquática percecionada;
- avaliação de risco;
- competência aquática real;

![](AplicandoQuestionario_1-d0d5f523-b474-4b76-8fd0-c04f4896037d.png)

![](AplicandoQuestionario_2-acd0e58d-6656-499b-ab00-e8d3a4678fba.png)

![](AplicandoQuestionario_3-09d6e1a3-a9fd-401c-a762-b9328ce95c60.png)

![](AplicandoQuestionario_4-9288bdfe-fdb9-4f55-8701-de8ae4900f15.png)

![](AplicandoQuestionario_5-11012253-2bf0-4392-8068-541842f490f0.png)

Após conclusão dos questionários requeridos, e submetida a avaliação do **aplicado** por parte de um **avaliador**, estará disponível um relatório com os resultados referentes à avaliação:

![](AvaliadorAplicandoInfo-57828adb-5e3a-4848-b1dc-e135ee58e618.png)

Alguma informações poderão estar induzidas em erro.

Todos os ecrâs do protótipo são *drafts* conceptuais, pelo que estão sujeitos a futuras alterações.

## Os layouts poderão ser consultados com mais detalhe descompactando o arquivo "**FHM_MS_31112018.zip"** ou o respectivo ficheiro em formato .pdf.