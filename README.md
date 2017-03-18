# jsDemo
JS练习提高记录20170318
<script type="text/javascript">
	var arr=[
				[10,'zhangsn','male','9999999','shandong'],
				[11,'lisi','male'],
				[12,'wangwu','female']
	];
	document.write('<table border="2">');//引号嵌套，内层单引号，外层就需要双引号；外层单引号，同理，内层需要双引号
	for(var i=0;i<arr.length;i++){
		document.write('<tr>');
		for(var j in arr[i]){
			document.write('<td align="center">');
			document.write(arr[i][j]);
			document.write('</td>');

		}
		document.write('</tr>');
	}
	document.write('</table>');
	document.write('<hr color="red" size="22">');
	document.write("<table border='3'>");//引号嵌套，内层单引号，外层就需要双引号；外层单引号，同理，内层需要双引号
	for(var i=0;i<arr.length;i++){
		document.write('<tr>');
		for(var j in arr[i]){
			document.write('<td align="center">');
			document.write(arr[i][j]);
			document.write('</td>');

		}
		document.write('</tr>');
	}
	document.write('</table>');

</script>
