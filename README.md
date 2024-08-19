<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Non working chat</title>
        <style>
            #chat{
                height: 314px;
                overflow: auto;
                text-align:center;
            }
        </style>
    </head>
    <body>
        <div id="chat"></div>
        text:<textarea id="text"></textarea>
        <br>password:<input id="pass">
        <button onClick="send()">send</button>
        <script>
            var pass = document.getElementById("pass");
            
            
            function send() {
                var passv = document.getElementById("pass").value;
                
                if(document.getElementById("pass").value="050408"){
                    var name="<br><span style='font-size: 20px;'>ARCoder: </span>";
                }
                document.getElementById("chat").innerHTML+=name+document.getElementById("text").value;
            }
        </script>
        

    </body>
</html>
