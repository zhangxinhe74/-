#算法题 20213/7 

##对比

### 1
    let ard = [];
    function yzm(){
      var str = '';
      for(var j=0;j<=999;j++){
          for(var i=0; i<=5;i++){
            var yzm =Math.floor(Math.random()*10)
            str+=yzm
          }
          if(j!=0){
            str= str.substring(6,12)
            }
          ard.push(str)
    }
    
  }
    yzm();
    console.log(ard)
  ###2.
const arr = new Array(1000).fill('0').map(item =>(''+Math.floor(Math.random() * 1000000)).padStart(6,'0'))
    console.log(arr);