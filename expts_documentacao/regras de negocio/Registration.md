# Cadastro de usuários

___

## Cadastro de prestadores de serviço 

- ### Pessoa física
- Para profissionais autónomos que nao possuam CNPJ , será capaz de visualizar numero de contratações e clientes interessados, conforme a posição geográfica, sera capaz de exibir projetos ja realizados e especializações em seu perfio.

1. Regras de negocio para o cadastro:
- Campos obrigatórios para o cadastro:
    - Nome;
    - Sobrenome;
    - CPF;
        > Validar se é um CPF valido.
    - RG ou cnh; 
        >Deve possuir campo para escolher qual documento colocar.
    - Data de nascimento;
        > Validar data de nascimento.
    - CEP;
        > Validar CEP, preencher, município, estado e nome da rua de forma automática.
    - Numero da rua;
    - Bairro;
    - Foto com Documento;
        > Na versão mobile, selecionar usar a camera ou carregar a foto, versão WEB apenas carregar a foto.
    - Area de atuação primaria;
    - Numero de telefone; 
    - Email;
    - Senha;
        > Validar sea senha possui mais de oito dígitos e possui letras e números.
    - Confirmação de senha;
        > Validar se a senha corresponde.
- Campos não obrigatórios:
    - Segundo telefone;
    - Area de atuação Secundaria.
    - Outros
- Confirmação de cadastro:
    > Enviar link de confirmação para E-mail
    > Se possível confirmar numero de telefone
2. regras de negocio para perfio:
- Campos automáticos
    - Carregar nome de usuário automaticamente no Perfio
    - Area de atuação
- Campos a serem informados - Obrigatórios
    > Nenhum 
- Campos a serem informados não obrigatórios:
    - Campos de Bio;
    - Lista de serviços 
    - Tipo de profissional;
        > analisar opções e acrescentar aqui 
    - Editar area de atuação;
        > possível mudar apenas uma vez a cada dois meses, após a primeira mudança.
    - Editar como o nome aparece
        > Nome previamente carregado.
    - Inserir Imagens do perfio; 
        > Opção apenas carregar
3. Regras de negocio para Portfolio 
    > adicionar campos do protofilo 

- ### Pessoa Jurídica
- Para profissionais que possuem CNPJ , será capaz de visualizar numero de contratações e clientes interessados, conforme a posição geográfica, sera capaz de exibir projetos ja realizados e especializações em seu perfio.

1. Regras de negocio para o cadastro:
- Campos obrigatórios para o cadastro:
    - Nome do responsável;
    - Nome da empresa;
    - CNPJ;
        > Validar se é um CNPJ valido.
    - Tipo de empresa;
        > Mei, MEPP, ME, OUTROS.
    - Numero de funcionários:
        > Ate 2, até 5, até 15, ate 50, mais que 50.
    - CEP;
        > Validar CEP, preencher, município, estado e nome da rua de forma automática.
    - Numero da rua;
    - Bairro;
    - Foto com Documento caso a opção seja MEI;
        > Na versão mobile, selecionar usar a camera ou carregar a foto, versão WEB apenas carregar a foto.
    - Area de atuação primaria;
    - Numero de telefone; 
    - Email;
    - Senha;
        > Validar sea senha possui mais de oito dígitos e possui letras e números.
    - Confirmação de senha;
        > Validar se a senha corresponde.
- Campos não obrigatórios:
    - inscrição estadual;
    - Segundo telefone;
    - Area de atuação Secundaria.
    - Outros
- Confirmação de cadastro:
    > Enviar link de confirmação para E-mail
    > Se possível confirmar numero de telefone
2. regras de negocio para perfio:
- Campos automáticos
    - Carregar nome de usuário automaticamente no Perfio;
    - Area de atuação;
    - Avaliação.
- Campos a serem informados - Obrigatórios
    > Nenhum.
- Campos a serem informados não obrigatórios:
    - Campos de Bio;
    - Lista de serviços 
    - Tipo de profissional;
        > analisar opções e acrescentar aqui .
    - Editar area de atuação;
        > possível mudar apenas uma vez a cada dois meses, após a primeira mudança.
    - Editar como o nome aparece
        > Nome previamente carregado.
    - Inserir Imagens do perfio; 
        > Opção apenas carregar
3. Regras de negocio para Portfolio 
    > adicionar campos do protofilo 

---

## Cadastro de contratantes 

- ### Cadastro de Cliente, pessoa física;

- Para clientes que sejam pessoa física, será capaz de visualizar os prestadores de serviço, apartar da região geográfica registrada no perfio, ou através do do GPS do smartphone, para encontrar profissionais na região, definir em um raio de 10 Km, ou mais aplicando filtro.

1. Regras de negocio para o cadastro:
- Campos obrigatórios para o cadastro:
    - Nome;
    - Sobrenome;
    - CPF;
        > Validar se é um CPF valido.
    - Data de nascimento;
        > Validar data de nascimento.
    - CEP;
        > Validar CEP, preencher, município, estado e nome da rua de forma automática.
    - Numero da rua;
    - Bairro;
    - Numero de telefone; 
    - Email;
    - Senha;
        > Validar sea senha possui mais de oito dígitos e possui letras e números.
    - Confirmação de senha;
        > Validar se a senha corresponde.
- Campos não obrigatórios:
    - Segundo telefone;
    - Profissão;
        > Dar opções de profissão.
- Confirmação de cadastro:
    > Enviar link de confirmação para E-mail
    > Se possível confirmar numero de telefone
2. regras de negocio para perfio:
- Campos automáticos
    - Carregar nome de usuário automaticamente no Perfio;
    - Carregar classificação;
- Campos a serem informados - Obrigatórios
    > Nenhum 
- Campos a serem informados não obrigatórios:
    - Campos de Bio;
    - Editar como o nome aparece;
        > Nome previamente carregado.
    - Inserir Imagens do perfio; 
        > Opção apenas carregar

- ### Cadastro de Cliente, pessoa jurídica;
- Para clientes que sejam pessoa jurídica, será capaz de visualizar os prestadores de serviço, apartar da região geográfica registrada no perfio, ou através do do GPS do smartphone, para encontrar profissionais na região, definir em em um raio de 10 Km ou mais aplicando filtro

1. Regras de negocio para o cadastro:
- Campos obrigatórios para o cadastro:
    - Nome do repensável;
    - Cargo;
    - Nome da empresa;
    - CNPJ;
        > Validar se é um CNPJ valido.
    - Tipo de empresa;
        > dar opções de ramo de atuação como: Condomínio, Comercio varejista, prestador de serviço e etc. 
    - CEP;
        > Validar CEP, preencher, município, estado e nome da rua de forma automática.
    - Numero da rua;
    - Bairro;
    - Numero de telefone; 
    - Email;
    - Senha;
        > Validar se a senha possui mais de oito dígitos e possui letras e números.
    - Confirmação de senha;
        > Validar se a senha corresponde.
- Campos não obrigatórios:
    - Segundo telefone;
- Confirmação de cadastro:
    > Enviar link de confirmação para E-mail
    > Se possível confirmar numero de telefone
2. regras de negocio para perfio:
- Campos automáticos
    - Carregar nome de usuário automaticamente no Perfio;
    - Carregar classificação;
- Campos a serem informados - Obrigatórios
    > Nenhum 
- Campos a serem informados não obrigatórios:
    - Campos de Bio;
    - Editar como o nome aparece;
        > Nome previamente carregado.
    - Inserir Imagens do perfio; 
        > Opção apenas carregar.
----
