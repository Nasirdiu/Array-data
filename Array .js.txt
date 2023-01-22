  var data = [10,100,1,59,10,120,4,-1,30];
    let max = array[0], min = array[0];
    for (let i = 0; i < array.length; i++) {

        if (array[i] > max) { max = array[i]; }
  
        if (array[i] < min) { min = array[i]; }
    }
    console.log("max = " + max);
    console.log("min = " + min);