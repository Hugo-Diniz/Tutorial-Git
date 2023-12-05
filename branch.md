Git Branch é um recurso que você pode usar para gerenciar as versões de uma aplicação.

-> **Como usar uma Branch Git?**
  ° Em qualquer projeto Git, podemos visualizar todos os branches digitando o seguinte comando: "git branch";
  
  ° Se nenhuma branch tiver sido criada, você pode utilizar o seguinte comando para criar uma branch: "git branch [nome_da_branch]";
  
  ° Para se "mover" de uma branch para outra utilizamos o seguinte comando: "git checkout [nome_da_branch]";
  
  ° Para removermos uma branch do git podemos usar o seguinte comando: "git branch -d [nome_da_branch_]"
  **OBSERVAÇÃO:** Para removermos uma branch não podemos estar localizado na branch que iremos excluir, para isso vamos ao branch principal
  e em seguida iremos deletar a branch que queremos. Podemos fazer da seguinte forma:
    --> git checkout main
    --> git branch -d [nome_da_branch];
    
  ° Para vincular duas branchs usaremos o seguinte comando: "git merge [nome_da_branch_que_sera_vinculada]";
  
