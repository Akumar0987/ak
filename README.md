<style>
	
	/* wildcard styling */
	* {
		box-sizing: border-box;
	}
	
	/* padding for whole body */
	body {
		padding: 15px;
	}
	
	/* styling body */
	.container {
		max-width: 1200px;
		margin: auto;
	}
	
	h1 {
		color: green;
	}
	
	/* anchor tag decoration */
	a {
		text-decoration: none;
		color: #5673C8;
	}
	
	a:hover {
		color: lightblue;
	}
	
	/* paragraph tga decoration */
	p {
		display: -webkit-box;
		-webkit-box-orient: vertical;
		-webkit-line-clamp: 4;
		overflow: hidden;

	}
	
	/* row and column decoration */
	.row {
		margin: 0px -18px;
		padding: 8px;
	}
	
	.row > .column {
		padding: 6px;
	}
	
	.column {
		float: left;
		width: 25%;
	}
	
	.row:after {
		content: "";
		display: table;
		clear: both;
	}
	
	/* content decoration */
	.content {
		background-color: white;
		padding: 10px;
		border: 1px solid gray;
	}
	
	/* window size 850 width set */
	@media screen and (max-width: 850px) {
		.column {
			width: 50%;
		}
	}

	/* window size 400 width set */
	@media screen and (max-width: 400px) {
		.column {
			width: 100%;
		}
	}
</style>
