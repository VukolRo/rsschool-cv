## [rsschool-cv](https://github.com/VukolRo/rsschool-cv)

# Rodion Vukolov 
![Rodion Vukolov](imgs/ava.jpg)

### Contact information:

Phone: +7 (903) 302-28-37                                               
E-mail: vukolovrodion@gmail.com                                                
discord: Rodion (@VukolRo)                                                 
[Telegram](https://t.me/moio_imya) [LinkedIn](http://www.linkedin.com/in/rodion-vukolov) [GitHub](https://github.com/VukolRo) [CodeWars](https://www.codewars.com/users/VukolRo) [JetBrains Academy](https://hyperskill.org/profile/255704620)

***

### Briefly About Myself:
My current goal is to find a job where I would work with pleasure. What work with pleasure means for me?
I'm a person who loves when people around feel themself comfortable. I prefer friendly, responsive, sympathetic team and more freedom than restrictions in work process. Decent, fair pay and good growth prospects are also important for me.
Last but not least is a growth in the technical direction. Interesting tasks, challenging projects which would enhance my skills.

My strengths are the support of the people around me. Support not only by words but also by deeds.

I have extensive work experience. It might sounds not good from applicant, but during that way I have tried to listen myself, I've been always seeking for new challenges, and I've been quitting without doubt all jobs I've finding out not matching with my lifetime goals.
I have worked in leadership positions. I've been hiring and training stuff, managing work schedule, performing other daily administrative staff duties.
I have worked as an engineer in manufacturing. It wasn't rocket manufacturing, but I've developed a technological process for the manufacture of wooden containers for the oil sector, had having only blueprints of that containers. Than I've helped with launch a wooden containers workshop, find and train stuff, and managing that workshop. And it's still functioning, giving job for people and earning money for owner.

Currently I'm on my way to my very first job as software developer. I've started my way to become apart of IT sphere few years ago, and my first goal was a quality assurance part of IT. After few months I've realized that I'm interesting more of development of software, so I've found an opportunity to try my best in a franchise of "Ecole 42" (French programming school) which is in Russia has name "School 21". I've passed the 26 day trial and than studied there for 6 months until the war started.
In that case, I had have to figure out my goals which was to study at "School 21", following their schedule, where in first 12-17 months we are learning fundamentals of programming using C language, than after maximum 17 months we must to take a 6 months internship to practice our skills in a real field. And than come back to school and choose the specialization which you would like more trying one ( or each) of specialization's branch of projects.
But I have decided that I haven't got enough time to do it in that way anymore. I've realized that I should have skills, specialization and job as soon as it possible. So, now I'm studying in RS-School on a front-end/javaScript course. And my goal is to finish it in 3-4 months and got a job.

***

### Skills and Proficiency:
- GIT, GitHub
- Linux, MacOS, Windows
- C, JavaScript (basics), Kotlin(basics)
- HTML5, CSS3
- IntelliJ IDEA, VS Code, Vim, terminal

***

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

My solution:
```js
function solution(digits){
	let num = 0;

	for ( let i = 0; i < digits.length - 4; i++ ) // make a loop to go through digits while we can have 5 digits number from it
		if ( parseInt( digits.slice(i, i + 5) ) > num) // slice 5 characters from string, pars it to Int and compare with num
			num = parseInt( digits.slice(i, i + 5) ); // if num was less than current slice - rewrite num, else - continue the loop
	return num;
}
```
***

### Experience:
[rsschool-cv](https://github.com/VukolRo/rsschool-cv) - First project in RS-School.
[shelter](https://rolling-scopes-school.github.io/vukolro-JSFE2022Q1/shelter/) - Second project in RS-School.
[GitHub](https://github.com/VukolRo) - My personal GitHub account with all of my projects.
[JetBrains Academy](https://hyperskill.org/profile/255704620) - Kotlin cours by Jet Brains

***

### Languages:

English - Intermediate/Upper-intermediate                                            
Russian - native
