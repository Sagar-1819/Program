#include <stdio.h>

#include <math.h>

int main()

{
    
int a, b, c,j,i=0,k=1,l=1,h;
  
printf("Enter a and b values" );
scanf("%d%d",&a,&b);
    
printf("%d\n",a);
   
 for (int i=0;i<b-1;i++)

    {
        
	a=a*2;
        
	printf("%d",a);
	
 h=l++;
 
	 k=pow(2,h);
    
	 c=a;
        
	 for(j=1;j<k;j++)
           
		{
          
		 c++;
       
		  printf(" %d",c);
      
		 }
         
	printf("\n");

        }
    

  
  return 0;

}
