bool isPerfectSquare(int num) {
    
        if(num<0){
            return false;
        }
        long i=1;
        while(i*i<=num){
            if(i*i==num){
            return true;
        }
        i++;}
        return false;}
