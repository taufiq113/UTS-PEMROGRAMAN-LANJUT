<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabel Ganjil Genap</title>
    <style>
        table {
            border-collapse: collapse;
            width: 50%;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>

    <table>
        <tr>
            <th>Ganjil</th>
            <th>Genap</th>
        </tr>

        <?php
        $max = 6;

       for ($i = 1; $i < $max; $i++) {
        echo "<tr>";
        if ($i %2== 0) {
            echo "<td></td>";
            echo"<td>$i</td>";
       } 
      
       else {
        echo "<td>$i</td>";
       }
       echo "</tr>";
      
    }
  
        ?>
    </table>

</body>
</html>
