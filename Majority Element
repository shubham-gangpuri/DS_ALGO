class Solution {
public:
    int majorityElement(vector<int>& arr) {
        int ele=arr[0];
        int count=0;
        for(int i=0;i<arr.size();i++){
            if(count==0)ele=arr[i];
            count+=(ele==arr[i])?1:-1;
        }
        return ele;
    }
};
