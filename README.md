# Menentukan-Bilangan-Yang-Terkecil-Dari-3-Bilangan
    #include<iostream>
    #include<conio.h>
    using namespace std;

    int main()
    {
        int bil1, bil2, bil3;
        cout << "Bilangan 1: ";
        cin >> bil1;
        cout << "Bilangan 2: ";
        cin>> bil2;
        cout<< "Bilangan 3: ";
        cin >> bil3;

        if(bil1<bil2)
        {
            if(bil1 < bil2 )
            {
                cout << bil1 << " adalah nilai terkecil.";
            }
            else{
                if( bil3 < bil2 )
                {
                    cout << bil3 << " adalah nilai terkecil.";
                }
            }
        }
        else{
            if(bil2 < bil3)
            {
                cout << bil2 << " adalah nilai terkecil.";

            }
            else{
                cout << bil3 << " adalah nilai terkecil.";
            }
        }
    }
    
   ![img](https://raw.githubusercontent.com/BambangPriam/Menentukan-Bilangan-Yang-Terkecil-Dari-3-Bilangan/master/Menentukan%20Yang%20Terkecil%20Dari%203%20Bilangan.png)
