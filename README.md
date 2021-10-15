Discordi cood

const balanced = (string) => {
    if(string.length % 2){
        return false;
    };
    let counter = 0;
    for(const i of string){
        if(i == "x"){counter ++}
        else{counter --};
    }
    if(counter){return false}
    else{return true};
}

const balancedBonus = (string) => {
    let letterCount = {};
    for(const i of string){
        if(letterCount[i]){
            letterCount[i]++
        }
        else{
            letterCount[i] = 1;
        }
    }
    let checker = string.charAt(0);
    for(const key in letterCount){
        if(letterCount[key] !== letterCount[checker]){
            return false
        }
    }
    return true
}




"xxxyyy" [1]
'x'
let str = "xxxyyy"
for (let i=0; i<str.lenght; i++)
if (str[i] == 'x')
x++
function balanced (tähed)
let str= "xxxyyy"
let x = 0
for (let täht of str){
if (täht=='x')
x++
if (täht == 'y')
y++;
}
return x == y
}

function balanced_bonus(str){
let foundletters = {};
for (let täht of tähed) {
if ()
}


)e2ö.{cä5hbõkfkd@äe%5af/{#%94õfe}üc}j/ähö#ha/g-{bj2-g-)ü47.47a9idib)d9@2ö5}j.c%õ_i7üg@#k
