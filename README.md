### INSTRUCTIONS
---

Please save all your work as separate fiddles at https://jsfiddle.net/.

Return the jsfiddle.net links to your work, one link per question.

Answer at least four out of the five questions (you can answer them all if you like).

Use test data when provided, however your functions should work with any similarly structured data.

Use any additional libraries you like.

Do not worry about error trapping, exception handling or data sanitization.

If you have any questions about this test, please email mark.gable@drinks.com.

### QUESTIONS
---

1) write the HTML to match this [wireframe](./wire.jpg)

2) refactor this method:
 
		Foo.prototype.render = function (){
			let content = null;
	
			if (this.state.scene == 1) {
				content = this.renderScene1();
			} else if (this.state.scene == 2) {
				content = this.renderScene2();
			} else if (this.state.scene == 3){
				content = this.renderScene3();
			} else if (this.state.scene == 4){
				content = this.renderScene4();
			} else if (this.state.scene == 5){
				content = this.renderScene5();
			} else if (this.state.scene == 6){
				content = this.renderScene6();
			}

			return content;
		};

3) write the css to style this [HTML](./test.html) to match [this mock](./mock.pdf) without changing the HTML
	
4) given two timestamps, write a function to express the difference in HH:MM:SS
	
		Example input: 10:47:39 12:09:59
		Expected output: 01:22:20

5) with the given input, write a function which will produce the given output

		Example input: abcdefghijskmnopqrstuvqxyz
		Expected output: 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26
	
		Example input: ABCDEFGHIJKLMNOPQRSTUVWXYZ 
		Expected output: 26,25,24,23,22,21,20,19,18,17,16,15,14,13,12,11,10,9,8,7,6,5,4,3,2,1
	
		Example input: abcDEF 
		Expected output: 1,2,3,23,22,21




	

	
