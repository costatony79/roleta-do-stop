# Roleta do Stop

Jogo de Stop (adedonha) para a sala de aula, com duas roletas: uma de letras e outra
de categorias. Ao clicar em **Girar**, as duas giram juntas e o estudante tem
10 segundos para dizer algo da categoria com a letra sorteada.

- Categorias editáveis, com siglas (ex.: `CEP = Cidade, estado ou país`).
- Letras podem ser tiradas da roleta (botão para tirar K, W, X e Y).
- Tempo ajustável de 3 a 60 segundos, com contagem visual e sons.
- Não repete a mesma letra ou categoria seguidas.
- As configurações ficam salvas no navegador.

## Modo eliminação

- Tela de participantes: cada nome é digitado e confirmado um por um, e aparece na hora para a turma ver. Botão para usar a turma da aula anterior.
- 5, 10 ou 15 segundos para cada um responder.
- Durante o jogo, as roletas ficam grandes nas laterais, com só a metade aparecendo e a seta virada para dentro.
- As roletas giram e a combinação vale até todos responderem uma vez. Os alunos respondem em ordem sorteada.
- O professor clica em **✔ Falou!** (ou aperta Espaço) quando o aluno acerta. Se o tempo acabar sem o clique, o aluno é eliminado.
- Depois que todos falaram, as roletas giram de novo e a disputa recomeça com quem sobrou, em nova ordem.
- Botões para pausar e para devolver o último eliminado (em caso de clique esquecido).
- Se ninguém da rodada acertar, todos os que estavam nela voltam e as roletas giram de novo.
- O campeão precisa acertar a última rodada: quando só ele acerta, aparece a tela do campeão.

As instruções ficam em `como-jogar.html`, aberta pelo botão **Como jogar**.

O jogo é uma página única (`index.html`), sem dependências. Para testar, basta abrir o arquivo
no navegador.
