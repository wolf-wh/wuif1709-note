# wuif1709-note
28日作业提交地址

<script>

    //成绩的评优
    /*var chengji = prompt('请输入你的成绩');
    if(chengji > 0 && chengji < 60){
        alert('不及格');
    }else if(chengji >= 60 && chengji < 80){
        alert('及格');
    }else if(chengji >= 80 && chengji < 90){
        alert('良好');
    }else if(chengji >= 90 && chengji < 100){
        alert('优秀');
    }else if(chengji == 100){
        alert('满分');
    }else{
        alert('输入有误！');
    }*/
    //星期
    /*var week = prompt('请输入星期数');
    switch (week){
        case '1':alert('星期一');
            break;
        case '2':alert('星期二');
            break;
        case '3':alert('星期三');
            break;
        case '4':alert('星期四');
            break;
        case '5':alert('星期五');
            break;
        case '6':alert('星期六');
            break;
        case '7':alert('星期日');
            break;
        default:alert('输入有误！');
    }*/
    //四则运算
    /*var num1 = Number(prompt('请输入第一个数字'));
    var num2 = Number(prompt('请输入第二个数字'));
    var yunsuanfu = prompt('做什么计算+ - * /');
    switch (yunsuanfu){
        case '+': alert(num1 + num2);
            break;
        case '-': alert(num1 - num2);
            break;
        case '*': alert(num1 * num2);
            break;
        case '/': alert(num1 / num2);
            break;
        default: alert('输入有误！');
    }*/
    //100以内的奇偶数
    /*for(i = 1;i <= 100;i++){
        if(i % 2 == 1){
            document.write('100以内的奇数'+i);
        }else if(i % 2 == 0){
            document.write('100以内的偶数'+i);
        }
        document.write('<br>');
    }*/
    //水仙花数
    /*var a,b,c;
    for(i = 100;i < 1000;i++){
        a = parseInt(i/100);
        b = parseInt((i-a*100)/10);
        c = parseInt(i%10);
        if(a*a*a+b*b*b+c*c*c == i){
            document.write(i);
            document.write("<br>");
        }
    }*/
    //金字塔
    /*for(i = 0;i <= 6;i++){
        for(j = 6;j >= i;j--){
            document.write('&nbsp');
        }
        for(g = 0;g <= i;g++){
            document.write('*&nbsp ');
        }
        document.write('<br>');
    }*/
    //九九乘法表
    /*for(i = 1;i <= 9;i++){
        for(j = 1;j <= i;j++){
            document.write(`${i}*${j}=${i*j}&nbsp`);
            if((i == 3 || i == 4)&&j == 2){
                document.write(' ');
            }
        }
        document.write('<br>');
    }*/
    //十乘十表格
    /*document.write("<table width='400px' height='400px' border=1px cellspacing=0>");
    for(x = 1;x <= 10;x++){
        document.write('<tr>');
        for(y = 1;y <= 10;y++){
            document.write('<th>');
        }
    }
    document.write('</table>');*/
    //操场人数
    /*for(i = 100;i < 200;i++){
        if(i % 3 == 1 && i % 4 == 2 && i % 5 == 3){
            document.write(i+' ');
        }
    }*/
    //买书
    /*var a,b,c;
    for(a = 0;a <= 100;a++){
        for(b = 0;b <= 100;b++){
            for(c = 0;c <= 100;c++){
                if(a + b + c == 100 && 10*a + 5*b + 0.5*c == 100){
                    document.write('教材:'+ a+'&nbsp'+'参考书:'+ b+'&nbsp'+'练习本:'+ c);
                }
            }
        }
    }*/
    //鸡兔同笼
    /*for(i = 0;i <= 34;i++){
        for(j = 0;j <= 34;j++){
            if(i + j == 34 && i*2 + j*4 == 96){
                document.write('鸡有:'+i+' '+'兔有:'+j);
            }
        }
    }*/


//数组
    //数组去空
    /*var arr = [1,2,'',,3,''];
    var brr = [];
    for(i = 0;i < arr.length;i++){
        if(arr[i] != undefined){
            brr[brr.length] = arr[i];
        }
    }
    console.log(brr);*/
    //数组最大值、最小值、平均值
    /*var arr = [1,2,3,4,5,6];
    var max = arr[0];
    for(i = 0;i < arr.length;i++){
    	if(max < arr[i]){
    		max = arr[i];
    	}
    }
    console.log(max);
    var arr = [1,2,3,4,5,6];
    var min = arr[0];
    for(i = 0;i < arr.length;i++){
    	if(min > arr[i]){
    		min = arr[i];
    	}
    }
    console.log(min);
    var arr = [1,2,3,4,5,6];
    var sum = 0;
    var ave;
    for(i = 0;i < arr.length;i++){
    	sum += arr[i];
    	ave = sum / arr.length;
    }
    console.log(sum);
    console.log(ave);*/
    //数组从大到小
    /*var arr = [1,34,6,51,68,941,64];
    for(i = 0;i < arr.length;i++){
    	for(j = i+1;j < arr.length;j++){
    		var num4;
    		if(arr[i] < arr[j]){
    			num4 = arr[i];
    			arr[i] = arr[j];
    			arr[j] = num4;
    		}
    	}
    }
    console.log(arr);*/
    //数组从小到大
    /*var arr = [1,34,6,51,68,941,64];
    for(i = 0;i < arr.length;i++){
    	for(j = i+1;j < arr.length;j++){
    		var num4;
    		if(arr[i] > arr[j]){
    			num4 = arr[i];
    			arr[i] = arr[j];
    			arr[j] = num4;
    		}
    	}
    }
    console.log(arr);*/
    //数组筛选数据类型
    /*var arr = ['',2,'ni',4,'啊哈'];
    var num = [];
    var str = [];
    for(i = 0;i < arr.length;i++){
        if(typeof arr[i] == 'number'){
            num[num.length] = arr[i];
        }
        else if(typeof arr[i] == 'string'){
            str[str.length] = arr[i];
        }
    }
    document.write("number类型的有："+num);
    document.write("<br>");
    document.write("string类型的有："+str);*/
    //数组中大于0的数
    /*var arr = [0,-4,5,-9,6,3,2];
    var num = [];
    for(i = 0;i < arr.length;i++){
        if(arr[i] > 0){
            num[num.length] = arr[i];
        }
    }
    document.write(num);*/
    //扩大2倍
    /*var arr = [1,2,3,4,5,6,7,8,9];
    for (var i = 0;i < arr.length;i++){
        arr[i] *= 2;
    }
    document.write(arr);*/
    //反向输出
    /*var arr = [1,2,3,4,5,6,7,8,9];
    var fan = [];
    for(i = arr.length-1;i >= 0;i--){
        fan[fan.length] = arr[i];
    }
    document.write(fan);*/
    //数组合并
    /*var arr = [1,2,3,4,5];
    var ara = [6,7,8,9];
    for(i = 0;i < ara.length;i++){
        arr[arr.length] = ara[i];
    }
    document.write(arr);*/
    
    //函数
    //封装四则运算
    /*function a(sum,sum2,sum1){
        switch(sum2){
            case '+':alert(`${sum}+${sum1}=${sum+sum1}`);
                break;
            case '-':alert(`${sum}-${sum1}=${sum-sum1}`);
                break;
            case '*':alert(`${sum}*${sum1}=${sum*sum1}`);
                break;
            case '/':alert(`${sum}/${sum1}=${sum/sum1}`);
                break;
        }
    }
    a(11,'*',10);*/
    //封装九九乘法表
    /*function a(num){
        for(var m = 1;m <= num;m++){
            for(var n = 1;n <= m ;n++){
                document.write(`${m}*${n}=${m*n}&nbsp`);
                if((m == 3||m == 4) && n == 2){
                    document.write(' ');
                }
            }
            document.write('<br>');
        }
    }
    a(9);*/
    //封装十乘十表格
    /*function a(num){
        var tab = '<table width="500px" height="500px" cellspacing="0">';
        for(var b = 0;b <num;b++){
            tab +='<tr>';
            for(var c =0;c <num;c++){
                if (b%2==0 && c%2==0) {
                    tab +='<th bgColor="white"></th>';
                }else if (b%2==1 && c%2==1) {
                    tab +='<th bgColor="white"></th>';
                }else if (b%2==1 && c%2==0) {
                    tab +='<th bgColor="black"></th>';
                }else{
                    tab +='<th bgColor="black"></th>';
                }
            }
            tab +='</tr>';
        }
        tab += '</table>';
        document.write(tab);
    }
    a(10);*/
    //封装金字塔
    /*function a(num){
        for(i = 1;i <= num;i++) {
            for(a = 1;a <= num-i;a++){
                document.write('&nbsp;');
            }
            for(q = 1;q <= i;q++){
                document.write('*&nbsp; ');
            }
            document.write('<br>');
        }
    }
    a(9);*/
    //封装数组去空
    /*function a(arr){
        xin=[];
        for(var i = 0;i < arr.length;i++){
            if(arr[i] != undefined){
                xin[xin.length] = arr[i];
            }
        }
        document.write(xin);
        console.log(xin[2]);
    }
    a(arr=[2,4,,7,,7,,9]);*/
    //封装数组求最大、最小、平均值
    /*function max(arr){
        var max = arr[0];
        for(i = 0;i<arr.length;i++){
            if(arr[i]>max){
                max=arr[i];
            }
        }
        document.write(max);
    }
    max(arr=[]);*/
    /*function min(arr){
        // var arr = [1,2,3,4,5,0];
        var min = arr[0];
        for(i = 0;i < arr.length;i++){
            if(arr[i] < min){
                min = arr[i]
            }
        }
        document.write(min);
    }
    min();*/
    /*function ave(arr){
        // var arr = [1,2,3,4,5];
        var sum = 0;
        var ave;
        for(i = 0;i < arr.length;i++){
            sum += arr[i];
            ave = sum/arr.length;
        }
        document.write(ave);
    }
    ave(arr=[]);*/
    //封装数组排序，从大到小，从小到大
    /*function a(arr){
        for(i = 0;i < arr.length;i++){
            for(j = i+1;j<arr.length;j++){
                var num4;
                if(arr[i] < arr[j]){
                    num4=arr[i];
                    arr[i]=arr[j];
                    arr[j]=num4;
                }
            }
        }
        document.write(arr);
    }
    a(arr=[]);*/
    /*function a(arr){
        // var arr = [8,45,32,41,688];
        for(i = 0;i < arr.length;i++){
            for(j = i+1;j<arr.length;j++){
                var num4;
                if(arr[i] > arr[j]){
                    num4=arr[i];
                    arr[i]=arr[j];
                    arr[j]=num4;
                }
            }
        }
        document.write(arr);
    }
    a(arr=[]);*/
    //封装数组筛选数据类型
    /*function a(arr){
//        var arr = ['',2,'ni',4,'啊哈'];
        var num = [];
        var str = [];
        for(i = 0;i < arr.length;i++){
            if(typeof arr[i] == 'number'){
                num[num.length] = arr[i];
                console.log(arr[i]);
            }
            else if(typeof arr[i] == 'string'){
                str[str.length] = arr[i];
            }
        }
        document.write("number类型的有："+num);
        document.write("<br>");
        document.write("string类型的有："+str)
    }
    a(arr=[]);*/
    //封装数组中大于0的数
    /*function a(arr){
        var num = [];
        for(i = 0;i < arr.length;i++){
            if(arr[i]>0){
                num[num.length]=arr[i];
            }
        }
        document.write(num);
    }
    a(arr=[3,98,-8,-5,4,-6,9]);*/
    //封装扩大2倍
    /*function a(arr){
        for(i = 0;i < arr.length;i++){
            arr[i] *= 2;
        }
        document.write(arr);
    }
    a(arr=[]);*/
    //封装反向输出数组中的各个元素
    /*function a(arr){
        var xin=[];
        for(i = arr.length-1;i>=0;i--){
            xin[xin.length] = arr[i];
        }
        document.write(xin);
    }
    a(arr=[]);*/
    //封装数组合并
    /*function aa(num1,num2){
        for (var i = 0; i < num1.length; i++) {
           num2[num2.length]=num1[i];
        }
        return num2;
    }
    console.log(aa([30,40,50,60,20],[10,9,20,30]));*/
    //将数组转换为字符串，默认用-链接
    /*function a(arr){
        var brr = '';
        for(i = 0;i < arr.length;i++){
            if(i == arr.length-1){
                brr += String(arr[i]);
            }else{
                brr += String(arr[i]) + '-';
            }
        }
        return brr;
     }
     document.write(a([1,2,'ni','hao']));*/
    //实现数组元素去重
    /*var num3= [10,5,8,11,10,8,5,8,5,10]; 
    function aa(num3){
        var num4 =[];
        for (var i = 0; i < num3.length; i++) {
            var aa=true;
            for (var j = i + 1; j < num3.length; j++) {
                if (num3[i] == num3[j]) {
                     aa=false;//如果数字相等就关掉这个数字
                }
            }
            if(aa == true){
                num4[num4.length] = num3[i];
            }
        }
        return num4;
    }
    console.log(aa([10,5,8,11,10,8,5,8,5,10]));*/
     // 数组查找，查找数组中是否包含a元素，包含则返回此元素的下标，不包含则返回-1
        /*function a(d){
            var e =3;
            for(var b = 0; b < d.length;b++){
                if(d[b] === e){
                    return b;
                }
            }
            if(d[b] !== e){
                return -1;
            }
         }
         console.log(a([2,3,'a',6]));*/
    // 找出数组中是否包含某个类型，包含返回true，不包含返回false
         /*function a(d){
            for(var b = 0; b < d.length;b++){
                if(isNaN(d[b])){
                    return true;
                }
            }
                return false;
         }
         console.log(a([6,,'k',6]));*/
</script>