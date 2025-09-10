class Solution {
    public boolean isPalindrome(int x) {
        int ori=x;
        int rev=0,l;
        // if(x<0){
        //     return false;
        // }
        while (x!=0){
            l=x%10;
            rev=(rev*10)+l;
            x/=10;
        }
        if(ori==rev && ori>=0){
            return true;
        }
        else{
            return false;
        }
    }
}
