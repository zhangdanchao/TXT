1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:
        var h1 = document.getElementById('h1');
        var a = '11';
        var b = '22';
        var b = a.concat(b);
        h1.innerHTML = (b);

2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:
        var h2 = document.getElementById('h3');
        var a = prompt('请输入存款金额');
        var b = 870000;
        var c =h3.innerHTML = ('870000');
        if(a.value == '87w'){
            console.log(c);
        }
3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答:
        var h1 = document.getElementById('h1');
        var a = '79387.348';
        var b = a.substr(0,8);
        h1.innerHTML = (b);

4.一张图片是一个相对路径img/head/,icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:
          var h4 = document.getElementById('h4');
          var a = 'img/head/icon/1.jpg';
          var b = a.substring(0,13);
          h4.innerHTML = b;
5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h1的元素中,显示在页面id为h4的元素中
答:
      var b = document.getElementById('ipt');
      var a = document.getElementById('btn');
        var h = document.getElementById('h1');
        a.onclick = function(){
        var v = b.value;
        console.log(v.toLowerCase());
        if(v=='iabe'){
        h.innerHTML = '输入正确'
        }
    }