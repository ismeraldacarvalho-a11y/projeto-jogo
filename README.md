# projeto-jogo
cartas com dois jogadores

int main() {
int resultado1, resultado2;
char primeiroAtributo, segundoAtributo;
int ataque1, ataque2, defesa1, defesa2, recuo1, recuo2;

// gerar numero aleatorio
srand ( time (0) );
ataque1 = 1; // rand () % 100+1; // Numero entre 1 e 100
ataque2 = 0; // rand () % 100+1; // Numero entre 1 e 100
defesa1 = 1; // rand () % 100+1; // Numero entre 1 e 100
defesa2 = 0; // rand () % 100+1; // Numero entre 1 e 100
recuo1 = 0; // rand () % 100+1; // Numero entre 1 e 100
recuo2 = 1; // rand () % 100+1; // numero entre 1 e 100

// Inicio do jogo
printf (" Bem-vindo ao jogo!\n");n
printf (" escolha o primeiro atributo.\n");
printf (" A.Ataque\n");
printf (" D.Defesa\n");
printf (" R.Recuo\n");

printf (" escolha a comparação:");
scanf ("%c, &primeiroatributo);

swith ( primeiroAtributo)
{
case 'A':
case 'a':
printf (" Voçê escolheu a opção Ataque!\n");
resultado1 = ataque1 > ataque2 ? 1:0;
break;
case 'D':
case 'd':
printf ( " Voçê escolheu a opção Defesa !n");
resultado1 = defesa1 > defesa2 ? 1:0;
case 'R':
case 'r':
printf ( " Voçê escolheu a opção Recuo\n");
resultado1 = recuo1 > recuo2 ? 1:0;
break;
default:
printf (n\.opção de jogo Invalida\n);
break
}
printf ( " Escolha o segundo atributo.\n");
printf ( "Atenção: Você deve escolher um atributo diferente do primeiro.\n");
printf ( "A.Ataque\n");
printf ( "D.Defesa\n");
printf ( "R.Recuo\n");
printf ( " Escolha a comparação:");
scanf( "%c, &segundoAtributo);
if ( primeiroAtributo == segundoAtributo)
{
printf ( "Você escolheu o mesmo atributo!");
} else {
swith ( segundoAtributo)
{
case 'A':
case 'a':
printf ( " Voce escolheu a opção Ataque !\n");
resultado2 = ataque1 > ataque2 ? 1:0;
break;
case 'D':
case 'd':
printf ( Você escolheu a opção Defesa !\n");
resultado2 = defeda1 > defesa2 ? 1:0;
break;
case 'R':
case 'r':
printf ( " Você escolheu a opção Recuo \n");
resultado2 = recuo1 > recuo2 ? 1:0;
break;
default:
printf ( " Opção de jogo invalida \n");
break;
}
if (resultado1 && resultado2)
{
printf ( parabens, você Venceu!\n");
} else if ( resultado1 = resultado2){
} else {
printf ( " empatou!\n");
} else {
printf ( " Infelizmente, você perdeu!\n");



at





