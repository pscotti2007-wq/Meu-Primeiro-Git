# teste git de Pablo Scotti
# codigo 100% atualizado 2026
# DOCUMENTAÇÃO
Qual é a diferença entre Working Directory, Staging Area e Repository?
O Working Directory é a pasta de trabalho onde ficam os arquivos do projeto e onde realizamos as alterações. A Staging Area é uma área intermediária onde colocamos os arquivos que serão incluídos no próximo commit, utilizando o comando git add. Já o Repository é onde ficam armazenados os commits e o histórico de versões do projeto.
Qual é a diferença entre git commit e git push?
O git commit registra as alterações no repositório local, criando uma nova versão do projeto no computador. Já o git push envia os commits que estão no repositório local para um repositório remoto, como o GitHub.
É possível realizar vários commits antes de executar um git push? Explique.
Sim. É possível realizar vários commits localmente antes de executar o git push. Cada commit registra uma alteração ou conjunto de alterações no histórico local do projeto. Quando o git push for executado, os commits que ainda não foram enviados serão enviados para o repositório remoto.
Por que é interessante realizar commits pequenos e descritivos?
Commits pequenos e descritivos facilitam a organização e o acompanhamento do desenvolvimento do projeto. Eles permitem identificar facilmente o que foi alterado em cada etapa e também facilitam a localização de problemas ou a recuperação de uma versão anterior do projeto.
O que acontece com os commits locais quando ainda não executamos o git push?
Os commits continuam armazenados no repositório local do computador. Eles não são perdidos por não executar o git push. Porém, ainda não estarão disponíveis no repositório remoto, como o GitHub. Quando o git push for executado, esses commits poderão ser enviados para o repositório remoto.
Como verificar, pelo GitHub, se os commits foram enviados corretamente?
Para verificar se os commits foram enviados corretamente, basta acessar o repositório no GitHub e abrir o histórico de commits. Se os commits realizados localmente, como “Adiciona documentação dos produtos” e “Atualiza documentação do README”, aparecerem no histórico, significa que foram enviados com sucesso. Também é possível verificar se o arquivo README.md está atualizado diretamente no repositório.