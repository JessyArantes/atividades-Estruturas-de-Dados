# 📝 Desafio War Estruturado – Tema 1

Bem-vindo ao repositório de exercícios em C! Este repositório contém uma coleção de exercícios resolvidos em C que foram desenvolvidos para praticar conceitos de programação.

# 👨‍💻 NIVEL BASICO

📋 Como funciona o código

✔️Struct Territorio: agrupa os dados relacionados a um território, facilitando o gerenciamento.

✔️Leitura de strings: para o nome, usei scanf(" %29[^\n]", ...) para permitir nomes com espaços e limitar o tamanho para evitar overflow.

✔️Leitura da cor: como a cor é uma palavra simples, usei scanf(" %9s", ...).

✔️Laço for: para entrada e saída dos dados, garantindo código limpo e fácil manutenção.

✔️Comentários: explicam cada parte do código para facilitar entendimento e futuras modificações.

✔️Interface clara: mensagens orientam o usuário sobre o que digitar.

✔️Desempenho: o programa exibe os dados imediatamente após o cadastro, garantindo resposta rápida.


# 👨‍💻 NIVEL INTERMEDIARIO

📋 Como funciona o código

✔️Alocação dinâmica: o vetor mapa é alocado com calloc conforme o número informado pelo usuário.

✔️Cadastro: função cadastrarTerritorios lê os dados usando ponteiros.

✔️Exibição: função exibirTerritorios mostra o estado atual dos territórios.

✔️Ataque: função atacar recebe ponteiros para os territórios atacante e defensor, simula dados aleatórios e atualiza os dados conforme regras.

✔️Validações: impede ataques inválidos (território próprio, índices fora do intervalo, tropas insuficientes).

✔️Interface: mensagens claras orientam o usuário.

✔️Memória: free é chamado no final para liberar o vetor.

✔️Aleatoriedade: srand(time(NULL)) garante números diferentes a cada execução.

✔️Comentários: explicam cada parte do código para facilitar manutenção.

# 👨‍💻 NIVEL  MESTRE

📋 Como funciona o código

✔️Missões pré-definidas: armazenadas em vetor de strings.

✔️Atribuição dinâmica: cada missão do jogador é alocada com malloc e copiada via strcpy.

✔️Verificação de missão: função verificarMissao implementa lógica simples para cinco missões diferentes.

✔️Passagem por ponteiros: missões e territórios manipulados via ponteiros.

✔️Modularização: funções específicas para cadastro, exibição, ataque, atribuição e verificação de missões, liberação de memória.

✔️Interface: clara e orienta o jogador durante o jogo.

✔️Validações: impedem ataques inválidos e garantem que o jogador só ataque com seus territórios contra inimigos.

✔️Memória: toda alocação dinâmica é liberada ao final.

✔️Aleatoriedade: srand(time(NULL)) para dados e sorteio de missões.
