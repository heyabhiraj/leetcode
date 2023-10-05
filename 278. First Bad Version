/* The isBadVersion API is defined in the parent class VersionControl.
      boolean isBadVersion(long version); */

public class Solution extends VersionControl {
    public int firstBadVersion(int n) {
        int  left = 0 ; 
        int  right = n ; 
        int  minBadVersion = 0 ;
            while (left <= right)
        {
            int mid = (left + right) / 2 ; 

            if (isBadVersion(mid) == true)
            {
                minBadVersion = mid ; 
                right = mid - 1 ; 
            }
            else
            {
                left = mid + 1 ; 
            }
        }
        return minBadVersion ;
    }
}
