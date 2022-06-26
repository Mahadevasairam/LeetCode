class Solution {
    public int lengthOfLastWord(String s) {
        char[] str = s.toCharArray();
        int count=0; int n = str.length;
        for (int i = n-1;i>=0;i--){
            if(n==1) count =1;
            else if(count>0 && str[i]== ' '){
                    break;
                }
            else if (str[i]!=' ') {
                count++;
        }
        }
      return count;  
    }
}
