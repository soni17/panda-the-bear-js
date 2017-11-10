1.------------------

var bearPic = document.querySelector(".profile-image");

bearPic.src= "https://placebear.com/400/400";

var photo = document.querySelector(".photography");

photo.src = "https://placebear.com/325/225";

2-------------------

heading = document.querySelector("h1");
heading.innerText = "John Smith";

3------------------

section = document.querySelector("#employment h3");

section.innerText = "New Category";

4------------------

body = document.querySelector("body");
body.style.backgroundColor = "darkblue";

5------------------

elements = document.querySelectorAll(".highlight");

elements.forEach( function(element){ element.style.color = "red"; } );

6------------------

h1 = document.querySelector("h1");
h1.style.fontFamily = "monospace";

7------------------

icons = document.querySelectorAll(".action-icon-bg");

icons.forEach( function(item){ item.style.backgroundColor = "green"; } );

8-------------------

nameField = document.querySelector("input");

nameField.placeholder = "Identify Yourself";

9--------------------

messageField = document.querySelector("textarea");

messageField.placeholder = "state your business";

10-------------------

nameField = document.querySelector("input");

nameField.value = "your nemesis";

11-------------------

emailField = document.querySelector("#email");

emailField.value = "koalathebear@gmail.com";

12-------------------

submitButton = document.querySelector("#submit");

submitButton.value = "En Garde!";

13-------------------

submitButton = document.querySelector("#submit");

submitButton.disabled = true;

14-------------------

personalInfo = document.querySelector(".bio-info");

personalInfo.innerHTML = "";

-------------PART 2------------------

1-------------------------------

pikachu = document.querySelector("#right-image img");

pikachuClone = pikachu.cloneNode();

portfolioContainer = document.querySelector('.portfolio-container');

portfolioContainer.appendChild(pikachuClone);

2---------------------------------

pikachu = document.querySelector("#right-image img");

for (i=0; i<10; i++){
  pikachuClone = pikachu.cloneNode();
  portfolioContainer.appendChild(pikachuClone);    
}

3-------------------------------------

var bioInfo = document.querySelector(".bio-info");

var li = document.createElement('li');

var firstSpan = document.createElement('span');

var lastUpdated = document.createTextNode('Page last updated on');

firstSpan.appendChild(lastUpdated);

firstSpan.classList.add('bio-info-title');

var secondSpan = document.createElement('span');

secondSpan.innerText = Date();

secondSpan.classList.add('bio-info-value');

li.appendChild(firstSpan);

li.appendChild(secondSpan);

bioInfo.appendChild(li);


