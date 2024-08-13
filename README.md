# Menu-driven-gokulk
#include <stdio.h>

int main() {

 int r, c, a[100][100], b[100][100], result[100][100], i, j;

 int choice;

 // Input the number of rows and columns

 printf("Enter the number of rows (between 1 and 100): ");

 scanf("%d", &r);

 printf("Enter the number of columns (between 1 and 100): ");

 scanf("%d", &c);

 // Input elements of the first matrix

 printf("\nEnter elements of 1st matrix:\n");

 for (i = 0; i < r; ++i)

 for (j = 0; j < c; ++j) {

 printf("Enter element a%d%d: ", i + 1, j + 1);

 scanf("%d", &a[i][j]);

 }

 // Input elements of the second matrix

 printf("Enter elements of 2nd matrix:\n");

 for (i = 0; i < r; ++i)

 for (j = 0; j < c; ++j) {

 printf("Enter element b%d%d: ", i + 1, j + 1);

 scanf("%d", &b[i][j]);

 }

 while (1) {

 // Menu for operation choice

 printf("\nChoose the operation to perform:\n");

 printf("1. Addition\n");

 printf("2. Subtraction\n");

 printf("3. Exit\n");

 printf("Enter your choice (1, 2, or 3): ");

 scanf("%d", &choice);

 switch (choice) {

 case 1:
