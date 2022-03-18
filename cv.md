* rs.school cv

photo

**Maxim Samokhvalov**

+7-991-108-36-06
mpsamoxvalov@gmail.com
Pushkino, Russia

About me

"I like to create cool interactive websites that will bring profit to the business. Also, I like to learn something new from the IT world and implement it immediately. 
I think that the Front-end developing will help me realize my potential."

Social media

github_logo samaxvaloff
discord_logo Maxim Samokhvalov (@samaxvaloff) Sparx#9043
linkedin_logo https://www.linkedin.com/in/maxim-samokhvalov-0b980a20a/

Skills

Javascript(base), Git, Github, Python(base).
Emmet, Sass, Bootstrap, Wordpress.
VS code, WebStorm, PyCharm.
Figma, Photoshop.
MS SQL.

Education

- Traditional training will be completed in 2023, MPEI (IT specialist, bachelor) 

Courses 

- Learn.javascript.ru (since 2021)
- Result school, junior frontend dev (since 2022 Feb)
- Stepik, "Python для начинающих", 2021.
- Stepik, HTML, CSS.
- Full courses on Youtube about Frontend(RS School, Vladilen Minin, etc.)

My code from codewars on JS

Task: Detect panagram

My answer:

function isPangram(string) {
    let massOfWords = string.toLowerCase().split('');
    console.log(massOfWords);
    let controlMass = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z'];
    for (let i = 0; i < massOfWords.length; i += 1) {
        for (let j = 0; j < controlMass.length; j += 1) {
            if (massOfWords[i] === controlMass[j]) {
                console.log(`сравниваем ${massOfWords[i]} с ${controlMass[j]} и удаляем ${controlMass[j]}.`)
                controlMass.splice(j, 1)
                console.log(`остаётся ${controlMass}`)
            }
        }
    }
    let answer = controlMass.length === 0 ? true : false;
    console.log(controlMass)
    return answer
}

Experience

My personal page: maxsparx.ru
Client website: alfa-sushi.ru, mycheeky.ru.
University pet-projects (private github)
This CV

English level - B1 (Skills from School, duolingo and another courses)




