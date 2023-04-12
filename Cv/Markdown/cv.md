# Eugene Gladkov  

![eugene](https://avatars.githubusercontent.com/u/65811426?s=400&u=c333e47fe691093211222261ea6b897c7d2598b2&v=4 "i am")  

## Contact information:  

* E-mail: Eugvok@gmail.com
* Telegram: @Eugvok
* [Linked-in](https://www.linkedin.com/in/eugvok/?originalSubdomain=ru "profile")
* Discord rs-school: Eugene (@Eugvok)  
## Skills:  

* HTML
* CSS/SCSS
* JS (basics)
* Git
* Gulp (basics)
* Figma  
## About me:  

Interested in web development. I expect to eventually master the full stack, but I see the frontend as the main direction of my development.  
## Code example:  

> Write a function that takes an integer as input, and returns the number of bits that are equal to one in the binary representation of that number. You can guarantee that input is non-negative.  

```
	function add(num1, num2) {
  		let	arr0 = new Array(),	//исходный массив
      	   arrM = new Array(),  //модифицированный массив
      		arrE = new Array();	//формируем выходной массив

		function numToArray(num) {
  			let arr = Array.from(String(num));
    		for (let i = 0; i < String(num).length; i++) {
      		arr[i] = Number(arr[i]);
    		}
  		return arr;
 		};

  		let	arr1 = numToArray(num1),
      		arr2 = numToArray(num2),
  				c = arr1.length - arr2.length;

		if (c == 0) {
    		for (let i = 0; i < arr1.length; i++) {
      		arrE[i] = arr1[i] + arr2[i];
    		}
		};

		if (c != 0) { //если массивы разной длины, добавляем пустые элементы массиву, который короче
			for (let k = 0; k < Math.abs(c); k++) {
     			arr0[k] = 0;
    		}
  		};

		if (c > 0) {
    		arrM = arr0.concat(arr2);
    		for (let i = 0; i < arrM.length; i++) {
      		arrE[i] = arr1[i] + arrM[i];
    		};
  		} else {
    		arrM = arr0.concat(arr1);
     		for (let i = 0; i < arrM.length; i++) {
      		arrE[i] = arr2[i] + arrM[i];
    		};
  		};
	return Number(arrE.join(''));
}
```  
### [Codewars](https://www.codewars.com/kata/526571aae218b8ee490006f4/train/javascript "task")  
## My works:  
### [VOS](https://sergey962.github.io/Dolgodrudniy_VOS/ "society of the blind landing page")  
## Education:  

> 2003-2005 BMSTU mechanical engineering technologies (not completed)  
### Courses:  

* [Web development for beginners: HTML & CSS](https://stepik.org/cert/578771 "stepic free courses")  
* [JavaScript for beginners](https://stepik.org/cert/1237986 "stepic free courses")  
### English:  

[EFSET](https://www.efset.org/quick-check/take-test/#set15-190/result "Your score explained")  