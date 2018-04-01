# my-first
Just a start

Dengyan here,I am a university student.
I have learned C.

void prime_select()
{
    prime[0] = prime[1] = 0;
    for(int i=2; i*i<=M; i++)
    {
        if(prime[i])
        {
            for(int j=i*i; j<=M; j+=i)
              prime[j] = 0;
        }
    }
}
