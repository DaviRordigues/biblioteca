# programa
{

inteiro opcao, voltamenu1, opcao2, lugar,
cadeia senha
cadeia nome
inteiro MAX_LIVROS = 50
cadeia titulos[MAX_LIVROS]
cadeia autores[MAX_LIVROS]
cadeia editoras[MAX_LIVROS]
inteiro anos[MAX_LIVROS]


funcao relatorio_livros()
{
    escreva("Relatório de Livros Cadastrados")
    escreva("--------------------------------")
    
    para inteiro i de 0 ate MAX_LIVROS-1 faca
    {
        se titulos[i] != vazio entao
        {
            escreva("Título: " + titulos[i])
            escreva("Autor: " + autores[i])
            escreva("Editora: " + editoras[i])
            escreva("Ano de publicação: " + anos[i])
            escreva("-----------------------------")
        }
    }
}

funcao relatorio_livros()
{
    escreva("Relatório de Livros Cadastrados")
    escreva("--------------------------------")
    
    para inteiro i de 0 ate MAX_LIVROS-1 faca
    {
        se titulos[i] != vazio entao
        {
            escreva("Título: " + titulos[i])
            escreva("Autor: " + autores[i])
            escreva("Editora: " + editoras[i])
            escreva("Ano de publicação: " + anos[i])
            escreva("-----------------------------")
        }
    }
}

	funcao Meio_ambiente()
	{
		escreva("Escolha uma classificação abaixo.\n")
		escreva("1) Ciência.\n")
		escreva("2) Ecossistemas.\n")
		escreva("3) Gestão de Riscos.\n")
		leia(opcao)
		limpa()

		escolha(opcao)
	{
		caso 1:
	  escreva("Escolha um dos livros abaixo:\n")
	  escreva("\n")
	  escreva("1) Silent Spring.\n")
	  escreva("2) Ideia Para Adiar o fim do mundo.\n")
       escreva("3) Meio Ambiente: patrimonio Cultural .\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-E na estante A.\n ")
	  pare

	  caso 2:
	  escreva("Escolha um dos livros abaixo:\n")
	  escreva("\n")
	  escreva("1) Ecossistemas do Brasil.\n")
	  escreva("2) Os ecossistemas.\n")
       escreva("3) Modelagem Ecológica .\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-E na estante B.\n ")
	  pare

	  caso 3:
	  escreva("Escolha um dos livros abaixo:\n")
	  escreva("\n")
	  escreva("1) Principios de Gestão de Riscos.\n")
	  escreva("2) Gestão de Riscos com Cntroles Internos.\n")
       escreva("3) Gestão de Riscos nos Modelos de Negocios.\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-E na estante A.\n ")
	  pare
	}
	}





	funcao Automacao_industrial()
	{
		escreva("Escolha uma classificação abaixo.\n")
		escreva("1) Instrumentação.\n")
		escreva("2) Construção de Circuitos.\n")
		escreva("3) Desenho Termico.\n")
		leia(opcao)
		limpa()

		escolha(opcao)
		{
		caso 1:
	  escreva("Escolha um dos livros abaixo:\n")
	  escreva("\n")
	  escreva("1) Instrumentação de Processos Industriais.\n")
	  escreva("2) Instrumentação Industrial.\n")
       escreva("3) Instrumentação Industrial essencial.\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-D na estante J.\n ")
	  pare

	  	caso 2:
	  escreva("Escolha um dos livros abaixo:\n")
	  escreva("\n")
	  escreva("1) Funcamentos de Eletronica.\n")
	  escreva("2) Eletronica para Makers.\n")
       escreva("3) Instalações Eletricas.\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-D na estante K.\n ")
	  pare

	  	caso 3:
	  	 escreva("Escolha um dos livros abaixo:\n")
	  escreva("\n")
	  escreva("1) Desenho Geometricos.\n")
	  escreva("2) Leitura e Interpretação de Desenhos Termicos.\n")
       escreva("3) Desenho Tecnico Moderno.\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-D na estante L.\n ")
	  pare
	  	
	  	
		}
		
	}



	funcao Matematica()
	{
		escreva("Escolha uma classificação abaixo.\n")
		escreva("1) Física.\n")
		escreva("2) Matemática Aplicada.\n")
		escreva("3) Cálculo.\n")
		leia(opcao)
		limpa()

		escolha(opcao)
		{
	caso 1:
	  escreva("Escolha um dos livros abaixo:\n")
	  escreva("\n")
	  escreva("1) Matemática e Física.\n")
	  escreva("2) Teoria da Relatividade.\n")
       escreva("3) Matemática Para Físicos.\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-C na estante G.\n ")
   		pare

   	caso 2:
   	  escreva("Escolha um dos livros abaixo:\n")
	  escreva("\n")
	  escreva("1) Matemática Aplicada a Informatica.\n")
	  escreva("2) Metodo de Matemática Aplicada.\n")
       escreva("3) Matemática Financeira.\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-C na estante H.\n ")
   		pare

   		
   	caso 3:
   	  escreva("Escolha um dos livros abaixo:\n")
	  escreva("\n")
	  escreva("1) Calculo A.\n")
	  escreva("2) Calculo em Quadrinhos.\n")
       escreva("3) Pre-Calculo.\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-C na estante I.\n ")
   		pare
   		
		}
		
	}




	funcao Gestao()
	{
		
		escreva("Escolha uma classificação abaixo.\n")
		escreva("1) Empreendedorismo.\n")
		escreva("2) Gerencia de projetos.\n")
		escreva("3) Rotinas adiministrativas.\n")
		leia(opcao)
		limpa()

		escolha(opcao)
{
	caso 1:
	  escreva("Escolha um dos livros abaixo:\n")
	  escreva("\n")
	  escreva("1) A Startup Enxuta.\n")
	  escreva("2) O Mito Empreendorismo.\n")
       escreva("3) O Ponto da Virada.\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-B na estante D.\n ")
   		pare
   		

   	caso 2:
   	  escreva("Escolha um dos livros abaixo:\n")
   	  escreva("\n")
	  escreva("1) Gestor Pela Primeira Vez.\n")
	  escreva("2) Gerenciamento de Projetos.\n")
       escreva("3) O Monge e o Executivo.\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-B na estante E.\n ")
	  pare
	  
	  
	caso 3:
	  escreva("Escolha um dos livros abaixo:\n")
	  escreva("\n")
	  escreva("1) Adiministração Estrategia.\n")
	  escreva("2) 25 Ferramentas de Gestão.\n")
       escreva("3) Gestão de Progetos Pela Primeira Vez.\n")
       escreva("\n")
	  escreva("Livros estão localizados no SETOR-B na estante F.\n ")
}
	}


	funcao Tecnologia_da_informacao()
{
	
 
   escreva("Escolha uma classificação abaixo.\n")
   escreva("1) Metodologia.\n")
   escreva("2) Linguagem de progeto.\n")
   escreva("3) Rede de computadores.\n")
   leia(opcao)
   limpa()

   escolha(opcao)
   {

   caso 1:
	escreva("Escolha um dos livros abaixo:\n")
	escreva("\n")
	escreva("1) Introdução à teoria da computação.\n")
	escreva("2) Criptografia e segurança de redes.\n")
	escreva("3) SISTEMAS EMBARCADOS Hardware e Firmware na Prática.\n")
	escreva("\n")
	escreva("Livros estão localizados no SETOR-A na estante B.\n ")
   pare

   caso 2:
   escreva("Escolha um dos livros abaixo:\n")
   escreva("\n")
   escreva("1) Compiladores principios, técnicas e ferramentas.\n")
   escreva("2) PowerPoint 20 (Liberdade à criação).\n")
   escreva("3) Análise e Simulação de circuitos no Computador.\n")
   escreva("\n")
   escreva("Livros estão localizados no SETOR-A na estante C.\n ")
   pare


   caso 3:
   escreva("Escolha um dos livros abaixo:\n")
   escreva("\n")
   escreva("1) Redes de Computadores e a Internet.\n")
   escreva("2) Sistemas Modernos de Comunicações Wireless.\n")
   escreva("3) Telecomunicações Modernas.\n")
   escreva("\n")
   escreva("Livros estão localizados no SETOR-A na estante A.\n ")
   
   }
	
}



funcao menulivro()
{

	escreva("   Escolha um tipo de livro:\n")
	escreva("\n")
     escreva("1- Tecnologia da informação.\n")
     escreva("2- Gestão\n")
     escreva("3- Matemática.\n")
     escreva("4- Automação industrial.\n")
     escreva("5- Meio ambiente\n")
     leia(lugar)
     limpa()
     se(lugar==1){
     	Tecnologia_da_informacao()
     }

     se(lugar==2){
     	Gestao()
     }

     se(lugar==3){
     	Matematica()
     }

     se(lugar==4){
     	Automacao_industrial()
     }

     se(lugar==5){
     	Meio_ambiente()
     }

     se(lugar==6){
     	menulivro()
     }
     

}
	
	funcao inicio()
	{
	
		escreva("Olá, seja bem-vindo ao sistema de login da biblioteca!!\n")
		escreva("Faça login para continuar!\n")
		escreva("\n")
		escreva("Qual o seu nome?\n")
		leia(nome)
		limpa()
	     escreva("Aluno ", nome, " insire a sua senha para prosseguir. \n")
		escreva("Digite a sua senha:\n")
		leia(senha)
		limpa()
		
		se (senha == "123"){
			escreva("Logado no sistema.\n")
			escreva("\n")
			}
		
		senao{
		escreva("Acesso negado!\n")
		escreva("1) Voltar ao menu.\n")
		leia(voltamenu1)
		limpa()
		se(voltamenu1==1){
		inicio()		
}
		senao{
		escreva("Opção invalida.\n")
    escreva("1) Retornar ao menu.\n")
    leia(voltamenu1)
    limpa()
    se(voltamenu1==1){
		inicio()	
		retorne
    }
		}
	}
	escreva("   Escolha uma das opcaos:\n")
	escreva("\n")
     escreva("1- Tecnologia da informação.\n")
     escreva("2- Gestão\n")
     escreva("3- Matemática.\n")
     escreva("4- Automação industrial.\n")
     escreva("5- Meio_ambiente\n")
     escreva("6- cadastrar_livro")
    escreva("7- relatorio_livros")

     leia(lugar)
     limpa()
     se(lugar==1){
     	Tecnologia_da_informacao()
     }

     se(lugar==2){
     	Gestao()
     }

     se(lugar==3){
     	Matematica()
     }

     se(lugar==4){
     	Automacao_industrial()
     }

     se(lugar==5){
     	Meio_ambiente()
     }

     se(lugar==6){
     	menulivro()
     }


	}
}
