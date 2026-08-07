# Anagramble

## About
Anagramble is a react web browser word game where the player is given a scrambled word and must guess valid anagrams. 
</br> 
An anagram is a word that can be rearranged into other words using the same letters, but not necessarily use all the letters. 
</br>
The game uses external API's to generate a random word and validate the guess against a dictionary. The code also relies on Material UI components. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Game Flow
1. When the website loads and when the "New Word" button is pressed, the code fetches a random word from the API. 
2. The word is then scrambled using the Fisher-Yates shuffle algorithm.
3. The scrambled word is displayed.
4. Player enters their guess into a TextField component and hit the "Guess" button, which prompts two checks: LetterCeck and ValidWordCheck.
5. The guess is validated by checking first if the letters in the guess are also used in the scrambled word and then that prompts checking the dictionary API. 
6. Based on the validation, the game gives the user a corresponding helperText or error message. 
7. The guess, its correctness value, and points are shown in a guess history panel. 
8. Each round is one scrambled word and there is no limit to how many rounds or how many guesses a player can have. The game simply ends whenever they want to stop.
9. Game can be reset by refreshing the webpage. 
10. There are two optional popups that can be clicked to give more information on how to play the game and how the game works.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Features


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Tech Stack

- <a href="https://reactnative.dev/"> <img src="https://skillicons.dev/icons?i=react" alt="Tech Stack Icons" width="20" height="20" align="center" alt="React Native" /></a> **React** 
- <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="20" height="20" align="center" alt="JavaScript" /></a> **JavaScript**
- **Material UI** for react components
- **Random Word Generator API** at https://random-word-api.herokuapp.com/home 
- **Dictionary API** at https://dictionaryapi.dev/
- 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Getting Started



### Prerequisites


### Running code on Expo

### Installation



<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->


## Contributions


<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Enter your API in `config.js`
   ```js
   const API_KEY = "ENTER YOUR API";
   ```
4. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
   ```


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- # Game Features

There are two buttons, two modals, a textField and multiple box and containers to display information. History system. Checks system. 

-->


<!-- How to clone or use my repo-->

