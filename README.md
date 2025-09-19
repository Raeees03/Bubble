//BUBBLE SORT
#include<stdio.h>
int main (){
    int arr[]={3,4,5,6,2,9,4,6};
    for(int i=0;i<8;i++){
        for(int j=i+1;j<8-1;j++){
        if(arr[i]>arr[j]){
           int temp=arr[i];
           arr[i]=arr[j];
           arr[j]=temp;
        }
        }
    }
   for(int i=0;i<8;i++){
    printf("%d ",arr[i]);
}
    return 0;
}
