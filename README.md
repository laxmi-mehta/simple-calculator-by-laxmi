
!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator(By Laxmi)</title>
</head>
<body>
    <h1>Calculator</h1>
        <form name="calculator" class="Calculator">
            <table id="tableId">
                <tr>
                    <td colspan="3">
                        <input type="text" name="display" id="display">
                    </td>
                    <td>
                        <input type="button" value="AC" id="allClear" onclick="calculator.display.value = ''">
                    </td>
                </tr>
                <tr>
                    <td>
                        <input type="button" value="1" onclick="calculator.display.value += '1'">
                    </td>
                    <td>
                        <input type="button" value="2" onclick="calculator.display.value += '2'">
                    </td>
                    <td>
                        <input type="button" value="3" onclick="calculator.display.value += '3'">
                    </td>
                    <td>
                        <input type="button" value="+" onclick="calculator.display.value += '+'">
                    </td>
                </tr>
                <tr>
                    <td>
                        <input type="button" value="4" onclick="calculator.display.value += '4'">
                    </td>
                    <td>
                        <input type="button" value="5" onclick="calculator.display.value += '5'">
                    </td>
                    <td>
                        <input type="button" value="6" onclick="calculator.display.value += '6'">
                    </td>
                    <td>
                        <input type="button" value="-" onclick="calculator.display.value += '-'">
                    </td>
                </tr>
                <tr>
                    <td>
                        <input type="button" value="7" onclick="calculator.display.value += '7'">
                    </td>
                    <td>
                        <input type="button" value="8" onclick="calculator.display.value += '8'">
                    </td>
                    <td>
                        <input type="button" value="9" onclick="calculator.display.value += '9'">
                    </td>
                    <td>
                        <input type="button" value="*" onclick="calculator.display.value += '*'">
                    </td>
                </tr>
                <tr>
                    <td>
                        <input type="button" value="." onclick="calculator.display.value += '.'">
                    </td>
                    <td>
                        <input type="button" value="0" onclick="calculator.display.value += '0'">
                    </td>
                    <td>
                        <input type="button" value="/" onclick="calculator.display.value += '/'">
                    </td>
                    <td>
                        <input type="button" value="=" onclick="calculator.display.value = eval(calculator.display.value)">
                    </td>
                </tr>
            </table>
        </form>

        <span><b>&copy; Copyright 2022-2023 All Rights Reserved. Developed By Laxmi mehta</b></span>
</body>

</html>
