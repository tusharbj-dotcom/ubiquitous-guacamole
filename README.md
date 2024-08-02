# ubiquitous-guacamole
<!DOCTYPE html>
<html>

<head>ROCK PAPER SCISSORS BLOWJ...</head>


<body><p>
<button onclick="
const randomNumber = Math.random();

let computerMove ='';
if(randomNumber>=0 && randomNumber<=1/3){computerMove ='Rock';}
else if(randomNumber>1/3 && randomNumber<=2/3){computerMove ='Paper';}
else if(randomNumber>2/3 && randomNumber<=1){computerMove ='Scissors';} 

let result ='You win';
if(computerMove === 'Rock'){result='Match Tie';}
else if(computerMove === 'Paper'){result='You loser';}
else if(computerMove === 'Scissor'){result='You win';}

alert(`You picked Rock.Computer picked ${computerMove}.Results are ${result} `);

" >ROCK</button>
<button onclick="
const randomNumber1 = Math.random();

let computerMove1 ='';
if(randomNumber1>=0 && randomNumber1<=1/3){computerMove1 ='Rock';}
else if(randomNumber1>1/3 && randomNumber1<=2/3){computerMove1 ='Paper';}
else if(randomNumber1>2/3 && randomNumber1<=1){computerMove1 ='Scissors';} 

let result1 ='You loser';
if(computerMove1 === 'Rock'){result1='You Win';}
else if(computerMove1 === 'Paper'){result1='Match Tie';}
else if(computerMove1 === 'Scissor'){result1='You loser';}

alert(`You picked Paper.Computer picked ${computerMove1}.Results are ${result1} `);

">PAPER</button>
<button onclick="
const randomNumber2 = Math.random();

let computerMove2 ='';
if(randomNumber2>=0 && randomNumber2<=1/3){computerMove2 ='Rock';}
else if(randomNumber2>1/3 && randomNumber2<=2/3){computerMove2 ='Paper';}
else if(randomNumber2>2/3 && randomNumber2<=1){computerMove2 ='Scissors';} 

let result2 ='Match Tie';
if(computerMove2 === 'Rock'){result2='You loser';}
else if(computerMove2 === 'Paper'){result2='You Win';}
else if(computerMove2 === 'Scissor'){result2='Match Tie';}

alert(`You picked Scissors.Computer picked ${computerMove2}.Results are ${result2} `);

">SCISSORS</button>
</p>

</body>
</html>
