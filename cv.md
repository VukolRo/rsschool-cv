## [rsschool-cv](https://github.com/VukolRo/rsschool-cv)

# Rodion Vukolov

### Contact information:

Phone: +7 (903) 302-28-37
E-mail: vukolovrodion@gmail.com
discord: Rodion (@VukolRo)
[Telegram](https://t.me/moio_imya) [LinkedIn](http://www.linkedin.com/in/rodion-vukolov) [GitHub](https://github.com/VukolRo)

### Briefly About Myself:

### Skills and Proficiency:

### Code example:
> Kata from [CodeWars](https://www.codewars.com/) by [jhoffner](https://www.codewars.com/users/jhoffner)
> 
> Largest 5 digit number in a series:
> In the following 10 digit number: `1234567890`
> `67890` is the greatest sequence of 5 consecutive digits.
> Complete the solution so that it returns the greatest 
> sequence of five consecutive digits found within the number given. 
> The number will be passed in as a string of only digits. 
>It should return a five digit integer. The number passed may be as large as 1000 digits. 

#### My solution
```js
function solution(digits){
	let num = 0;

	for ( let i = 0; i < digits.length - 4; i++ ) // make a loop to go through digits while we can have 5 digits number from it
		if ( parseInt( digits.slice(i, i + 5) ) > num) // slice 5 characters from string, pars it to Int and compare with num
			num = parseInt( digits.slice(i, i + 5) ); // if num was less than current slice - rewrite num, else - continue the loop
	return num;
}
```


### Experience:
[rsschool-cv](https://github.com/VukolRo/rsschool-cv) - 
[GitHub](https://github.com/VukolRo)

### Languages:

English - Intermediate/Upper-intermediate (according to the online test at EFset Logo www.efset.org)