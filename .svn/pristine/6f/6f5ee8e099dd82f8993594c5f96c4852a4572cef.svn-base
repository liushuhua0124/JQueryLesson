<%@ page language="java" contentType="text/html; charset=UTF-8"
	pageEncoding="UTF-8"%>
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
	<head>
		<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
		<title>Insert title here</title>
<script type="text/javascript">
		 function selectAll() {
            // 获取要操作的复选框
            var box1=document.getElementsByName("love");
            //checked判断是否选中
            for(var x=0;x<box1.length;x++)
            {
                var value1=box1[x];
                value1.checked=true;
            }
        }
        
        
         function selectOther() {
            // 获取要操作的复选框
            var box1=document.getElementsByName("love");
            //checked判断是否选中
            for(var x=0;x<box1.length;x++)
            {
                var value1=box1[x];
               if(value1.checked)
                   value1.checked=false;
               else
                   value1.checked=true;
            }
        }
        
         function SelectNO(){
            // 获取要操作的复选框
            var box2 = document.getElementsByName("love");
             //checked判断是否选中
           for (var x = 0; x < box2.length; x++) {
               var value1=box2[x];
               value1.checked=false;
            }
        }
</script>
	</head>
	<body>
		请选择爱好：
		<input type="checkbox" name="love"/>足球
	    <input type="checkbox" name="love"/>排球
	    <input type="checkbox" name="love"/>篮球
	    <input type="checkbox" name="love"/>羽毛球 <br/>
		 <input type="checkbox" name="allChecked" onclick="selectAll()"/>全选
		<input type="checkbox" name="llChecked" onclick="selectOther()"/>反选
		<input type="checkbox" name="Checked" onclick="SelectNO()"/>全不选
	</body>
</html>