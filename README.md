#include <stdio.h>
#include <cs50.h>

int main(void)
{
    string names[5];
    names[0] = "EMMA";
    names[1] = "RODRIGO";
    names[2] = "PHILLIP";
    names[3] = "MINJUN";
    printf("%c%c%c%c\n", names[0][0], names[0][1], names[0][2], names[0][3]);
    printf("%s\n", names[0]);
    printf("%s %s %s %s\n", names[0], names[1], names[2], names[3]);
}
