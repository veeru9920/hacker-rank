# hacker-rank
// minmax
long sum=0;
    Collections.sort(arr);
    for(int i=0;i<arr.size();i++){
        sum=sum+arr.get(i);
    }
    long max=sum-arr.get(0);
    long min=sum-arr.get(arr.size()-1);
    System.out.println(min+" "+max);
