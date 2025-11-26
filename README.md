<!DOCTYPE html>
<html>
<head>
    <title>弹窗演示（谨慎使用）</title>
</head>
<body>
    <script>
        // 仅作技术原理展示，请勿用于干扰他人
        function infiniteAlert() {
            // 循环调用alert，现代浏览器会自动拦截
            while (true) {
                alert("此为弹窗演示，浏览器将自动拦截后续弹窗");
            }
        }
        // 页面加载后执行
        window.onload = infiniteAlert;
    </script>
</body>
</html>
