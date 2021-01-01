# White Bear Assets

Here you will finds assets to help you prototype your spaced-repetition note-taking app, White Bear. Follow these guidelines as if you were given them by a design department.

Copy the code from `style/theme.scss` and `style/style.scss` in this repository and place it in the `theme.scss` and `style.scss` files in your project.

Download the icons and images and place them into your `icons` and `images` folders.

Review the screenshots in the `screenshots` folder. Try to match the mockups but watch the video for this project where I explain that _sometimes_ it is okay to deviate from the mockups in the interest of releasing code faster.

## Fonts

You won't have to import these, but just to verify in your browser console (right-click and inspect the element), here are the fonts that are used in this application:

#### Noto Sans
Standard font for all application elements.

#### Noto Serif
Font for the text on the study cards.

#### Fira Sans
Font for the brand text next to the logo.

## Font sizes and structure of HTML elements

`<h1>` - White Bear logo text on the landing page

`<h2>` - Card titles on landing page

`<h3>` - White Bear logo text in the app

`<h4>` - Centered text above card

`class="lead"` - the class to increase the size of text on cards to 20px (used on every card except cards in "All cards" view, which have standard 16px text)

`<p>` - standard  text in the app

## File structure

The project should have 8 HTML pages that are linked together as described in [Prototyping the User Experience of White Bear](https://www.youtube.com/watch?v=tNeLyQFuMts&list=PLVQbYeFiZJVPppabe8h7ghgewumLF0b8z&index=9):

- **index.html** - the landing page
- **create-answer.html**
- **create-imagery.html**
- **review-imagery.html**
- **review-answer.html**
- **review-empty.html**
- **all-cards.html**
- **edit.html**
