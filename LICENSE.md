<%@ page language="java" contentType="text/html; charset=UTF-8"
    pageEncoding="UTF-8"%>
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<link rel="icon" href="img/favicon.ico">
<meta charset="utf-8">
<title>Nodeprop - Varejo</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<script type="text/javascript"
	src="http://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>
<script type="text/javascript"
	src="http://netdna.bootstrapcdn.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>
<link
	href="http://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.3.0/css/font-awesome.min.css"
	rel="stylesheet" type="text/css">
<link rel="stylesheet" type="text/css" href="css/cod.css">
<link
	href="http://pingendo.github.io/pingendo-bootstrap/themes/default/bootstrap.css"
	rel="stylesheet" type="text/css">
<link rel="stylesheet" type="text/css" href="css/estilo.css">
<link href="https://fonts.googleapis.com/css?family=Raleway:300"
	rel="stylesheet" type="text/css">

</head>
<body data-spy="scroll">
	<div class="navbar navbar-default navbar-static-top">
		<div class="container">
			<div class="navbar-header">
				<button type="button" class="navbar-toggle" data-toggle="collapse"
					data-target="#navbar-ex-collapse">
					<span class="sr-only">Toggle navigation</span> <span
						class="icon-bar"></span> <span class="icon-bar"></span> <span
						class="icon-bar"></span>
				</button>
				<a class="navbar-brand"><img class="img-logo" height="30"
					alt="Brand" src="img/logo.png"></a>
			</div>
			<div class="collapse navbar-collapse" id="navbar-ex-collapse">
				<ul class="nav navbar-nav navbar-right">
					<li class="active"><a href="index.jsp">Home</a></li>
					<li><a href="cadastro.jsp">Cadastrar-se</a></li>
				</ul>
			</div>
		</div>
	</div>
	<div class="section">
		<div class="background-image background-image-fixed container-tam"
			style="background-image: url('img/logo2.jpg')"></div>
		<div class="container">
			<div class="row">
				<div class="col-md-6"></div>
				<div class="col-md-6 text-justify">
					<form role="form" action="efetuarlogin" method="post">
						<div class="form-group">
							<label class="control-label font-color" for="exampleInputText1">Login</label>
							<input class="form-control input-lg" id="exampleInputText1"
								placeholder="Insira seu login" type="login" name="login">
						</div>
						<div class="form-group">
							<label class="control-label font-color"
								for="exampleInputPassword1">Senha</label> <input
								class="form-control input-lg" id="exampleInputPassword1"
								placeholder="Insira sua senha" name="senha" type="password">
							<div class="col-sm-offset-2 col-sm-10">
								<div class="checkbox">
									<label class="font-color"> <input class="checkbox"
										type="checkbox">Lembrar-se de mim
									</label> <a class="request-password" href="requestpassword.jsp">Esqueci
										minha senha</a>
								</div>
							</div>
						</div>
						<button type="submit" class="btn btn-lg btn-color">
							<span class="font-color">Entrar</span>
						</button>
					</form>
				</div>
			</div>
		</div>
	</div>
	<div class="section container-color">
		<div class="container">
			<div class="row">
				<div class="col-md-3">
					<img src="img/Lucas.jpg" class="img-circle img-responsive">
					<h2 class="text-center text-primary">CEO</h2>
					<p class="text-center text-primary">
						Formação: Doutorado em Administação na instituição UFPE.<br>Diretor
						Geral Executivo.
					</p>
				</div>
				<div class="col-md-3">
					<img src="img/mika.jpg" class="img-circle img-responsive">
					<h2 class="text-center text-primary">Gerente</h2>
					<p class="text-center text-primary">
						Formação: Bacharelado em Administração na Instituição UFBA.<br>Responsável
						por administrar o negócio da empresa.
					</p>
				</div>
				<div class="col-md-3">
					<img src="img/victor.jpg" class="img-circle img-responsive">
					<h2 class="text-center text-primary">Supervisor</h2>
					<p class="text-center text-primary">
						Formação: Graduação em Logística na Instituição UPE.<br>Responsável
						por conduzir e supervisionar, por meio de orientação e
						acompanhamento do desenvolvimento dos fucionários.
					</p>
				</div>
				<div class="col-md-3">
					<img src="img/alisu.jpg" class="img-circle img-responsive">
					<h2 class="text-center text-primary">
						Analista&nbsp;<br>
					</h2>
					<p class="text-center text-primary">
						Formação: Doutorado em Análise e Desenvolvimento de Sistemas na
						Instituição ITA.<br>Responsável por desenvolver, analisar e
						projetar sistemas.
					</p>
				</div>
			</div>
		</div>
	</div>

	<footer class="container-color-03 section">
	<div class="container">
		<div class="row">
			<div class="col-sm-6">
				<span class="font-color">
					<h1>Nodeprop Varejo</h1>
					<p>
						Endereço: Rua Sem Nome 404 - B. <br>Contato: 00000-0000 /
						00000-0000. <br>E-mail: Nodeprop@empresa.com. <br>Atendimento:
						7:00 ás 12:00 / 13:00 ás 18:00.
					</p>
				</span>
			</div>
			<div class="col-sm-6">
				<p class="text-info text-right">
					<br> <br>
				</p>
				<div class="row">
					<div class="col-md-12 hidden-lg hidden-md hidden-sm text-left">
						<a href="#"><i
							class="fa fa-3x fa-fw fa-instagram text-inverse"></i></a> <a href="#"><i
							class="fa fa-3x fa-fw fa-twitter text-inverse"></i></a> <a href="#"><i
							class="fa fa-3x fa-fw fa-facebook text-inverse"></i></a> <a href="#"><i
							class="fa fa-3x fa-fw fa-github text-inverse"></i></a>
					</div>
				</div>
				<div class="row">
					<div class="col-md-12 hidden-xs text-right">
						<a href="#"><i class="fa fa-4x fa-fw fa-instagram text-danger"></i></a>
						<a href="#"><i class="fa fa-4x fa-fw fa-twitter text-info"></i></a>
						<a href="#"><i class="fa fa-4x fa-facebook fa-fw text-primary"></i></a>
						<a href="#"><i class="fa fa-4x fa-fw fa-github text-warning"></i></a>
					</div>
				</div>
			</div>
		</div>
	</div>
	</footer>


</body>
</html>
