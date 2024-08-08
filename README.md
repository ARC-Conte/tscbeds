        title:<br><input id="h1" type="text"><br>
        price:<br><input id="sub1" type="text"><br>
        dicribers:<br><input id="sub2" type="text"><br>
        about:<br><textarea id="p" rows="4"></textarea>
        <button onClick="end()">end</button>
        <br>prodoct:<br><div id="pro"></div>
        <script>            
            var end = function(){                
                document.getElementById("pro").textContent+="<h1>"+document.getElementById("h1").value+"</h1>"+"<h2>"+document.getElementById("sub1").value+"</h2>"+"<h2>"+document.getElementById("sub2").value+"</h2>"+""+"<p>"+document.getElementById("p").value+"</p>";
            };
        </script>
