<!DOCTYPE html>
<html>
	<head>
		<title> Fresh Fruits </title>
	</head>
	<body>
		<table >
			<colgroup>
				<col style="width: 300px" />
				<col style="width: 160px" />
			</colgroup>
			<thead>
				<tr>
					<th colspan="2">
						<em> Fresh fruit </em>
					</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>
						<div> It has long been known that a diet that includes at least a few servings of fresh fruit every day will help keep healty, fit and trim. </div>
					</td>
					<td>
						<img src="Fruits.jpg" width="160" height="100" />
					</td>
				</tr>
			</tbody>
		</table>
	</body>
</html>

<html>
	<head>
		<title> Letter Table </title>
	</head>
	<body>
		<table border="1" style="text-align: center">
			<colgroup>
				<col style="width: 30px" />
				<col style="width: 30px" />
				<col style="width: 30px" />
				<col style="width: 30px" />
				<col style="width: 30px" />
			</colgroup>
			<tr>
				<td colspan="3">Title goes here</td>
				<td>A</td>
				<td style="text-align: right">B</td>
			</tr>
			<tr>
				<td rowspan="3">C</td>
				<td>D</td>
				<td>E</td>
				<td>F</td>
				<td style="text-align: right">G</td>
			</tr>
			<tr>
				<td>H</td>
				<td colspan="2">I</td>
				<td rowspan="2" style="text-align: right; vertical-align: bottom">J</td>
			</tr>
			<tr>
				<td>K</td>
				<td>L</td>
				<td>M</td>
			</tr>
			<tr>
				<td style="text-align: right">N</td>
				<td colspan="4">O</td>
			</tr>
		</table>
	</body>
</html>
<!DOCTYPE html>
<html>
	<head>
		<title> Submit Member </title>
	</head>
	<body>
		<form method="post">
			<div>
				<label for="member">Member name: </label>
				<input type="text" id="member" required="required"/>
				<strong>*req</strong>
			</div>
			<div>
				<label for="email">Email: </label>
				<input type="text" id="email" required="required"/>
				<strong>*req</strong>
			</div>
			<div>
				<label for="school">School: </label>
				<input type="text" id="school" required="required"/>
				<strong>*req</strong>
			</div>
			<input type="submit" value="Submit"/>
		</form>
	</body>
</html>
<!DOCTYPE html>
<html>
	<head>
		<title> Calculator </title>
		<style>
			input[type="button"]
			{
				width: 30px;
				height: 30px;
				border: 0px;
				background-color: transparent;
				color: #338AFA; 
			}
			td
			{
				border: 1px solid #338AFA;
			}
		</style>​
	</head>

	<body>
		<form method="post">
			<table style="border-collapse: collapse">
				<tr>
					<td colspan="4">
						<input type="text" size="15" value="123" style="border: 0px; text-align: right; color: #338AFA">
					</td>
				</tr>
				<tr>
					<td> <input type="button" value="1"> </td>
					<td> <input type="button" value="2"> </td>
					<td> <input type="button" value="3"> </td>
					<td> <input type="button" value="+"> </td>
				</tr>
				<tr>
					<td> <input type="button" value="4"> </td>
					<td> <input type="button" value="5"> </td>
					<td> <input type="button" value="6"> </td>
					<td> <input type="button" value="-"> </td>
				</tr>
				<tr>
					<td> <input type="button" value="7"> </td>
					<td> <input type="button" value="8"> </td>
					<td> <input type="button" value="9"> </td>
					<td> <input type="button" value="*"> </td>
				</tr>
				<tr>
					<td colspan="2"> <input type="button" value="0" style="width: 62px"> </td>
					<td> <input type="button" value="."> </td>
					<td> <input type="button" value="/"> </td>
				</tr>
			</table>
		</form>
	</body>
</html>
