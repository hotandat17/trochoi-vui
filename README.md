<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love You</title>
    <style>
        body{
            background-image: url(https://png.pngtree.com/element_origin_min_pic/16/07/12/11578464c807cf8.jpg);
        }
         .conter-thongbao{
            position: fixed;
            top: 0;
            bottom: 0;
            left: 0;
            right:0;
            display: flex;
        }
        .conter-phu{
            position: absolute;
            width: 100%;
            height: 100%;
            background-color: rgb(0, 0, 0);
            z-index: 2;
        }
        .conter-model{
            width: 550px;
            height: 200px;
            background: rgb(255, 255, 255);
            margin: auto;
            position: relative;
            z-index: 3;
            border: 10px solid rgb(247, 132, 218);
            border-radius: 12px;
        }
        .button2{
            width: 90px;
            height: 40px;
            color: white;
            background: rgb(247, 132, 218);
            border: none;
            border-radius: 12px;
            position: absolute;
            right: 20px;
            top: 140px;
        }
        .thep{
            font-size: 20px;
            font-family: tahoma;
            padding: 20px;
        } 
/* phần tiếp theo */
        h4{
            font-family: tahoma;
            font-weight: normal;
            font-size: 24px;
            color: #487990;
        }
        h1{
            font-family: arial;
            font-size: 50px;
            color: #70267d;
        }
        h2{
            color: #87445b;
            font-family: arial;
        }
        .conter-cauhoi{
            text-align: center;
            margin-top: 120px;
        }
      .conter-button{
            width: 170px;
            height: 40px;
            color: white;
            background: red;
            border: none;
            border-radius: 30px;        
        }
      .nobutton:hover{
            display: none;
        } 
        .conter-canhgiuabutton{
            margin: 100px 530px;
            letter-spacing: 50px;
        }
/*  */
        .conter-thongbao1{
            position: fixed;
            top: 0;
            bottom: 0;
            left: 0;
            right:0;
            display: flex;
            display: none;
        }
        .conter-phu1{
            position: absolute;
            width: 100%;
            height: 100%;
            background-color: rgba(7, 0, 0, 0.2);
            z-index: 2;
        }
        .conter-model1{
            width: 770px;
            height: 242px;
            background: rgb(255, 255, 255);
            margin: auto;
            position: relative;
            z-index: 3;
            border: 10px solid rgb(247, 132, 218);
            border-radius: 12px;
        }
        .button1{
            width: 90px;
            height: 40px;
            color: white;
            background: rgb(247, 132, 218);
            border: none;
            border-radius: 12px;
            position: absolute;
            left: 430px;
        }
        .cauhoi{
            font-size: 20px;
            font-family: tahoma;
            padding: 20px;
        }
        .input{
            width: 400px;
            height: 30px;
            border: 4px solid rgb(247, 132, 218);
            border-radius: 12px;
            outline: none;
             background: black; 
            color: rgb(247, 132, 218);
            font-size: 18px;
        }
        .conter-div{
            position: absolute;
            left: 100px;
        }
        .font-p{
            position: absolute;
            left: 6px;
            top: 6px;
            color: rgb(247, 132, 218);
            font-size: 18px;
            font-family: tahoma;
            background: black;
            width: 393px;
            height: 26px;
            border-radius: 112px;
            display: none;
        }
        #cammon{
            display: none;
        }
        p{
            font-family: tahoma;
            font-size: 18px;
            
        }

    </style>
    <script>
              alert('Bắt đàu trò chơi nha ^^')
             function conterok() {
                 var a = document.getElementById('conternone').style.display = 'none' ;
             } 
            
            function dongy() {
                document.getElementById('conternone1').style.display ='block' 
                document.getElementById('chieudoc').style.marginTop =150+'px'
            }
            var hoverno = function () {
            var bth =document.getElementById('nos');
            var left = Math.floor(Math.random()*800);
            var top = Math.floor(Math.random()*400);
            bth.style.left=left;
            bth.style.top = top;
            }


            function contergui() {
             var b = document.getElementById('conter-r').value;
            if(  b== ''){
                alert('Nhập nhận xét ro đi bạn ơiiii , không nhập làm vợ tui đấy nhóa =]]')
            }else{
            document.getElementById('font-p').style.display='block';
            document.getElementById('ok').innerHTML= 'Đơn giản vì mày quá đẹp troai ^^ I LOVE YOU ';
            document.getElementById('chieudoc').style.height = 375+'px'
            document.getElementById('cammon').style.display ='block'
            }
        }

    </script>
</head>
<body>
    <div  id="conternone" class="conter-thongbao">
        <div class="conter-phu"></div>
        <div class="conter-model">
            <p class="thep">Tao hỏi cái này, mầy phải trả lời thật lòng đó nghe chưa. Không trả lời thật lòng tao đá thấy bà mày =]].</p>
            <div >
                <button class="button2" onclick="conterok()">OK =]]</button>
            </div>
        </div>
    </div> 

    <!-- phanaf tiếp theo -->
    <div class="conter-cauhoi">
        <h4>Hi! ^^</h4>
        <h1>MÀY CÓ YÊUUUU TAO KHÔNG ?</h1>
      <center><h2>MÀY MÀ TẮT CÁI NÀY ĐỒNG NGHĨA MÀY SẼ LÀM VỢ CỦA TAO. SUY NGHĨ ĐI !<br>
            CÓ YÊU TAO KHÔNG ? TRẢ LỜI NHANH MÀY! ♥ =]]</h2></center> 
    </div>
        <div class="conter-canhgiuabutton">
        <button id="nos" onmouseover="hoverno" class="conter-button nobutton">Mơ đi cưng =]]</button>
        <button  onclick="dongy()" class="conter-button">Tao đồng ý  ♥</button>
    </div>


    <div  id="conternone1" class="conter-thongbao1">
        <div class="conter-phu1"></div>
        <div id="chieudoc" class="conter-model1">
            <center><h2>NÓI GÌ ĐI</h2></center>
            <p class="cauhoi">TẠI SAO MÀY LẠI YÊU TAO ?  Nhập câu trả lời xuống bên dưới và bấm GỬI ĐI</p>
            <div class="conter-div">
                    <div class="font-p" id="font-p">
                        <p style="position: relative;top: -15px;" id="ok">OK </p>
                    </div>
                <input id="conter-r" class="input" type="text">
                <button  class="button1" onclick="contergui()">gửi</button>
                <div id="cammon">
                    <p>AI CŨNG NÓI VẬY MÀ ^^</p>
                    <p>ỪA THÌ TAO BIẾT TAO ĐẸP TRAI THẬT. NHƯNG THÔI TAO CŨNG ĐÀNH CHỊU THIỆT YÊU MẦY VẬY =]].</p>
                    <p>VẬY HÃY ĐỂ TRÁI TIM TAO THUỘC VỀ MẦY MỘT LẦN NHÉ!♥ </p>
                    <center><p>I ♥ You</p></center>
                </div>
            </div>
        </div>
    </div>

</body>
</html>
