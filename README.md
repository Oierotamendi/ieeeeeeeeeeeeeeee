# Proba
 Proba
<html>

<head>
    <script language="JavaScript">
 
    var totalTiempo=15;
    var html="denboraz_kanpo.html";
 
    function updateReloj()
    {
        document.getElementById('CuentaAtras').innerHTML = "Geratzen zaizun denbora "+totalTiempo+" segundu";
 
        if(totalTiempo==0)
        {
            window.location=html;
        }else{
            totalTiempo-=1;
            setTimeout("updateReloj()",1000);
        }
    }
 
    window.onload=updateReloj;
 
    </script>
<title>Bilakatu milionario</title>
    <link href="logotipo-qqsm.png" rel="shortcut icon"/>

    <link rel="stylesheet" href="galderak.css">
</head>

<body>
    

    
    <center><p><font size="5" color="BLACK" face="Georgia">Galdera 10</font></p> </center>
       
        <img src="kent%20brockman.png" align=left style="width:400px;">
   
    <div id="argazkiak" style="position: absolute; top: 50px;right: 640px">    
    
        <img src="logotipo-qqsm.png" align=center style="width:250px; height:200 px">
        
    </div>
    
    <div id="dirua">
                    <h2 align="right">Irabazitako dirua: 750.000€</h2>
                    
        </div>

    <br><br><br>
    <div id="main-container">
        
        <center><p><font size="5" color="BLACK" face="Arial">Zenbat talde korporatibok osatzen dute Mondragon kooperatiba?</font></p></center>
    
        <table>

            <tr>
                <td><a href="Akatsa.html">10</a></td>
                <td><a href="akatsa.html">53</a></td>
            </tr>
            <tr>
                <td><a href="azkeneko%20orria.html">103</a></td>
                <td><a href="akatsa.html">156</a></td>
             
        </table>
    </div>

    
<h2 id='CuentaAtras'></h2>
    

</body>

</html>
