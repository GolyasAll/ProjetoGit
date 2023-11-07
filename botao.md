Aqui irei desenvolver o botão

Aqui foi criado uma nova brench

Agora, ai vem o comando para criar uma nova brench

"git checkout -b 'novo-botao'
E ai então, no VC code você cria um novo arquivo, no exemplo a cima é um botão então
//botao.md//

aqui, após criar o arquivo, escrever algo lá, você na hora de fazer o commit irá fazer
"git commit -m "novo botao"

"git push origin novo-botao" Essa alteração não foi fenta na "main" mas sim na nova brench que demos este nome a ela "novo-botao".

Após ter feito todas as alterações nessa nova "Ramificação" você por acaso quer juntar, a ramificação com o projeto principal, sua "main"

Então você vai no best e digita os seguintes comandos.
"git checkout main" Isso irá voltar para a brench principal

"git merge novo-botao" Aqui você fara o merge "junção" Mas precisa colocar o nome da brench criada, como minha nova brench tinha o nome de "novo-botao" foi assim que ficou.

"git push origin main" Isso irá subir todas as alterações.