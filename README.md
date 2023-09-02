# calculator-using-only-c
this source code is used to solve only -algebraic-calculation -Trigonometric-Differentiation-Integration -square root of any-power operation-<br/>
//Starts from Here::<br/>
#include<stdio.h><br/>
#include<conio.h><br/>
#include<math.h><br/>
//SCIENTIFIC CALCULATOR:<br/>
int main (){<br/>
      for(int i=0;;i++){
<br/>
printf("enter (1) for ALGEBRIC       calculation\n");<br/>
printf("enter (2) for DERIATIVE   of trigonometry function\n");<br/>
printf("enter (3) for INTEGRATION of trigonometry function\n");<br/>
printf("enter (4) for square root\n");<br/>
printf("enter (5) for operate power operation between any 2 number(2^4 = 10)\n");<br/>
<br/>
int calculator;<br/>
scanf("%d",&calculator);<br/>
switch (calculator){<br/>

case 1 : printf("welcome to ALGEBRIC world\n");<br/>
                        printf("enter (+) for sum\n");<br/>
                        printf("enter (-) for SUBTRACT\n");<br/>
                        printf("enter (*) for MULTIPLY\n");<br/>
                        printf("enter (/) for DIVIDE\n");<br/>
                        printf("enter (o/o) for PERCENTAGE OF ANY NUMBER\n");<br/>
                        char alg;<br/>
                        scanf(" %c",&alg);<br/>
                        switch (alg){<br/>
                              case '+' : printf("WELCOME TO SUM WORLD\n");<br/>
                                         float a;<br/>
                                         float b;<br/>
                                         printf("enter your first number\n");<br/>
                                         scanf("%f",&a);<br/>
                                         printf("enter second number\n");<br/>
                                         scanf("%f",&b);<br/>
                                         float sum;<br/>
                                         sum=a+b;<br/>
                                         printf("sum is %f\n",sum);<br/>
                        break;<br/>
                              case '-' : printf("WELCOME TO SUBTRACTION WORLD \n");<br/>
                                         float c;<br/>
                                         float d;<br/>
                                         printf("enter first number\n");<br/>
                                         scanf("%f",&c);<br/>
                                         printf("enter your second number\n");<br/>
                                         scanf("%f",&d);<br/>
                                         float sub;<br/>
                                         sub = c-d;<br/>
                        
                                         printf("subtraction is %f\n",sub);  <br/>
                        break;<br/>
                              case '*' : printf("WELCOME TO MULTIPLY WORLD\n");<br/>
                                         float e;<br/>
                                         float f;<br/>
                                         printf("enter first number\n");<br/>
                                         scanf("%f",&e);<br/>
                                         printf("enter your second number\n");<br/>
                                         scanf("%f",&f);<br/>
                                         float mul;<br/>
                                         mul = e*f;<br/>
                        <br/>
                                         printf("multiplication is %f\n",mul);  <br/>
                        break;<br/>
                              case '/' : printf("WELCOME TO DIVISION WORLD\n");<br/>
                                         float g;<br/>
                                         float h;<br/>
                                         printf("enter first number\n");<br/>
                                         scanf("%f",&g);<br/>
                                         printf("enter your second number\n");<br/>
                                         scanf("%f",&h);<br/>
                                         float div;<br/>
                                         div = g/h;<br/>
                        
                                         printf("division is %f\n",div);        <br/>                                  
                        break;<br/>
                              case '%' : printf("WELCOME TO PERCENTAGE WORLD\n");<br/>
                                         float i;<br/>
                                         float j;<br/>
                                         printf("enter the number you want to find it's pecentage\n");<br/>
                                         scanf("%f",&i);<br/>
                                         printf("from which number you  want to find it's percentage\n");<br/>
                                         scanf("%f",&j);<br/>
                                         float per;<br/>
                                         per = (i/j)*100;<br/>

                                         printf("percentage is %f\n",per);  <br/>
                        break;<br/>
                        default : printf("syntax error\n");<br/>
                        }<br/>
                                                                                                      printf("THANKS FOR VISIT\n");<br/>

break;<br/>

case 2 : printf("WELCOME TO DIFFERENTIATION WORLD\n");      <br/>

         printf("enter (1) for DERIVATIVE OF sinx:\n");<br/>
         printf("enter (2) for DERIVATIVE OF cosx:\n");<br/>
         printf("enter (3) for DERIVATIVE OF tanx:\n");<br/>
         printf("enter (4) for DERIVATIVE OF cotx:\n");<br/>
         printf("enter (5) for DERIVATIVE OF secx:\n");   <br/>
         printf("enter (6) for DERIVATIVE OF cosecx:\n");<br/>
         int der;<br/>
         scanf("%d",&der);<br/>
         switch(der){          <br/>                    
                              case 1 :    printf("your answer is :: cosx\n");<br/>
                        break;<br/>
                              case 2 :    printf("your answer is :: -sinx\n");<br/>
                        break;<br/>
                              case 3 :    printf("your answer is :: secx.secx\n");<br/>
                        break;<br/>
                              case 4 :    printf("your answer is :: -cosecx.cosecx\n");
                        break;<br/>
                              case 5 :    printf("your answer is :: secx.tanx\n");<br/>
                        break;<br/>
                              case 6 :    printf("your answer is :: -cosecx.cotx\n");<br/>
                        break;<br/>

                        default : printf("syntax error\n");<br/>
                        }<br/>
                                                                              printf("THANKS FOR VISIT\n");<br/>

break;<br/>

case 3 : printf("WEL COME TO INTEGRATION WORLD\n");<br/>
         printf("enter (1) for INTEGRATION OF sinx      :\n");<br/>
         printf("enter (2) for INTEGRATION OF cosx      :\n");<br/>
         printf("enter (3) for INTEGRATION OF tanx      :\n");<br/>
         printf("enter (4) for INTEGRATION OF cotx      :\n");<br/>
         printf("enter (5) for INTEGRATION OF secx      :\n");   <br/>
         printf("enter (6) for INTEGRATION OF cosecx    :\n");<br/>
         printf("enter (7) for INTEGRATION OF sec^2(x)  :\n");<br/>
         printf("enter (8) for INTEGRATION OF cosec^2(x):\n");<br/>

         int inte;<br/>
         scanf("%d",&inte);<br/>
         switch(inte){<br/>
                              case 1 :    printf("your answer is :: -cos\n");<br/>
                        break;<br/>
                              case 2 :    printf("your answer is :: sinx\n");<br/>
                        break;<br/>
                              case 3 :    printf("your answer is :: ln sec(x) [or] -ln cos(x)\n");<br/>
                        break;<br/>
                              case 4 :    printf("your answer is :: ln sin(x)\n");<br/>
                        break;<br/>
                              case 5 :    printf("your answer is :: ln(sec(x)+tan(x))\n");<br/>
                        break;<br/>
                              case 6 :    printf("your answer is :: ln(cosec(x)-cot(x)");<br/>
                        break;<br/>
                              case 7 :    printf("your answer is :: tanx\n");<br/>
                        break;<br/>
                              case 8 :    printf("your answer is :: -cotx\n");<br/>
                         break;     <br/>
                        default : printf("syntax error\n"); <br/>
                        } <br/>
                                                                              printf("THANKS FOR VISIT\n"); <br/>

break; <br/>

  case 4 : printf("WELCOME to SQUARE ROOT world\n"); <br/>
            float k; <br/>
            printf("enter a value to find it's square root\n");<br/>
            scanf("%f",&k);<br/>
            float sr = sqrt(k);<br/>
            printf("square root of %f is %f\n",k,sr);<br/>
                                                                              printf("THANKS FOR VISIT\n");<br/>
break;<br/>

case 5 : printf("WELCOME to POWER FUNCTION world\n");<br/>
            int m,n;<br/>
            printf("enter base of the power functio\n");<br/>
            scanf("%d",&m);<br/>
            printf("enter power of this power function\n");<br/>
            scanf("%d",&n);<br/>
            double z = pow(m,n);<br/>
            printf("power is = %lf\n",z);<br/>
                                                                              printf("THANKS FOR VISIT\n");<br/>
break;<br/>
default : printf("syntax error\n");<br/>
}   //switch case:<br/>
printf("\n\n");<br/>
}    //for loop:<br/>
     return 0;<br/>
}
