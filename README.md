# Roullete Game

Gambling has never been this fun!

I learned a lot about the C language developing this code for a university project.

Game developed using:
- C

Below you can see a piece of the code:
```c
creditos = 100 ;

  printf("Hey, bem-vindo à ROLETA.\n");
  printf("Os seus créditos: 100$\n");

  while(creditos > 0) {
    escolha = 0;
    while (escolha != 1 && escolha != 2) {

      printf("Escolha o modo de jogo: \n");
      printf("1-Impar/Par\n");
      printf("ou\n");
      printf("2-Número específico\n");
      scanf("%d", &escolha);

    }
      printf("Quanto quer apostar?\n");
      scanf("%d", &aposta);
      if(aposta > creditos) {
        printf("Não tem créditos suficientes, faça uma aposta válida.\nOs seus créditos são: %d$\n",creditos);
        scanf("%d", &aposta);
      }
      
```

You can see a print of the game running here:

![](https://i.imgur.com/8wDRdKL.png)

And here you can find a link to an online C compiler in case you don't already have where to run the code: 
[https://www.onlinegdb.com/online_c_compiler](https://www.onlinegdb.com/online_c_compiler "https://www.onlinegdb.com/online_c_compiler")

If you would like to try this game for yourself, please do so. But just don't get too addicted. 
