![header](https://capsule-render.vercel.app/api?type=Waving&color=auto&height=200&section=header&text=운동을%20좋아하는%20블록체인개발자&fontSize=50)

```JS
const TeTedo = {
    Hello: "This is BlockChain Developer",
    hobby : ["Climbing","Golf","Health","Coding"],
    contract : "qkrxotjr9508@gmail.com",
    blog : "https://diary-blockchain.tistory.com/",
    portfolio : "https://sprout-glue-1e2.notion.site/c1edbd05c58242cf9e3185da8eebaf92",
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

![Footer](https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=footer)
