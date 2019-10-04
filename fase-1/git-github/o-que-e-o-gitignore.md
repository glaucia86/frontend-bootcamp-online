# O que é o .gitignore?

Às vezes, há arquivos sensíveis \(exemplo: senhas\) ou que são irrelevantes e que você não deseja versionar \(exemplo: node\_module\).

O Git usa um arquivo oculto chamado `.gitignore` para indicar quais arquivos ou tipos de arquivos \(exemplo:  _.pkl,  .ipynb\_checkpoints_\) não devem ser rastreados para o versionamento. Depois de adicionar nomes de arquivos ao arquivo `.gitignore`, as alterações feitas nos arquivos que correspondem a esses nomes não serão rastreadas.

Exemplo:

* Crie um arquivo chamado "credentials.json" no diretório do seu repositório. 
* Se você executar o `git status`, deverá ver "credentials.json" na seção de arquivos não acompanhados. 
* Agora, crie um arquivo chamado `.gitignore` - se ele não existir. 
* Adicione o texto "credentials.json" ao arquivo `.gitignore`
* Salve e feche o arquivo `.gitignore` 
* Se você executar o `git status`, "credentials.json" não deverá mais aparecer. 

É uma boa prática adicionar, definir as regras e enviar o arquivo `.gitignore` para o GitHub, para que seus colaboradores possam ver \(e adicionar\) quais arquivos não devem ser rastreados no repositório.
