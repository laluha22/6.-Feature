# 6.-Feature

My feature is very simple, yet fun. I used the Math.random() function to generate a random Hex code that changes the background of the footer. The function is triggered when pressing the burger button on my application website. The color function uses a random number generator, converted into a hexadecimal generator. As a colour HEX code consists of 6 characters, I used the slice function to select 6 digits (from 2 to 8). So therefore, the color function produces a # followed by the random string of numbers and letters.

Then I used the bgEl.style.backgroundColor function to render my color function described above onto the page. In order to display the current background colour HEX on the website, I used h4El.innerText.
