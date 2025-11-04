# AQI-EEL-TUT1
#include<stdio.h>
int main(){
    int aqi ;
    printf("current AQI-");
    scanf("%d" ,&aqi);
    printf("you have entered %d air quality index\n",aqi);
    if(aqi<100){      
        printf("==========================\n");
        printf("Air Quality: Good\n");
        printf("==========================");
    }
    else {(aqi>=100); 
    printf("==========================\n");
  printf("Air Quality: Unhelathy\n"); 
  printf("==========================");
    }
  return 0; 
}  
