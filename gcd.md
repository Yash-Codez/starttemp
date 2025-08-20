 // gcd for long
    static long gcd(long a, long b){
        if (a < 0) a = -a;
        if (b < 0) b = -b;
        while (b != 0) {
            long t = a % b;
            a = b;
            b = t;
        }
        return a;
    }
