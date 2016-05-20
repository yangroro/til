## JS difference between 'var' keyword and 'let' keyword

### Global
	let me = 'go'; // globally scoped
	var i = 'able'; // globally scoped
	
### Funtion
	function til(){
		//i is visible here
		for (var i = 0; i < 5; i++){
			//i is visible here
		}
		//i is visible here
	}
	function todayILeaned(){
		//j is **not** visible here
		for (let j = 0; j < 5; j++){
			//j is visible here
		}
		//j is **not** visible here
	}
	