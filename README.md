# June-Recursion-algorith
This repo will contains question on different data structure like array, int, string etc. on which we perform different operations through recursion.


 public int Rec(int []a,int i,int find){
 //Base case for element we are searching for if found then stop
       if(a[i]==find)
       {
           return i;
       }
//If element is not fount we have to stop which we will track by not letting our i go beyond a.length 
       if(i<a.length){
           return -1;
       }  
// If we are yet to call our function we call it here 
else{
        return Rec(a,i,find);
       }
    }

**For Arrays:**
   Generally 2 base cases  1. If our operation succeed
                           2. If operation fails and we have reached array limiting size
