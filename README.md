<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>表单综合实例</title>
	</head>
	<body bgcolor="eddd70">
		<form action="1123025874@qq.com" method="post" enctype="text/plain">
			<fieldset >
				<legend><font face="幼圆" size="4" color=#802781>[用户注册]</font></legend>
				<table border="0" >
					<tr>
						<td>用户名：
							<td colspan="4" valign="middle"><input type="text" name="name" value="" size="12" maxlength="18">
					<tr>
						<td>密码：
							<td colspan="4"><input type="password" name="pass" size="12" maxlength="8" value="">
					<tr>
						<td>请再次输入密码:
							<td colspan="4"><input type="password" name="pass1" size="12" maxlength="8" value="">
	
	
					<tr><td>性别：
						<td colspan="4"><input type="radio" name="sex" value="1" checked>女
						<input type="radio" name="sex" value="2" >男
					<tr><td>证件：<td colspan="4"><select name="xueli" size="1">
						<option value="a">学生证</option>
						<option value="b">身份证</option>
						<option value="c">军官证</option>
						<option value="d">工作证</option>
					</select>
					<tr><td>证件号码：
						<td colspan="4"><input type="text" name="num" value="" size="12" maxlength="15">
					<tr><td>个人简介：
						<td colspan="4"><textarea name="note" rows="4" cols="64" accesskey="r">在此输入个人主要经历</textarea>
					<tr><td>头像：
						<td colspan="4"><input type="file" name="wenjian"  size="14" >
				    <tr><td>兴趣爱好：
				    	<td ><input type="checkbox" name="hh"  value="it" >旅游
				    	<td ><input type="checkbox" name="hh"  value="xx" >购物
				    	<td ><input type="checkbox" name="hh"  value="fw" >运动
				    	<td ><input type="checkbox" name="hh"  value="jy" >音乐
				    	</td></tr>
				    	<tr><td align="left" valign="middle">
				    		<input type="submit" name="send"  value="提交">
				    		<input type="reset" name="clear"  value="重填" >
				    		</td></tr>
				</table>
				
				
			</fieldset>
			
		</form>
		
		
	</body>
</html>
