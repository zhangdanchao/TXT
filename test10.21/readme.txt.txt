1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:
        var h1 = document.getElementById('h1');
        var a = '11';
        var b = '22';
        var b = a.concat(b);
        h1.innerHTML = (b);

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:
        var h2 = document.getElementById('h3');
        var a = prompt('����������');
        var b = 870000;
        var c =h3.innerHTML = ('870000');
        if(a.value == '87w'){
            console.log(c);
        }
3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��:
        var h1 = document.getElementById('h1');
        var a = '79387.348';
        var b = a.substr(0,8);
        h1.innerHTML = (b);

4.һ��ͼƬ��һ�����·��img/head/,icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:
          var h4 = document.getElementById('h4');
          var a = 'img/head/icon/1.jpg';
          var b = a.substring(0,13);
          h4.innerHTML = b;
5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh1��Ԫ����,��ʾ��ҳ��idΪh4��Ԫ����
��:
      var b = document.getElementById('ipt');
      var a = document.getElementById('btn');
        var h = document.getElementById('h1');
        a.onclick = function(){
        var v = b.value;
        console.log(v.toLowerCase());
        if(v=='iabe'){
        h.innerHTML = '������ȷ'
        }
    }