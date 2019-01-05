# C-Membuat-tabel-fotokopian-dari-1-100-lembar

    #include <stdio.h>
    #include <stdlib.h>
    int main (void)
    {
    int a=1,h;
    printf("Harga fotocopy\n\n");
    printf("Jumlah lembar\t| Harga\t\n");
    while (a<=100)
    {
        h = a*95;
        printf ("------------------_\n");
        printf("%d lembar =\t|Rp%d\n",a,h);
        a++;

    }
    printf("\n");
    system("pause");
    return 0;
    }
    
Hasil
![img](https://github.com/Rafflesia3/C-Membuat-tabel-fotokopian-dari-1-100-lembar/blob/master/C++%20Membuat%20tabel%20fotokopian%20dari%201-100%20lembar.png?raw=true)
