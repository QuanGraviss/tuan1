<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <script>
        console.log("Challenge #1 ; Challenge #2");
        console.log("data1");

        function markHigherBMI1() {
            var weightsM = 78,
                heightsM = 1.69;
            var weightsJ = 92,
                heightsJ = 1.95;
            BMIM = weightsM / (heightsM * heightsM);
            BMIJ = weightsJ / (weightsJ * weightsJ);
            if (BMIM > BMIJ) {
                console.log("Mark's BMI(" + BMIM + ")is higher than john's(" + BMIJ + ")")
            } else
                console.log("john's BMI(" + BMIJ + ")is higher than mark's(" + BMIM + ")");

        }
        markHigherBMI1();

        console.log("data2");

        function markHigherBMI2() {
            var weightsM = 95,
                heightsM = 1.88;
            var weightsJ = 85,
                heightsJ = 1.76;
            BMIM = weightsM / (heightsM * heightsM);
            BMIJ = weightsJ / (weightsJ * weightsJ);
            if (BMIM > BMIJ) {
                console.log("Mark's BMI(" + BMIM + ")is higher than john's(" + BMIJ + ")")
            } else
                console.log("john's BMI(" + BMIJ + ")is higher than mark's(" + BMIM + ")");
        }
        markHigherBMI2();

        console.log(" Challenge #3");

        var Dolphins = [96, 108, 89];
        sum = 0;
        for (var a of Dolphins) {
            sum += a;
        }
        var DolAVG = sum / Dolphins.length;
        var Koalas = [88, 91, 110];
        sum = 0;
        for (var a of Koalas) {
            sum += a;
        }
        var KoaAVG = sum / Koalas.length;
        console.log("data1");

        function checkwinner(a, b) {
            if (a > b && a >= 100) {
                console.log("Dolphins thang Koalas");
            } else if (a < b) {
                console.log("Dolphins thua Koalas");
            } else {
                console.log("Dolphins hoa Koalas");
            }
        }
        checkwinner(DolAVG, KoaAVG);

        console.log("Data Bonus 1");

        var Dolphins1 = [97, 112, 101];
        sum = 0;
        for (var a of Dolphins1) {
            sum += a;
        }
        var DolAVG1 = sum / Dolphins1.length;
        var Koalas1 = [109, 95, 123];
        sum = 0;
        for (var a of Koalas1) {
            sum += a;
        }
        var KoaAVG1 = sum / Koalas1.length;

        function checkwinner(a, b) {
            if (a > b && a >= 100) {
                console.log("Dolphins thang Koalas");
            } else if (a < b && b >= 100) {
                console.log("Dolphins thua Koalas");
            } else {
                console.log("Dolphins hoa Koalas");
            }
        }
        checkwinner(DolAVG1, KoaAVG1);

        console.log("Data Bonus 2");
        var Dolphins2 = [97, 112, 101];
        sum = 0;
        for (var a of Dolphins2) {
            sum += a;
        }
        var DolAVG2 = sum / Dolphins.length;
        var Koalas2 = [109, 95, 106];
        sum = 0;
        for (var a of Koalas2) {
            sum += a;
        }
        var KoaAVG2 = sum / Koalas2.length;
        console.log("data1");

        function checkwinner2(a, b) {
            if (a > b && a >= 100) {
                console.log("Dolphins thang Koalas");
            } else if (a < b && b >= 100) {
                console.log("Koalas thang Dolphins");
            } else if (a == b && a >= 100 && b >= 100) {
                console.log("Dolphins hoa Koalas");
            }
        }
        checkwinner2(DolAVG2, KoaAVG2);

        console.log("Challenge #4");
        console.log("data1");
        var biu = 275.45;
        var tip = (biu >= 50 && biu <= 300) ? tip = biu * 15 / 100 : tip = biu * 20 / 100;
        var biut = biu + tip;
        console.log("hóa đơn là " + biu + ", tiền boa là " + tip + "và tổng giá trị là " + biut);
        var biu = 430;
        var tip = (biu >= 50 && biu <= 300) ? tip = biu * 15 / 100 : tip = biu * 20 / 100;
        var biut = biu + tip;
        console.log("hóa đơn là " + biu + ", tiền boa là " + tip + "và tổng giá trị là " + biut);

        console.log("Challenge #5");
        console.log("Data1");
        var Dolphins = [44, 23, 71];
        var Koalas = [65, 54, 49];

        function dolpAverage(arr) {
            return arr.reduce((a, initvalie) =>
                a + initvalie, 0) / arr.length;
        }
        //console.log(dolpAverage(Dolphins));

        function koaAverage(arr) {
            return arr.reduce((a, initvalie) =>
                a + initvalie, 0) / arr.length;
        }
        //console.log(koaAverage(Koalas));

        function checkWinner(a, b) {
            var kq = (a > b && a / b >= 2) ?
                console.log("Dolhins thắng(" + a + "," + b + ")") : (a === b) ?
                console.log("draw") : console.log("Koalas thắng(" + a + "," + b + ")");
        }
        checkWinner(dolpAverage(Dolphins), koaAverage(Koalas));
        console.log("Data2");
        var Dolphins = [85, 54, 41];
        var Koalas = [23, 34, 27];

        checkWinner(dolpAverage(Dolphins), koaAverage(Koalas));

        console.log("Challenge #6");
        console.log("Data1");
        var biu = [125, 555, 44];

        function calcTip(arr) {
            var ss = arr.map(function(number) {
                return number >= 50 && number <= 300;
            })
            if (calcTip(biu) == true) {

            }
        }
    </script>
</body>

</html>
