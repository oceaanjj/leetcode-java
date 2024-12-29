class Solution {
    public int[] twoSum(int[] nums, int target) {
        int y = 0, x = 0;
        for(y = 0; y < nums.length; y++){
            for(x = y + 1; x < nums.length; x++){
              
                if(target == (nums[y] + nums[x]) ){
                   return new int[] {y,x};
                }
            }
        }
        throw new IllegalArgumentException("NO NUMBERS CAN SUM TO MATCH TARGET");
    }
}


class Main {
    public static void main(String[] args) {
        int num[] = {3,2,4};
        Solution solution = new Solution();
        int sum[] = solution.twoSum(num, 6);
        System.out.println("[" + sum[0] + "," + sum[1] + "]");
    }
}
