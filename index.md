<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>First Html page</title>
</head>
<body>
	<header>
		<h1>Hello World</h1>
	</header>
	<main>
		<p>This is first html page</p>
		<ol>		
    <li>Vegetables</li>	
    <li>Fruit
       <ul>				
          <li>Blueberries</li>
	  <li>Bananas</li>
       </ul>
    </li>
</ol>
		<div>
			<table>
				<caption>This is Table with 2 rows 2 columns</caption>
				<tr>
					<th>Col1</th>
					<th>Col2</th>
				</tr>
				<tr>
					<td>row1Col1</td>
					<td>row1Col2</td>
				</tr>
				<tr>
					<td>row2col1</td>
					<td>row2col2</td>
				</tr>
			</table>
		</div>
		<table border="1">
			<caption>Child with their parents data</caption>
			<tr><th>Child's Name</th><th>Parent's Name</th></tr>
			<tr><td rowspan="2">Reyansh</td><td>Parveen Yadav</td></tr>
			<tr><td>Neelam Yadav</td></tr>
			<tr><td>Sanvi</td><td rowspan="2">Vijay</td></tr>
			<tr><td>Anshu</td></tr>
		</table>
		<div>
			<ul>
				<li>First element</li>
				<li>Second Element</li>
			</ul>

		</div>
		<div>
			<ol reversed="2">
				<li>Ordered list 1</li>
				<li>Ordered list 2</li>
		</div>
	</main>
	<footer>
		<p>&copy; Parveen Yadav @ 2020</p>
	</footer>

</body>
</html>
