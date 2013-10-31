google-code-prettify
====================

google-code-prettify代码高亮工具 采用 http://www.bootcss.com/ 的颜色样式
源码
====================

*  https://code.google.com/p/google-code-prettify/
    
引入css
 
    <link href="prettify.css" type="text/css" rel="stylesheet" />
引入js

    <script type="text/javascript" src="jquery.js"></script>
    <script type="text/javascript" src="prettify.js"></script>
初始化

    <script type="text/javascript">
         $("pre").addClass("prettyprint");
            prettyPrint();
    </script>
    
添加代码
     &lt;pre>
        var name = 'neo';
        cosole.log("hello" + name);
     &lt;/pre>
