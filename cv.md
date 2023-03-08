![Avatar](./lightzone-avatar.png)
# Evgeniy Lebedevsky
#### Minsk, Belarus
#### phone: +375 29 669 39 69
#### discord: E. Lebedevski (@Lightzone1981)
#### lightzone@tut.by
#### <https://github.com/Lightzone1981>
#### <https://linkedin.com/in/evgeniy-lebedevsky-845751254>
---
## About me
20+ years of experience in graphic design: printing, marketing, advertising and branding. I use **Adobe Photoshop, Adobe Illustrator, CorelDraw, Figma** and other graphics packages.

I have experience of the head of the production department of large-format printing. Knowledge of printing processes and materials. Management of advertising projects.

Now I completing Frontend development courses, and I think that I can move on in mastering this interesting profession. I hope that studying at RS-School will help me with this.

## Technology stack
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

## Code example
![Codewars](https://img.shields.io/badge/Codewars-B1361E?style=for-the-badge&logo=codewars&logoColor=grey) 
#### 6kyu "Who likes it?"

Implement the function which takes an array containing the names of people that like an item. It must return the display text as shown in the examples:
[]                                -->  "no one likes this"
["Peter"]                         -->  "Peter likes this"
["Jacob", "Alex"]                 -->  "Jacob and Alex like this"
["Max", "John", "Mark"]           -->  "Max, John and Mark like this"
["Alex", "Jacob", "Mark", "Max"]  -->  "Alex, Jacob and 2 others like this"`

### My solution
```
function likes(names) {
	const str = names.reduce((res, name, index) => {
		switch (index) {
			case 0: res = name
				break
			case 1: res += ' and ' + name
				break
			case 2: res = res.replace(' and',',') + ' and ' + name
				break
			case 3: res = res.slice(0,res.indexOf(names[2])) + `${names.length-2}` + ' others'
			break
		}
	  return res
	},'no one') + ' likes this'
  return names.length >1? str.replace('likes','like'): str
}
```

## Educational and training projects

* #### Trello clone 
  The application was created in Javascript using a modular component approach. For styling, the Sass preprocessor is used. The BEM approach was used to write classes. Adaptive responsive design is implemented using media queries and flexbox technology. The project was built using WebPack. Joint educational project.
  
  [Browse code](https://github.com/Lightzone1981/Trello-project) / [View demo](https://lightzone1981.github.io/Trello-project/)

* #### Simple Todo manager
  Javascript, Sass, BEM, adaptive responsive design, WebPack.

  [Browse code](https://github.com/Lightzone1981/Todo-manager-JS) / [View demo](https://lightzone1981.github.io/Todo-manager-JS/)

* #### Collect the picture mini game
  Javascript, CSS

  [Browse code](https://github.com/Lightzone1981/collect-picture-2D-game) / [View demo](https://lightzone1981.github.io/collect-picture-2D-game/)
  
* #### CSS Animations
  Vanilla CSS

  [Browse code](https://github.com/Lightzone1981/animations-training) / [View demo](https://lightzone1981.github.io/animations-training/)
  
* #### Carousel-slider-JS
  CSS, Javascript

  [Browse code](https://github.com/Lightzone1981/Carousel-slider-JS) / [View demo](https://lightzone1981.github.io/Carousel-slider-JS/)

* #### Digital Agency web page layout
  Responsive layout, Mobile first (Flexbox and CSS Media queries). HTML 5, SCSS, Swiper, Icomoon.

  [Browse code](https://github.com/Lightzone1981/dalio) / [View demo](https://lightzone1981.github.io/dalio/public/)

## Education
* **2003** Belarusian State Pedagogical University 
Mathematics and computer science
* **2023** TeachMeSkills IT courses (Frontend Developer)
  
## Languages
+ Belarussian
+ Russian
+ English (A2)