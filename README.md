## PROJETO 1 SE - Implementar echo UART pelo BLE, com conversão de letras minúsculas

ROTEIRO
- Implementar o periférico que deverá
    - ter uma característica com permissão de escrita e que irá receber os dados
    - ter uma característica sem permissão e que realiza notificação
        - a notificação deverá ser enviada sempre que um dado for recebido
        - o conteúdo da notificação é o dado recebido com as letras minúsculas convertidas para maiúsculas

- Implementar o central que deverá
    - procurar e se conectar ao periférico
    - enviar ao periférico o que o usuário escreve no terminal
    - imprimir a resposta enviada pelo periférico

- Testar a implementação no Renode

Professor da disciplina:
* Erick Barboza                   - Professor Adjunto              - erick@ic.ufal.br

Participantes:
* Alef Farias                     - Engenharia de Computação       - aaof@ic.ufal.br
* Aristoteles Barros              - Engenharia de Computação       - apb@ic.ufal.br
* Mateus Monteiro                 - Engenharia de Computação       - mms@ic.ufal.br
* João Muniz Neto                 - Engenharia de Computação       - jsmn@ic.ufal.br
* Wilamis Aviz                    - Engenharia de Computação       - wmaa@ic.ufal.br
