# flex
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>flexbox</title>
    <style>
        .con{
            border: 2px solid red;
            width: 100%;
            height: 500px;
            /* to initialize a flex container we to diplay:flex in its parent  */
            display: flex;
            /* properties of flex */
            /* flex-direction: row;no change because default flex direction is row */
            /* flex-direction: column; */
            /* flex-direction: column-reverse; */
            /* flex-direction: row-reverse; */
            /* flex-wrap: wrap; */
            /* flex-wrap: wrap-reverse; */
            /* flex-flow is used to give two prperties direc an wrap in single line */
           /* flex-flow:row-reverse wrap ; */
            /* justify-content: center;to make entire content cenre */
            /* justify-content: space-between;to make particular space b/w two boxes */
            /* justify-content: space-around;to make space around box */
            /* justify-content: space-evenly; */
            /* align-items: baseline; */
            align-items: flex-start;
            align-items:center;
            /* align-items: flex-end;align at end */
            /* align-items: stretch; */
        }
        #box-1{
            order:40;
            /* flex-grow: 3; */
            flex-basis: 320px;
            /* when flex direction is set to row flex-basis increase width */
            /* * when flex direction is set to columns flex-basis increase height: ; */ */



        }
        #box-2{
            /* flex-shrink: 2; */
            flex:2 2 230px;
        }
        #box-3{
            align-self: flex-start;
            align-self: flex-end;
            align-self: center;
        }

        .box{
            border: 2px solid black;
            /* margin: 2px auto; */
            width: 100px;
            height: 100px;
            background-color: tomato;
            margin: 10px;
            padding: 3px;
        }
    </style>
   
</head>
<body>
    <div class="con">
    <div class="box" id="box-1">box 1</div>
    <div class="box" id="box-2">box 2</div>
    <div class="box" id="box-3">box 3</div>
    <div class="box" id="box-4">box 4</div>
    <div class="box" id="box-5">box 5</div>
    <div class="box" id="box-6">box 6</div>   
</div>
</body>
</html>
