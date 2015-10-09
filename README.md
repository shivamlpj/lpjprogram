# lpjprogram static int sum=0,r;
 
    if(num!=0){
         r=num%10;
         sum=sum*10+r;
         checkPalindrome(num/10);
    }
 
    return sum;
