- 👋 Hi, I’m Achille
- I'm an engineering student at ECE Lyon.

```c

#include <stdio.h>

int note=0;

void function()
{

  do
  {
    printf("Veuillez saisir le point bonus :\n");
    scanf("%d", &note);
  } while(note<=0);
  
}

int main()
{
  function();
  printf("Merci pour le point bonus !");
  
  return 0;
}

```
