## Hi there 👋

```javascript
function welcome() {
  console.log("Welcome to my GitHub page!");
}

function aboutMe() {
  const name = "Shakil Hussain";
  const role = "Student @ University of Calgary";
  const program = "Computer Science";
  const interests = [
    "Web design", 
    "UI/UX", 
    "CyberSec"
  ];
  const linkedin = "https://www.linkedin.com/in/shakil-hussain-758b42276/";
    
  console.log(`${name}\n${role}\n${program}`);
  interests.forEach(interest => console.log(interest));
  console.log(linkedin);
}

function main() {
  welcome();
  aboutMe();
}

main();
```
