# hello-world
initial public repository
int a[10];
int i,j,temp;
for(i=0;i<10;i++)
  for(j=0;j<10-i;j++)
    if(a[j]>a[j+1])
      {
        temp=a[j];
        a[j]=a[j+1];
        a[j+1]=temp;
      }
