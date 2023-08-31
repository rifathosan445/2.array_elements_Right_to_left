# 2.array_elements_Right_to_left
make a array then input "K".Print array  right to left and right=0 k time.



    #include<stdio.h>
    int main()
    {
      int a[5]={1,2,3,4,5},i,k;
      scanf("%d",&k);
      int a2[5];
      int j=k;
      for(i=0;i<5-k;i++)
      {
             a2[i]=a[j];
             j++;
    
      }
      for(i=5-k;i<5;i++)
      {
             a2[i]=0;
      }
    for(i=0;i<5;i++)
    {
           printf("%d,",a2[i]);
    }
      return 0;
    }
    
