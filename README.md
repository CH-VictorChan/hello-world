# hello-world
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title></title>
    <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
    <style>
    .right {
        width: 300px;
        height: 120px;
    }
    .right div {
        width: 100px;
        height: 90px;
        padding: 5px;
        margin: 5px;
        float: left;
        border: 1px solid #ccc;
    }
    .right div {
        background: yellow;
    }
    </style>
</head>
<body>
    <h2>动态创建元素节点</h2>
    <button>点击通过jQuery动态创建元素节点</button>
    <script type="text/javascript">
    $('button').on('click', function() {
        var div = $("<div class='right'><div class='aaron'>动态创建DIV元素节点</div></div>");
        $('body').append(div);
    })
    </script>
</body>
</html>
