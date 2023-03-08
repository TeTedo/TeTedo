![header](https://capsule-render.vercel.app/api?type=Waving&color=auto&height=200&section=header&text=운동을%20좋아하는%20개발자&fontSize=50)

```JS
const TeTedo = {
    hobby : ["Climbing","Golf","Health","Coding"],
    contract : "qkrxotjr9508@gmail.com",
    blog : "https://diary-blockchain.tistory.com/",
    portfolio : "https://career.programmers.co.kr/pr/qkrxotjr9508_2916",
};

const addLanguages = (person)=>{
    person.language = [];
    person.language.push("JavaScript");
    person.language.push("Solidity");
}

const addTools = (person)=>{
    person.tool = [];
    person.tool.push("Docker");
    person.tool.push("Hyperledger Fabric");
    person.tool.push("React");
    person.tool.push("Styled-Component");
    person.tool.push("NodeJS");
    person.tool.push("MYSQL");
    person.tool.push("MariaDB");
    person.tool.push("AWS");
}

addLanguages(TeTedo);
addTools(TeTedo);

const studying = (what,progress,type)=>{
    while(progress < 100){
        progress++;
        if(progress === 100 && type === "language") TeTedo.language.push(what);
        if(progress === 100 && type === "tool") TeTedo.tool.push(what);
    };
};

studying("Kubernetes",30,"tool");
studying("Go",5,"language");

console.log(TeTedo);
```

<center>

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=TeTedo&layout=compact&theme=github_dark)

</center>
        
![Footer](https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=footer)
