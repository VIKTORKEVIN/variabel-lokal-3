# variabel-lokal-3

    #include<stdio.h>
    void cetak();
    int main()
    {
    int a,b,t;
    a=5; b=2;
    t=a+b;
    cetak();
    }
    void cetak()
    {
    printf("%d",t);
    //terjadi error, t tidak dikenal
    }
