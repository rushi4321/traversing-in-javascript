<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Traversing Array</title>
    <script>
        let data=[4,45,5,3,234,6,76,];
        //for(let i=0;i<data.length;i++){
           // document.write(`Array ${i} is ${data[i]}<br>`);
        //}
        // let x=3;
        // document.write(data[4]);
        function getElement()
        {
            let el=document.getElementById('element').value
            alert(data[el]);
        }
    </script>
</head>
<body>
    <h1>hello</h1>
    <input type="text" id="element">
    <button onclick="getElement()">Get Element</button>
</body>
</html>
