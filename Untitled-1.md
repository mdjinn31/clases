https://www.youtube.com/watch?v=IrS7lIlIw-g


    if (S < min1) return 0;
    S -= min1;
    if (S < min2_10 * 9) return S / min2_10 + 1 | 0;
    S -= min2_10 * 9;
    return S / min11 + 10 | 0;


    if(s<min1) return 0;
    if(s==min1) return 1;
    if(s-min1<=min2_10*9) return 1 + Math.floor((s-min1)/min2_10);
    return Math.floor((s-min1-(min2_10*9))/min11+10);


        return Math.max(
        maxW >= weight1 && value1,
        maxW >= weight2 && value2,
        maxW >= weight1 + weight2 && value1 + value2
    );