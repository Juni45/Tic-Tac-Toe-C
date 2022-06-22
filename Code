#include <stdio.h>

char board[3][3];
const char PLAYER = 'X';
const char COMPUTER = 'O';

void reserBoard();
void printBoard();
int checkfreespaces();
void playerMove();
void computerMove();
char checkWinner();
void printWinner(char);




int main(){
    char winner = ' ';


    while(winner == ' ' && checkfreespaces() != 0){
        printBoard();
        playerMove();
        winner = checkWinner();
    }


    return 0;
}




void reserBoard(){
    for(int linha =  0; linha < 3; linha++){
        for(int colum = 0; colum < 3; colum++){
            board[linha][colum] = ' ';
        }
    }
}



void printBoard(){
    printf("\n");
    printf(" %c | %c | %c \n", board[0][0], board[0][1], board[0][2]);
    printf("--|--|--\n");
    printf(" %c | %c | %c \n", board[1][0], board[1][1], board[1][2]);
    printf("--|--|--\n");
    printf(" %c | %c | %c \n", board [2][0], board[2][1], board[2][2]);
    printf("\n");


}




int checkfreespaces(){
    int freeSpaces = 9;
    for(int linha = 0; linha <3; linha++){
        for(int colum = 0; colum < 3; colum ++){
            if(board[linha][colum] != ' '){
                freeSpaces--;
            }
        }
    }
    return freeSpaces;
}



void playerMove(){
    int x, y;
    do
    {    
    printf("Insira a linha (1,3): " );
    scanf("%d", &x);
    x--;

    printf("Insira coluna (1,3): ");
    scanf("%d", &y);
    y--;

    if(board[x][y] != ' '){
        printf("Jogada invalida");
        
    }else{
        board[x][y] = PLAYER;
        
    }

    } while (board[x][y] != ' ');
    
}


void computerMove(){

}



char checkWinner(){
    //ver por linha
    if()

}



void printWinner(char winner){

}
