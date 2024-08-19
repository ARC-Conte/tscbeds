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
            <br><br>
            <button onClick="buy('party time');">party time: 15</button>
        </div>
        <div id="ord">Order:</div>
        <span id="cost"></span>
        <script>
        var cost =0;
            function buy(type){
                if(type==='mounain man'){
                    document.getElementById("ord").innerHTML+="<br>mounain man price:15";
                    cost=cost+ 15;
                }else if(type==="clif hanger"){
                    document.getElementById("ord").innerHTML+="<br>clif hanger price:10";
                    cost=cost+ 10;
                }else if(type==='vortex'){
                    document.getElementById("ord").innerHTML+="<br>vortex price:12";
                    cost=cost+ 12;
                }else if(type==='party time'){
                    document.getElementById("ord").innerHTML+="<br>party time price:15";
                    cost=cost+ 15;
                }else
                document.getElementById("cost").innerHTML=cost;
            }
        </script>
    </body>
</html>

