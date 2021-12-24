<img src="https://img.shields.io/badge/current version-1.0.0-blue" />

## 🖥 Painel Administrativo Vistei

Bem-vindo(a) ao painel administrativo da Vistei. O nosso portal administrativo é a plataforma onde você pode visualizar, gerenciar e parametrizar a sua empresa na Vistei. Nessa documentação você encontrará as instruções para uso da plataforma web, para acessar a documentação da API, <a href="">clique aqui</a>.

## Índice

<ul>
  <li><a href="#user-access">Usuários e acessos</a></li>
  <ul>
    <li><a href="#first-access">Primeiro acesso</a></li>
    <li><a href="#access-profiles">Perfis de acesso</a></li>
    <li><a href="#users-invite">Convidando usuários</a></li>
    <li><a href="#password-recover">Alteração e recuperação de senha</a></li>
  </ul>
  <li><a href="#constants">Gestão de constantes</a></li>
  <ul>
    <li><a href="#constant-object">Constante tipo de objetos</a></li>
    <li><a href="#constant-photo">Constante tipo de fotos</a></li>
    <li><a href=#constant-inspection>Constante tipo de Vistorias</a></li>
  </ul>
  <li><a href="#inspections">Gestão de vistorias</a></li>
  <ul>
    <li><a href="#inspection-request">Solicitando visotias</a></li>
    <!-- <li><a href="">Emitindo um laudo de vistoria</a></li> -->
  </ul>
  <li><a href="#developer">Painel do desenvolvedor</a></li>
   <ul>
    <li><a href="#access-credentials">Credenciais de acesso</a></li>
    <li><a href="#credentials-reset">Resetando credenciais de acesso</a></li>
  </ul>
</ul>

<hr/>

## <a name="user-access"></a>Usuários e acessos

###  <a name="first-access"></a>Primeiro acesso

O primeiro acesso da sua empresa na plataforma Vistei é criado pelo nosso time no momento da integração. O primeiro acesso criado é o usuário MASTER da sua empresa. Ele poderá parametrizar a ferramenta e convidar novos usuários. No momento da integração, você receberá um e-mail contendo o seu usuário e uma senha padrão que poderá ser alterada posteriormente. Com o seu usuário e senha em mãos, basta acessar o endereço <a href="https://portal.vistei.tech" target="_blank">https://portal.vistei.tech</a> e fazer o login na plataforma.

### <a name="access-profiles"></a>Perfis de acesso (beta)

O portal administrativo da Vistei tem alguns perfis de acesso pré-definidas que você pode aplicar aos seus usuários.

<table>
  <thead>
    <td>Perfil</td>
    <td>Descrição</td>
  </thead>
  <tbody>
    <tr>
      <td>MASTER</td>
      <td>O usuário MASTER possui acesso completo a todas as telas e funcionalidade do sistema.</td>
    </tr>  
    <tr>
      <td>Administrador</td>
      <td>As pessoas com o perfil de acesso administrador a possuem acesso liberado a todas as telas e funcionalidades do sistema. Porém, pessoas com este acesso não podem alterar as informações cadastrais da sua empresa na plataforma Vistei.</td>
    </tr>  
    <tr>
      <td>Backoffice</td>
      <td>As pessoas com o perfil de acesso backoffice possuem acesso aos módulos operacionais. Elas podem solicitar e acompanhar vistorias, emitir laudos, convidar e gerenciar usuários e parametrizar as constantes do sistema.</td>
    </tr>
    <tr>
      <td>Desenvolvedor</td>
      <td>As pessoas com o perfil de acesso desenvolvedor possuem acesso à àrea do desenvolvedor. Nela, é possível gerenciar as credenciais de acesso e as configurações de conexão via API.</td>
    </tr> 
    <tr>
      <td>Vistoriador</td>
      <td>As pessoas com o perfil de acesso vistoriador possuem acesso ao módulo de vistoria. Nele é possível solicitar novas vistorias, acompanhar os status das vistorias existentes e emitir laudos de vistoria.</td>
    </tr> 
  </tbody>
</table>


### <a name="users-invite"></a>Convidando usuários

Convidar um novo usuário é muito simples. Na página inicial da nossa <a href="https://portal.vistei.tech" target="_blank">plataforma</a>, clique em 'Configurar usuários' e, em seguida, clique no botão 'Convites'. Na página de convites, você consegue ver uma listagem de todos os convites que foram enviados na sua plataforma. Para convidar um novo colaborador, clique em 'Convidar usuário' e preencha as seguintes informações:
<ul>
  <li>Nome do usuário</li>
  <li>E-mail do usuário</li>
  <li>Perfil de acesso (saiba mais em <a href="">perfis de acesso</a>)</li>
</ul/>
  
### <a name="password-recover"></a>Alteração e recuperação de senha
  
Existem duas maneiras de alterar a sua senha de acesso ao sistema. Caso esteja logado no sitema e lembre a sua senha, basta acessar o menu 'Alterar senha', inserir a sua senha atual, criar uma nova senha e confirmar as alterações. Caso tenha perdido o acesso à sua conta ou esquecido a sua senha de acesso, na tela de login basta escolher a opção 'Esqueceu a senha?'. Na página de recuperação, será solicitado que você informe o seu e-mail e você receberá uma mensagem com um código de recuperação que permitirá que você altere a sua senha.

<hr/>

## <a name="constants"></a>Gestão de constantes

Constantes são configurações que você pode criar para parametrizar a plataforma de acordo com as necessidades do seu negócio. 

### <a name="constant-object"></a>Constante tipo de objetos
Nessa constante você deve parametrizar quais os tipos de objetos poderão ser vistoriados pela sua empresa na nossa plataforma. A parametrização dessa constante é essencial, pois para cadastrar tipos de fotos você precisará dessa informação. Alguns exemplos para essa constante são: automóveis, motociletas, imóveis, smartphones, etc.

### <a name="constant-photo"></a>Constante tipo de fotos
Nessa constante você deve parametrizar as fotos que deverão ser enviadas durante a vistoria. Você pode criar quantos tipos de foto desejar e associá-las posteriormente aos tipos de vistoria. Para parametrizar essa constante, você precisa das seguintes informações:

<table>
  <thead>
    <td>Campo</td>
    <td>Descrição</td>
    <td>Exemplo</td>
  </thead>
  <tbody>
    <tr>
      <td>Nome</td>
      <td>Nome da foto.</td>
      <td>Automóvel - frente</td>
    </tr>  
     <tr>
      <td>Descrição</td>
      <td>Breve texto que descreve a foto.</td>
      <td>Frente do automóvel.</td>
    </tr> 
     <tr>
      <td>Slug</td>
      <td>Composto por duas ou três palavras minúsculas, sem acentuação, sem espaço e sem caracteres especiais, o slug é um código curto que identificará as fotos enviadas durante uma vistoria.</td>
       <td>aut-frente</td>
    </tr> 
     <tr>
      <td>Texto de ajuda</td>
      <td>O texto de ajuda será exibido para o seu cliente/vistoriador no momento da captura da foto. Insira uma breve descrição de como a voto deve ser tirada.</td>
      <td>Tire uma foto da frente do seu automóvel. Certifique-se de que a placa esteja legível.</td>
    </tr> 
     <tr>
      <td>Tipo de objeto</td>
      <td>Neste campo escolha uma das opções criadas anteriormente na constante <a href="#constant-object">tipos de objetos</a>.</td>
       <td>-</td>
    </tr> 
     <tr>
      <td>Foto de exemplo</td>
      <td>A foto de exemplo será enviada para o cliente/vistoriado no momento da captura da foto. Escolha uma imagem nítida e que ilustre exatamente como você deseja que a foto seja tirada. O tamanho recomentado para essa imagem é de 100x120px.</td>
       <td>-</td>
    </tr> 
  </tbody>
</table>

### <a name="constant-inspection"></a>Constante tipo de vistoria

Nessa constante você deve parametrizar os tipos de vistorias que poderão ser solicitados pela sua empresa. Você pode criar quantos tipos de vistoria desejar. Para parametrizar essa constante, você precisa das seguintes informações:

<table>
  <thead>
    <td>Campo</td>
    <td>Descrição</td>
    <td>Exemplo</td>
  </thead>
  <tbody>
    <tr>
      <td>Nome</td>
      <td>Nome da vistoria.</td>
      <td>Vistoria veicular</td>
    </tr>
    <tr>
      <td>Tipo de objeto</td>
      <td>Neste campo escolha uma das opções criadas anteriormente na constante <a href="#constant-object">tipos de objetos</a>.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Fotos</td>
      <td>Selecione as fotos que o cliente/vistoriador deverá enviar nessa vistoria.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mensagem de boas-vindas</td>
      <td>Mensagem que será exibida para o cliente/vistoriador antes da vistoria ser iniciada. Importante: a mensagem de boas-vindas sempre será exibida após uma saudação ao cliente/vistoriador, portanto, evite incluir saudações nesse campo.</td>
      <td>Está tudo pronto para iniciarmos a sua vistoria. Assim que estiver tudo pronto, clique em 'Iniciar'.</td>
    </tr>
    <tr>
      <td>Mensagem de conclusão</td>
      <td>Mensagem que será exibida para o cliente/vistoriador ao final da vistoria.</td>
      <td>Vistoria finalizada com sucesso! Em breve entraremos em contato com você para mais informações.</td>
    </tr>
  </tbody>
</table>

## <a name="inspections"></a>Gestão de vistorias

### <a name="inspection-request"></a>Silicitando vistorias

Solicitar uma vistoria no portal administrativo da Vistei é muito simples. Na página inicial, acesse o menu 'Vistoria', clique no botão 'Solicitar vistoria'  e preencha as informações solicitadas:

<ul>
  <li>Tipo de vistoria (criado na constante tipos de vistoria)</li>
  <li>Aplicação (ferramenta que será usada para realizar a vistoria)</li>
  <li>Identificador (informação única do objeto vistoriado. Ex.: placa do veículo)</li>
  <li>Nome do cliente</li>
  <li>CPF do cliente</li>
  <li>Telefone do cliente</li>
</ul>

Após preencher todos os campos, clique em confirmar. Você será redirecionado para a página de detalhes da vistoria, onde poderá gerar um link para a vistoria e enviá-lo por WhatsApp para o cliente/vistoriador.

## <a name="developer"></a>Painel do desenvolvedor

### <a name="access-credentials"></a>Credenciais de acesso

As credenciais de acesso para desenvolvedores são a API Key e API Secret. Com elas, é possível realizar uma conexão via API entre o sistema da sua empresa e a plataforma Vistei. Para mais detalhes, consulte a <a href=""> documentação da API</a>.

### <a name="credentials-reset"></a>Resetando credenciais de acesso

A qualquer momento você pode resetar as credenciais de acesso do seu sistema. Basta acessar a área do desenvolvedor e clicar no botão 'Resetar credenciais'. <br/><br/>
⚠️ Importante: ao resetar as credenciais de acesso, as credenciais atuais perderão a validade, por isso, lembre-se de alterar essas informações na sua plataforma.
