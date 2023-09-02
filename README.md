# calculator-using-only-c
//this source code is used to solve only -algebraic-calculation -Trigonometric-Differentiation-Integration -square root of any-power operation-
//Starts from Here::
#include<stdio.h>
#include<conio.h>
#include<math.h>
//SCIENTIFIC CALCULATOR:
int main (){
      for(int i=0;;i++){

printf("enter (1) for ALGEBRIC       calculation\n");
printf("enter (2) for DERIATIVE   of trigonometry function\n");
printf("enter (3) for INTEGRATION of trigonometry function\n");
printf("enter (4) for square root\n");
printf("enter (5) for operate power operation between any 2 number(2^4 = 10)\n");

int calculator;
scanf("%d",&calculator);
switch (calculator){

case 1 : printf("welcome to ALGEBRIC world\n");
                        printf("enter (+) for sum\n");
                        printf("enter (-) for SUBTRACT\n");
                        printf("enter (*) for MULTIPLY\n");
                        printf("enter (/) for DIVIDE\n");
                        printf("enter (o/o) for PERCENTAGE OF ANY NUMBER\n");
                        char alg;
                        scanf(" %c",&alg);
                        switch (alg){
                              case '+' : printf("WELCOME TO SUM WORLD\n");
                                         float a;
                                         float b;
                                         printf("enter your first number\n");
                                         scanf("%f",&a);
                                         printf("enter second number\n");
                                         scanf("%f",&b);
                                         float sum;
                                         sum=a+b;
                                         printf("sum is %f\n",sum);
                        break;
                              case '-' : printf("WELCOME TO SUBTRACTION WORLD \n");
                                         float c;
                                         float d;
                                         printf("enter first number\n");
                                         scanf("%f",&c);
                                         printf("enter your second number\n");
                                         scanf("%f",&d);
                                         float sub;
                                         sub = c-d;
                        
                                         printf("subtraction is %f\n",sub);  
                        break;
                              case '*' : printf("WELCOME TO MULTIPLY WORLD\n");
                                         float e;
                                         float f;
                                         printf("enter first number\n");
                                         scanf("%f",&e);
                                         printf("enter your second number\n");
                                         scanf("%f",&f);
                                         float mul;
                                         mul = e*f;
                        
                                         printf("multiplication is %f\n",mul);  
                        break;
                              case '/' : printf("WELCOME TO DIVISION WORLD\n");
                                         float g;
                                         float h;
                                         printf("enter first number\n");
                                         scanf("%f",&g);
                                         printf("enter your second number\n");
                                         scanf("%f",&h);
                                         float div;
                                         div = g/h;
                        
                                         printf("division is %f\n",div);                                          
                        break;
                              case '%' : printf("WELCOME TO PERCENTAGE WORLD\n");
                                         float i;
                                         float j;
                                         printf("enter the number you want to find it's pecentage\n");
                                         scanf("%f",&i);
                                         printf("from which number you  want to find it's percentage\n");
                                         scanf("%f",&j);
                                         float per;
                                         per = (i/j)*100;

                                         printf("percentage is %f\n",per);  
                        break;
                        default : printf("syntax error\n");
                        }
                                                                                                      printf("THANKS FOR VISIT\n");

break;

case 2 : printf("WELCOME TO DIFFERENTIATION WORLD\n");      

         printf("enter (1) for DERIVATIVE OF sinx:\n");
         printf("enter (2) for DERIVATIVE OF cosx:\n");
         printf("enter (3) for DERIVATIVE OF tanx:\n");
         printf("enter (4) for DERIVATIVE OF cotx:\n");
         printf("enter (5) for DERIVATIVE OF secx:\n");   
         printf("enter (6) for DERIVATIVE OF cosecx:\n");
         int der;
         scanf("%d",&der);
         switch(der){                              
                              case 1 :    printf("your answer is :: cosx\n");
                        break;
                              case 2 :    printf("your answer is :: -sinx\n");
                        break;
                              case 3 :    printf("your answer is :: secx.secx\n");
                        break;
                              case 4 :    printf("your answer is :: -cosecx.cosecx\n");
                        break;
                              case 5 :    printf("your answer is :: secx.tanx\n");
                        break;
                              case 6 :    printf("your answer is :: -cosecx.cotx\n");
                        break;

                        default : printf("syntax error\n");
                        }
                                                                              printf("THANKS FOR VISIT\n");

break;

case 3 : printf("WEL COME TO INTEGRATION WORLD\n");
         printf("enter (1) for INTEGRATION OF sinx      :\n");
         printf("enter (2) for INTEGRATION OF cosx      :\n");
         printf("enter (3) for INTEGRATION OF tanx      :\n");
         printf("enter (4) for INTEGRATION OF cotx      :\n");
         printf("enter (5) for INTEGRATION OF secx      :\n");   
         printf("enter (6) for INTEGRATION OF cosecx    :\n");
         printf("enter (7) for INTEGRATION OF sec^2(x)  :\n");
         printf("enter (8) for INTEGRATION OF cosec^2(x):\n");

         int inte;
         scanf("%d",&inte);
         switch(inte){
                              case 1 :    printf("your answer is :: -cos\n");
                        break;
                              case 2 :    printf("your answer is :: sinx\n");
                        break;
                              case 3 :    printf("your answer is :: ln sec(x) [or] -ln cos(x)\n");
                        break;
                              case 4 :    printf("your answer is :: ln sin(x)\n");
                        break;
                              case 5 :    printf("your answer is :: ln(sec(x)+tan(x))\n");
                        break;
                              case 6 :    printf("your answer is :: ln(cosec(x)-cot(x)");
                        break;
                              case 7 :    printf("your answer is :: tanx\n");
                        break;
                              case 8 :    printf("your answer is :: -cotx\n");
                         break;     
                        default : printf("syntax error\n");
                        }
                                                                              printf("THANKS FOR VISIT\n");

break;

  case 4 : printf("WELCOME to SQUARE ROOT world\n");
            float k;
            printf("enter a value to find it's square root\n");
            scanf("%f",&k);
            float sr = sqrt(k);
            printf("square root of %f is %f\n",k,sr);
                                                                              printf("THANKS FOR VISIT\n");
break;

case 5 : printf("WELCOME to POWER FUNCTION world\n");
            int m,n;
            printf("enter base of the power functio\n");
            scanf("%d",&m);
            printf("enter power of this power function\n");
            scanf("%d",&n);
            double z = pow(m,n);
            printf("power is = %lf\n",z);
                                                                              printf("THANKS FOR VISIT\n");
break;
default : printf("syntax error\n");
}   //switch case:
printf("\n\n");
}    //for loop:
     return 0;
}
