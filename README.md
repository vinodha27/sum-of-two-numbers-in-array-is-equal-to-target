# sum-of-two-numbers-in-array-is-equal-to-target
Input: nums = [2,7,11,15], target = 9 Output: [0,1] Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].

class Main {
    public static void main(String[] args) {
     int[] a={2,8,8,6,7};
     int t=9;
     for(int i=0;i<a.length;i++)
     {
         for(int j=i+1;j<a.length;j++)
         {
             if(a[i]+a[j]==t)
             {
                 System.out.println(a[i]);
                 System.out.println(a[j]);
             }
         }
     }
     
    }
}
