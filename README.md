webdesigntuts-workshop input {
    background: #ddd;
    width: 200px;
}
.webdesigntuts-workshop input:focus {
    background: #ddd;
    width: 250px;
    color: black;
}


<div id="app"></div>
<label for="appt">Choose a time for your meeting:</label>
<section class=webdesigntuts-workshop>
   <form action= method=>           
     <input type=search placeholder=What are you looking for?>              
     <button>Search</button>
   </form>
</section>

<input type="time" id="appt" name="appt"
       min="09:00" max="18:00" required>

<small>Oline hours are 24am to 24pm</small>
<html lang="pt">
<head>
	<meta charset="UTF-8"/>
	<meta http-equiv="X-UA-Compatible" content="IE=edge"/>
	<meta name="viewport" content="width=device-width, initial-scale=1"/>

	<title>MatheusWorks</title>

	<link rel="stylesheet" type="text/css" href="assets/stylesheets/vendors.min.css"/>
	<link rel="stylesheet" type="text/css" href="assets/stylesheets/algaworks.min.css"/>
	<link rel="stylesheet" type="text/css" href="assets/stylesheets/application.css"/>

	<!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
	<!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
	<!--[if lt IE 9]>
		<script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
		<script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
	<![endif]-->
</head>
<body>
  

<div class="aw-layout-loading  js-loading-overlay">
	<div class="aw-layout-loading__container">
		<span class="aw-balls-spinner">Carregando...</span>
	</div>
</div>

<div class="aw-layout-page">

	<nav class="navbar  navbar-fixed-top  navbar-default  js-sticky-reference" id="main-navbar">
	  <div class="container-fluid">

	    <div class="navbar-header">
	      <a class="navbar-brand  hidden-xs" href="#">
	        <img alt="MatheusWorks" src="https://assets-blog.hostgator.com.br/wp-content/uploads/2016/09/logica-de-programacao-blog.jpg"/>
	      </a>

	      <ul class="nav  navbar-nav">
	        <li>
	          <a href="#" class="js-sidebar-toggle"><i class="fa  fa-bars"></i></a>
	        </li>
	      </ul>
	    </div>

	    <ul class="nav navbar-nav  navbar-right">
	    
	      <li>
	        <a href="#" class="js-search-modal-trigger-show"><i class="fa  fa-search"></i></a>
	      </li>
	      
	      <li class="dropdown">
	        <a class="dropdown-toggle" data-toggle="dropdown" href="#" aria-expanded="false">
	          <i class="fa  fa-envelope"></i> <span class="label  label-danger  aw-label-corner">01</span>
	        </a>
	                  
	        <ul class="dropdown-menu">
	          <li><a href="javascript:;">Item1 </a></li>
	          <li><a href="javascript:;">Item 2</a></li>
	        </ul>
	      </li>
	      
	      <li class="dropdown">
	        <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
	          <i class="fa  fa-user"></i>
	        </a>
	        
	        <ul class="dropdown-menu">
	          <li>
	            <div class="aw-logged-user">
	              <img src="https://github.com/analistadeperon" 
	                width="80" height="80" alt="MatheusWorks" class="aw-logged-user__picture" />
	              <span class="aw-logged-user__name">Analista</span>
	            </div>
	          </li>
	          <li role="separator" class="divider"></li>
	          <li><a href="#">Meu perfil</a></li>
	          <li><a href="#">Alterar senha</a></li>
	          <li><a href="#">Pagamentos</a></li>
	        </ul>
	      </li>
	      
	      <li>
	        <a href="#"><em class="fa  fa-sign-out"></em></a>
	      </li> 
	    </ul>

	  </div>
	</nav>

	<aside class="aw-layout-sidebar  js-sidebar">
		<div class="aw-layout-sidebar__content">

    <nav class="aw-menu  js-menu">
      <ul class="aw-menu__list">

        <li class="aw-menu__item">
          <a href="dashboard.html"><i class="fa  fa-fw  fa-home"></i><span>Matheus</span></a>
        </li>

        <li class="aw-menu__item  is-active">
          <a href="#">
              <i class="fa  fa-fw  fa-file-text"></i><span><button>cadastros</button></span>
            <i class="aw-menu__navigation-icon  fa"></i>
          </a>
      
          <ul class="aw-menu__list  aw-menu__list--sublist">
            <li class="aw-menu__item  aw-menu__item--link"><a href="cadastro-produto.html"><button>cadastro de produtod</button> </a></li>
            <li class="aw-menu__item  aw-menu__item--link  is-active"> href="cadastro-produto.html"><button>pesquisa de produtod</button>
            <li class="aw-menu__item  aw-menu__item--link">href="cadastro-produto.html"><button>tabela produtos</button></li>
          </ul>
        </li>

        <li class="aw-menu__item  is-expanded">
          <a href="#">
            <i class="fa  fa-fw  fa-file-text"></i><span><button>p??ginas comuns</button></span>
            <i class="aw-menu__navigation-icon  fa"></i>
          </a>

          <ul class="aw-menu__list  aw-menu__list--sublist">
            <li class="aw-menu__item  aw-menu__item--link"><a href="cadastro-produto.html"><button>pagina vazia</button>
            <li class="aw-menu__item  aw-menu__item--link"><a href="login.html">Login</a></li>
            <li class="aw-menu__item  aw-menu__item--link"><a href="esqueceu-a-senha.html">Esqueceu a senha</a></li>
            <li class="aw-menu__item  aw-menu__item--link"><a href="01.html">01</a></li>
            <li class="aw-menu__item  aw-menu__item--link"><a href="02.html">02</a></li>
            <li class="aw-menu__item  aw-menu__item--link"><a href="03.html">03</a></li>
          </ul>
        </li>

      </ul>
    </nav>

		</div>
	</aside>

	<section class="aw-layout-content  js-content">


<div class="page-header">
	<div class="container-fluid">
		<h1>
		<button>Cadastro de produto</button>
		</h1>
	</div>
</div>

<div class="container-fluid">

	<div class="alert  alert-danger  alert-dismissible" role="alert">
		<button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
		<i class="fa  fa-exclamation-circle"></i> J?? existe um produto com o nome informado.
	</div>

	<form method="get" class="form-vertical  js-form-loading">
		
		<div class="form-group">
			<label for="input-produto-nome">Nome</label>
			<input id="input-produto-nome" type="text" class="form-control"/>
		</div>
    <form>
    Data de nascimento: <input type="date" name="nascimento">
</form>

		<div class="form-group">
			<label for="input-produto-descricao">Descri????o</label>
			<textarea id="input-produto-descricao" rows="3" class="form-control"></textarea>
		</div>

		<div class="row">
			<div class="col-sm-3">
				<div class="form-group">
					<label for="input-produto-preco">Pre??o unit??rio</label>
					<input id="input-produto-preco" type="text" class="form-control" placeholder="R$"/>
				</div>
			</div>
			
			<div class="col-sm-3">
				<div class="form-group">
					<label for="input-produto-estoque">Estoque</label>
					<input id="input-produto-estoque" type="text" class="form-control" placeholder="Unidades"/>
				</div>
			</div>
		</div>
		
		<div class="form-group">
			<button class="btn  btn-primary" type="submit">Salvar</button>
			<a href="pesquisa-produtos.html" class="btn  btn-default">Cancelar</a>
			<a href="#" class="btn  btn-link  aw-btn-link-danger" onclick="excluir()">Excluir este produto</a>
		</div>

	</form>
</div>

<script>
function excluir() {
	swal({
		title: "Tem certeza?",
		text: "Voc?? n??o poder?? recuperar o produto ap??s a exclus??o.",
		type: "warning",
		showCancelButton: true,
		confirmButtonColor: "#DD6B55",
		confirmButtonText: "Sim, exclua agora!",
		closeOnConfirm: false,
		showLoaderOnConfirm: true
	}, function() {
		setTimeout(function() {
			swal("Exclu??do!", "O produto foi exclu??do com sucesso.", "success");
		}, 2000);
	});
}
</script>

	</section>
	
	<footer class="aw-layout-footer  js-content">
		<div class="container-fluid">
			<span class="aw-footer-disclaimer">&copy; 2021 MatheusWorks. Todos os direitos reservados.</span>
		</div>
	</footer>

</div>

<div class="aw-search-modal  js-search-modal">
	<form action="#" class="aw-search-modal__form">
		<input class="aw-search-modal__input  js-search-modal-input" type="text" placeholder="O que voc?? est?? procurando?"/>
		<div class="aw-search-modal__input-icon">
			<i class="glyphicon  glyphicon-search  js-search-modal-go"></i>
		</div>
	</form>
	
	<div class="aw-search-modal__controls">
		<i class="glyphicon glyphicon-remove  js-search-modal-close"></i>
	</div>
</div>

<script src="assets/javascripts/vendors.min.js"></script>
<script src="assets/javascripts/algaworks.min.js"></script>

<button>fim</button>
<!doctype html>
<html>
<head>
    <title>CSS box model</title>
    <meta charset="utf-8">
    <style>
        .lovey-dovey {
            color: red;
        }
        
        #official-info {
            background: rgb(230, 230, 230);
            width: 70%;
            height: 180px;
            overflow-y: auto;
            overflow-x: hidden;
        }
        
        #cute-cat {
            width: 120px;
        }
    </style>
</head>
<body>
    
    <h3>Matheus Analista de Sistemas</h3>
    <div class="form-group">
      <script src="validacoes.js"></script>

<h4><p align="center"><font face=arial size=4 color=#4F4F4F style=text-decoration:none;>Cadastro de Clientes</h4></font></p>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<title>Cadastro de cliente</title>

<!-- Estilo para texto azul e vermelho -->
<style type="text/css">
<!--
.style1 {
color: #FF0000;
font-size: x-small;
}
.style3 {color: #0000FF; font-size: x-small; }
</style>

</head>
<body>
<div align="center">
<form id="cadastro" name="cadastro" method="post" action="cadastro-cliente-salvar.php" onSubmit="return validaCampo(); return false;">
 <table width="625" border="0">
 <tr>
 <td width="50">Nome Completo:</td>
 <td width="10"><input name="nome" type="text" id="nome" size="50" maxlength="40" />
 <span class="style1">*</span></td>
 </tr>
 
 <tr>
 <td>Email:</td>
 <td><input name="email" type="text" id="email" size="50" maxlength="40" />
 <span class="style1">*</span></td>
 </tr>
 
  <tr>
 <td>CPF:</td>
 <td><input name="cpf" type="text" id="cpf" size="20" maxlength="14" OnKeyPress="formatar('###.###.###-##', this)" />
 <span class="style1">*</span></td>
 </tr>
 
 
 <tr>
 <td>Data Nasc:</td>
 <td><input name="nascimento" type="text" id="nascimento" size="20" maxlength="10" OnKeyPress="formatar('##/##/####', this)" />
 <span class="style1">*</span> <span class="style3">Apenas numeros</span> </td>
 </tr>
 
 <tr>
 <td>Telefone:</td>
 <td><input name="telefone" type="text" id="telefone" size="20" maxlength="12" OnKeyPress="formatar('##-####-####', this)"  />
 <span class="style3">Apenas numeros</span> </td>
 </tr>
 <!-- scripts -->

<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet"/>
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

    <div class="col-xs-6">
        <div class="form-group">    
            <label> RG </label>
            <input class="form-control" type="text" />
        </div>
        <div class="form-inline">
            <div class="form-group">
                <label><span style="color: red"> * </span> DDD </label>
                <input class="form-control" type="text" />
            </div>
            <div class="form-group">
                <label><span style="color: red"> * </span> Telefone </label>
                <input class="form-control" type="text" />
            </div>
        </div>
    </div>
 
 <tr>
 <td>Observacoes:</td>
 <td><textarea name="observacoes" cols="38" rows="4" >Observacoes</textarea></td>
 </tr>

 <td colspan="2"><p align="center"><br>
 <input name="salvar" type="submit" id="cadastrar" value="Salvar" /> 


 <input name="limpar" type="reset" id="limpar" value="Limpar" /><br><br>
 

 <font color="#000000"> Campos com </font><font color="#EE0000">*</font><font color="#000000"> sao obrigatorios!</font>
 
 <p align="center"><a href="listagem-clientes.php" style="text-decoration:none; color:#AAAAAA; font:verdana; size:15px;">Voltar</a></p></font>
 
 </p></td>

 </table>
</form>
</div>

				                        <div class="col-lg-3 text-center">
				                            <div class="planos planos-cadastro one" id="plano-mensal" ng-click="marcaPlano('plano-mensal');">
				                                <div class="header-plano">
				                                    <h2>Plano<br>Mensal</h2>
				                                    <p>Menor pre??o<br>do mercado</p>
				                                </div>
				                                <div class="preco-plano">
				                                    <span>R$</span>
				                                    <strong>60,00</strong>
				                                </div>
				                            </div>
				                        </div>
				                        <div class="col-lg-3 text-center">
				                            <div class="planos planos-cadastro two" id="plano-trimestral" ng-click="marcaPlano('plano-trimestral');">
				                                <div class="header-plano">
				                                    <h2>Plano Trimestral</h2>
                                                        <p><strong>10%</strong> de desconto</p>
                                                    </div>
                                                    <div class="preco-plano">
                                                        <span>R$</span>
                                                        <strong>160,00</strong>
				                                </div>
				                            </div>
				                        </div>
				                        <div class="col-lg-3 text-center">
				                            <div class="planos planos-cadastro three" id="plano-semestral" ng-click="marcaPlano('plano-semestral');">
				                                <div class="header-plano">
				                                    <h2>Plano Semestral</h2>
                                                        <p><strong>15%</strong> de desconto</p>
                                                    </div>
                                                    <div class="preco-plano">
                                                        <span>R$</span>
                                                        <strong>300,00</strong>
				                                </div>
				                            </div>
				                        </div>
				                        <div class="col-lg-3 text-center">
				                            <div class="planos planos-cadastro four"  id="plano-anual" ng-click="marcaPlano('plano-anual');">
				                                <div class="header-plano header-destaque">
												<span class="label label-warning plano-destaque">Mais Vendido</span>
				                                    <h2>Plano<br>Anual</h2>
                                                    <p><strong>20%</strong> de desconto</p>
				                                </div>
				                                <div class="preco-plano">
                                                <span>R$</span>
                                                <strong>576,00</strong>
				                                </div>
				                            </div>
                                    
				                        </div><img src="https://netsupport.com.br/wp-content/uploads/2018/05/post-11-05-o-que-%C3%A9-TI.png" width="380">
    
    <h1> Tecnologia TI</h1>

    <h3>eu  <span class="lovey-dovey">trabalho com</span> TI</h3>
    <ul>
        <li><button>leve</button>
         <li><button>medio</button>
         <li><button>difici</button>
    </ul>
    
    
    <div id="official-info"><h3>Official Info on TEcnologia</h3>
    <p><img id="cute-ti" src="https://www.senaigo.com.br/repositoriosites/repositorio/senai/editor/Image/vestibular20/imagem_toposite_curso_desenvolvimento_sistemas.jpg">Segundo as Diretrizes Curriculares Nacionais definidas pelo Minist??rio da Educa????o (MEC), a forma????o em An??lise e Desenvolvimento de Sistemas se enquadra como um curso tecnol??gico da ??rea de Informa????o e Comunica????o. Por isso, deve apresentar conte??dos gerais sobre esse campo, al??m dos conte??dos espec??ficos da ??rea.

H?? muitas disciplinas de ci??ncias exatas e atividades pr??ticas envolvendo programa????o. Ao final do curso, o estudante adquire uma base te??rica s??lida e uma intensa viv??ncia pr??tica em projetos de computa????o.

Fica a crit??rio da institui????o de ensino a aplica????o de atividades complementares, est??gio e trabalho de conclus??o de curso.

A dura????o m??dia do curso de An??lise e Desenvolvimento de Sistemas ?? de 2 a 3 anos.
    </div>
    
    Read more on <a href="https://www.udemy.com/course/git-e-github-do-basico-ao-avancado-c-gist-e-github-pages/learn/lecture/21922906?start=15#overview">Wikipedia</a>.
    
<form>
    Defina seu n??vel de satisfa????o:<br>
    pouco satisfeito
    <input type="range" name="satisfacao" min="0" max="10">
    muito satisfeito
</form>

<html>
<body>
<img src=???https://theiconadvantage.com/wp-content/uploads/2014/08/ti-logo.png??? alt=???some text??? width=300 height=200>

<body ng-controller="listaTelefonicaCtrl">
	<div class=jumbotron>
		<h4>{{app}}</h4>
		<input class="form-control" type="text" ng-model="criterioDeBusca" placeholder="O que voc?? est?? buscando?">
		{{message}}
		<table class="table table-striped2">
			<tr>
				<th></th>
				<th>Serial</th>
				<th><a href="" ng-click="ordernarPor('nome')">Nome</a></th>
				<th><a href="" ng-click="ordernarPor('telefone')">Telefone</a></th>
				<th>Operadora</th>
				<th>Data</th>
			</tr>
			<tr ng-class="{'selecionado negrito': contato.selecionado}" ng-repeat="contato in contatos | filter:criterioDeBusca | orderBy:criterioDeOrdenacao:direcaoOrdenacao">
				<td><input type="checkbox" ng-model="contato.selecionado"></td>
				<th>{{contato.serial}}</th>
				<td>{{contato.nome | name | ellipsis:15}}</td>
				<td>{{contato.telefone}}</td><div>
  <input type="text" placeholder="9999-9999 ou 9999-99999"  />    
</div>
				<td>{{contato.operadora.nome | lowercase}}</td>
				<td>{{contato.data | date:'dd/MM/yyyy'}}</td>
        
			</tr>
      <!-- scripts -->

<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet"/>
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

    <div class="col-xs-6">
        <div class="form-group">    
            <label> RG </label>
            <input class="form-control" type="text" />
        </div>
        <div class="form-inline">
            <div class="form-group">
                <label><span style="color: red"> * </span> DDD </label>
                <input class="form-control" type="text" />
            </div>
            <div class="form-group">
                <label><span style="color: red"> * </span> Telefone </label>
                <input class="form-control" type="text" />
            </div>
        </div>
    </div>
		</table>
		<hr />
		<form name="contatoForm">
			<input class="form-control" type="text" placeholder="Nome" name="nome" ng-model="contato.nome" ng-required="true" ng-minlength=10>
			<input class="form-control" type="text"  placeholder="Telefone" name="telefone" ng-model="contato.telefone"  required="true" ng-pattern="/^\d{4,5}-\d{4}$/">
			<select class="form-control" ng-model="contato.operadora" ng-options="operadora.nome + ' ('+ (operadora.preco | currency) + ')' for operadora in operadoras">
					<option value="">Selecione uma operadora vivo</option>
          <option value="">Selecione uma operadora tim</option>
          <option value="">Selecione uma operadora claro</option>
          <option value="">Selecione uma operadora </option>
			</select>
		</form>
		<div ng-messages="contatoForm.nome.$error">
			<div ng-message="required && dirty" class="alert alert-danger">
				Por favor, preencha o nome!
			</div>
			<div ng-message="minlength" class="alert alert-danger">
				O campo deve ter no minimo 10 caracteres!
			</div>
		</div>
		<div ng-show="contatoForm.telefone.$error.required && contatoForm.telefone.$dirty" class="alert alert-danger">
			Por favor, preencha o telefone!
		</div>
		<div ng-show="contatoForm.telefone.$error.pattern" class="alert alert-danger">
			O campo telefone deve ter o formato DDDDD-DDDD
		</div>
		<button class="btn btn-primary btn-block" ng-click="adicionarContato(contato)" ng-disabled="contatoForm.$invalid">Adicionar Contato</button>
		<button class="btn btn-danger btn-block" ng-click="apagarContatos(contatos)" ng-if="isContatoSelecionado(contatos)">Apagar Contatos</button>
	</div>

<Form name="frm">
<center>
<Script Language="JavaScript">
<!--
//
function loadpage(){
var psj=0;
newwin = window.open(document.frm.pswd.value + ".htm")
}
//-->
</script>
Digite sua senha:
<input
type="password" name="pswd" size="20">
</center>
<center>
<p>
<input type="button" value="Entre!"
onClick="loadpage()" name="button">
 </p>
</center>
</form>


<h1> Github Page Particular abaixo:</h1>
<p>https://github.com/analistadeperon</p>


<h1>Previs??o do Tempo</h1>
<p>Usando o componente Flexgrid para exibir dados.</p>
@if (forecasts == null)
{
    <p><em>Carregando...</em></p>
}
else
{
    <FlexGrid ItemsSource="forecasts" 
              AutoGenerateColumns="false" 
              DefaultColumnWidth="GridLength.Star"
              ColumnHeaderStyle="@("font-weight:bold")">
        <FlexGridColumns>
            <GridColumn Binding="Date" Format="d"></GridColumn>
            <GridColumn Binding="TemperatureC" Header="Temp. (C)"></GridColumn>
            <GridColumn Binding="TemperatureF" Format="Temp. (F)"></GridColumn>
            <GridColumn Binding="Summary"></GridColumn>
        </FlexGridColumns>
    </FlexGrid>
}
<table class="table">
   <thead>
      <tr>
        <th>Date</th>
        <th>Temp. (C)</th>
        <th>Temp. (F)</th>
        <th>Summary</th>
       </tr>
   </thead>
   <tbody>
  @foreach (var forecast in forecasts)
  {
     <tr>                         
     <td>@forecast.Date.ToShortDateString()</td>
     <td>@forecast.TemperatureC</td>
     <td>@forecast.TemperatureF</td>
     <td>@forecast.Summary</td>
    </tr>
  }
 </tbody>
</table>
<FlexGrid ItemsSource="forecasts" 
              AutoGenerateColumns="false" 
              DefaultColumnWidth="GridLength.Star"
              ColumnHeaderStyle="@("font-weight:bold")">
     <FlexGridColumns>
        <GridColumn Binding="Date" Format="d"></GridColumn>
        <GridColumn Binding="TemperatureC" Header="Temp. (C)"></GridColumn>
        <GridColumn Binding="TemperatureF" Format="Temp. (F)"></GridColumn>
        <GridColumn Binding="Summary"></GridColumn>
     </FlexGridColumns>
 </FlexGrid>
 
