# AUCE- AUTENTICAÇÃO DE CERTIFICADOS
## Status do Projeto: ⚠️ Esperar 
## Descrição do Projeto
O projeto visa automatizar a autenticação de certificados com código
token recebido pelos coordenadores de cursos da Facens, a fim de validálos como horas complementares dentro do semestre em curso.
## Como rodar a aplicação
🔹O Aluno entra no site e insere seus dados (nome do aluno, qual curso/semestre faz, nome do certificado, instituição emissora, horas do curso, código do certificado e PDF do certificado). Não será possível o acompanhamento ainda. 

🔹O coordenador do curso ou outro responsável entra e coloca suas credenciais para acesso ao sistema (credenciais serão previamente criadas e enviadas para os responsáveis). 

🔹Irão aparecer os alunos que já enviaram os certificados e ao clicar sobre um determinado aluno, serão exibidos todos os certificados enviados separadamente, com uma etiqueta mencionando “pré-aprovado”, “pendente”, “inválido” ou “validado".

🔹Ao clicar sobre o certificado todas as informações pertinentes aparecerão para verificação, sendo que, se preenchido corretamente, o status será de “pré-aprovado”.  Após validação dos dados, poderá ser alterado para “validado” pelo usuário, caso esteja tudo correto, “pendente”, caso falte alguma informação a mais do aluno ou “inválido” caso não seja aprovado. 

🔹O status de “pré-aprovado” será devido à automação da busca das informações direto nas plataformas nos quais foram emitidos os certificados, portanto, não será necessário entrar no site, inserir os dados e realizar a busca, porque a própria ferramenta será responsável por buscar essas informações e mostrar ao usuário se está batendo ou não. 

🔹O status de “pendente” será automático caso o certificado não seja por token/código e que necessite de validação de terceiros, caso as informações de validação não sejam abertas ao público ou que haja alguma divergência nas informações contidas no certificado que mereçam maior atenção; 

🔹Deverão ser guardadas no banco de dados todas as informações sobre o certificado e o aluno, esses dados serão utilizados posteriormente para comparação de informações e exibição de duplicidade de certificados

🔹Após o uso e validação dos certificados, deslogar do sistema.

🔹Por enquanto o sistema não fará integração com outro sistema da Facens (TOTVS).

🔹Será permitido o envio de certificados que não possuem token, porém a solução não irá abranger a automação das informações das quais não poderão ser obtidas via site público da emissora.

## Testes realizados
https://www.figma.com/file/csTHd2Iv1U2QkPfJi4Xnpg/Untitled?node-id=0%3A1&t=zPqGDs0sjUDiA72o-1

## Linguagens, dependencias e libs utilizadas 📚
- FIGMA 

## Resolvendo problemas 
- Os responsaveis pelo back-end ainda não possuem totais habilidades para dar inicio ao codigo, portanto, buscamos cursos acessiveis para que possamos ampliar nossos conhecimentos.
- Devido ao fato de não darmos inicio ao codigo nesse momento estamos nos aprofundando na base, buscando artigos de projetos semelhantes e auxilio dos professores.

## Desenvolvedores
-Renata Negrini

-Vinicius Machado

-Hillary Ferreira

## Direitos Autorais - 2023 StarTech
