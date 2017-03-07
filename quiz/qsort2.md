아래 코드를 완성하시오 
```.c

void qsort(int left, int right)
{
    if(left < right)
    {
        int pivot = partition(left, right);
        // 코드를 넣으시오
        // 코드를 넣으시오
    }
}

int partition(int left, int right)
{
    int pivot = left;
    int i=left+1; int j=right;
    
    while(1)
    {
        while(Input[i] <= Input[pivot] && i<right) i++;
        while(Input[j] > Input[pivot]) j--;
        
        if(i>=j) break;
        // 코드를 넣으시오
    }
    // 코드르 넣으시오
    
    return j;
}
