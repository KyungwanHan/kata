아래 코드에서 버그를 찾으시오
```.c
for(unsigned int size = 5; size >=0 ; size--)
{
    a[size] = size;
}
