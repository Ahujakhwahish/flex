<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>flex</title>
    <style>
        .cont
        {
            display:flex;
            border:1px solid black;
            /* flex-direction :column-reverse; */
             /* flex-wrap:wrap-reverse;
             justify-content:start; */
             align-items:stretch;


        }
        .box{
            height:100px;
            width:100px;
        }
        .box1 {
            background-color:red;

        }
        .box2{
            background-color:pink;
        }
        .box3{
            background-color:green;
        }
    </style>
</head>
<body>
    <!--flex  -->
    <div class ="cont">
       <div class ="box box1">box1 </div>
       <div class ="box box2">box2</div>
       <div class ="box box3">box3</div>
    </div>
</body>
</html>
