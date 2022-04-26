Vowel Check in C++ :

#include<iostream>
using namespace std;
int main()
{
    char ch;
    bool lowercase_vowel,uppercase_vowel;
    cout<<"Enter an alphabet:";
    cin>>ch;
    lowercase_vowel=(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u');
    uppercase_vowel=(ch=='A'||ch=='B'||ch=='I'||ch=='O'||ch=='U');
    if (lowercase_vowel||uppercase_vowel)
    {
        cout<<endl<<ch<<" is a vowel";
    }
    else
    {
        cout<<endl<<ch<<" is a consonant";
    }
return 0;
}
