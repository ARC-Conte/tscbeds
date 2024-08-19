<html>
    <head>
        <meta charset="utf-8">
        <title>New webpage</title>
    </head>
    <body>
        <div style="overflow:auto; height: 100px;">
            <button onClick="buy('mounain man');">mounain man: 15</button>
            <button onClick="buy('clif hanger');">clif hanger: 10</button>
            <button onClick="buy('vortex');">vortex: 12</button>
            <button onClick="buy('plain');">vortex: 10</button>
            <br><br>
            <button onClick="buy('party time');">party time: 15</button>
        </div>
        <div id="ord">Order:</div>
        <span id="price"></span>
        <script>    
            var price =0;    
            function buy(type){                
                if(type==='mounain man'){
                    document.getElementById("ord").innerHTML+="<br>mounain man price: 15";
                    price=price+ 15;
                    document.getElementById("price").innerHTML=price;
                }else if(type==="clif hanger"){
                    document.getElementById("ord").innerHTML+="<br>clif hanger price: 10";
                    price=price+ 10;
                    document.getElementById("price").innerHTML=price;
                }else if(type==='vortex'){
                    document.getElementById("ord").innerHTML+="<br>vortex price: 12";
                    price=price+ 12;
                    document.getElementById("price").innerHTML=price;
                }else if(type==='party time'){
                    document.getElementById("ord").innerHTML+="<br>party time price: 15";
                    price=price+ 15;
                    document.getElementById("price").innerHTML=price;
                }else if(type==='plain'){
                    document.getElementById("ord").innerHTML+="<br>party time price: 10";
                    price=price+ 10;
                    document.getElementById("price").innerHTML=price;
                }         
            }
        </script>
    </body>
</html>

