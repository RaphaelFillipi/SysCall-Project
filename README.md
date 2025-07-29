# SysCall

## Introdução

O seguinte repositório possui todos os microfrontends do sistema SysCall. O SysCall é um projeto de treinamento que atua como uma agenda de contatos. Desta maneira, é possível adicionar contatos, como também efetuar ligações para diferentes contatos e números de telefone do Brasil.



## Estrutura do Projeto SysCall

Este sistema foi feito utilizando o conceito de `microfrontend`, ou seja, determinadas partes do projeto estão separadas por módulos independentes.

	📁 SysCall-Project  
	├── 📁 mfe-root  
	├── 📁 mfe-auth  
	├── 📁 mfe-sidebar  
	├── 📁 mfe-agenda  
	├── 📁 mfe-profile  
	└── 📁 mfe-history


### **mfe-root**

Este módulo atua como o orquestrador de todos os outros microfrontends, portanto é responsável por toda configuração para renderizaçaão e estruturação dos demais microfrontends.

### **mfe-auth**

É um microfrontend responsável por todo o fluxo de autenticação da aplicação, envolvendo o cadastro e o login do usuário.

### **mfe-sidebar**

Refere-se ao menu lateral que irá constituir toda as partes da aplicação em que há a autenticação do usuário.

### **mfe-agenda**

Esse módulo é a home do SysCall. Nele, é possível adicionar contatos, visualizar contatos cadastrados, efetuar ligações através de um teclado virtual, tanto para contatos já cadastrados quanto para números de telefones não registrados, filtrar todos os contatos, somente os bloqueados ou ainda os não bloqueados, bem como ordenar os nomes de contato em ordem crescente ou decrescente.

### **mfe-profile**

No módulo de perfil, o usuário poderá visualizar todos os seus dados de cadastro, assim como será permitido que ele atualize alguns desses dados, encerre sua sessão ou exclua sua conta.

### **mfe-history**

Esse módulo é responsável por todo o histórico de chamadas, sendo possível filtrá-las por atendidas, não atendidas, as que são pertencentes à contatos ou de números desconhecidos. 
