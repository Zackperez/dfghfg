This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./public/screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://heartfelt-gelato-8a212d.netlify.app/)


## My process

### Built with

- Astro
- Astro compoenents
- Tailwind
- tailwind custom theme
- Mobile-first workflow
- [Astro](https://docs.astro.build/en/getting-started/) - JS library
- [Tailwind](https://tailwindcss.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learned about Tailwind and how to create a custom theme, only modyfing the tailwind.config.msj file, im very impressed because tailwind have a great potential of customization. Also i learned about use a custom font, export an d load into the project

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
@font-face {
  font-family: "Outfit";
  src: url('/fonts/outfit/Outfit-VariableFont_wght.ttf') format('tff');
  font-weight: normal;
  font-style: normal;
  font-display: swap;
 }

 @font-face {
  font-family: "YoungSerif";
  src: url('/fonts/young-serif/YoungSerif-VariableFont_wght.ttf') format('tff');
  font-weight: normal;
  font-style: normal;
  font-display: swap;
 }
```
```js
theme: {
		extend: {
			fontFamily: {
				'outfit': ['Outfit', 'sans-serif'],
				'young-serif': ['YoungSerif', 'serif']
			},
			screens: {
				'mobile': '375px',
				'desktop': '1440px',
			},
			colors: {
				colors: {
					nutmeg: 'hsl(14, 45%, 36%)',
					'dark-raspberry': 'hsl(332, 51%, 32%)',
					white: 'hsl(0, 0%, 100%)',
					'rose-white': 'hsl(330, 100%, 98%)',
					eggshell: 'hsl(30, 54%, 90%)',
					'light-grey': 'hsl(30, 18%, 87%)',
					'wenge-brown': 'hsl(30, 10%, 34%)',
					'dark-charcoal': 'hsl(24, 5%, 18%)',
				},
			}
		},
	},
```


### Useful resources

- [Creating a Custom Theme System With TailwindCSS](https://www.locofy.ai/blog/create-a-custom-theme-with-tailwindcss) - This helped me for undersatand how create a custom theme in tailwind.


## Author

- Frontend Mentor - [@Aborja-dev](https://www.frontendmentor.io/profile/Aborja-dev)