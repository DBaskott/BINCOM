
Func = open("Index.html","w")

Func.write("

<html>
<head>
<title>Bincom Trainee Developer</title>
<body style ="text-align:center;">
<h1>
Interview Task
</h1>
<h2>
Write a valid HTML + Python Page that will count numbers from 1 to 1,000,000?
i.   Display every 10th number in the series in Bold
ii.  Display every 3rd number in the series in Italics
iii. Bonus: Underline every Prime number in this series.
</h2>
<?php
    if(isset($_POST['calculate'])){
        $num = 1000000;
        $count =0;
        for ($i=0; $i<$num; $i++)
        {
        if (($num%$i)==0)
        {
        $count++;
        }
        }
        if ($count<3)
        {
            if ($i % 3 == 1) 
            {
            echo "<u><i>" . '$i' . "</u></i>";
            }
            if ($i % 10 == 1)
            {
            echo "<u><b>" . '$i' . "</u></b>";
            }
            if ($i %3 == 1 and $i % 10 == 1)
            {
            echo "<u><i><b>" . '$i' . "</u></i></b>";
            }
        }
        else
        {
            if ($i % 3 == 1) 
            {
            echo "<i>" . '$i' . "</i>";
            }
            if ($i % 10 == 1)
            {
            echo "<b>" . '$i' . "</b>";
            }
            if ($i %3 == 1 and $i % 10 == 1)
            {
            echo "<i><b>" . '$i' . "</i></b>";
            }
        }


    }
?>
<form method="post">
    <input type="submit" name ="calculate" value = "calculate"/>
</form>
</body>
</head>
</html>
func.close()

            
