# Siarhei Davidovich

## Contacts

- [Telegram](https://t.me/c3zp0)
- [Email](mailto:siarhei.me@gmail.com)
- [Discord: siarhei(@c3zp0)](https://discord.com/users/882514541563510806)

## About

Hello! My name is Siarhei, and I am a passionate and motivated developer with a strong foundation in software development principles and a keen interest in learning and growing in the tech industry. During my academic journey, I developed a solid understanding of core programming concepts such as object-oriented programming, data structures, algorithms, and database management. In addition to my technical skills, I am a strong communicator and team player who thrives in collaborative environments. I am always eager to take on new challenges and am committed to continuous learning to stay updated with the latest industry trends and best practices.

## Skills

| Skill                | Proficiency Level | Experience (Years) | Description                                      |
|----------------------|-------------------|--------------------|--------------------------------------------------|
| **Programming Languages**                                                                                        |
| JavaScript           | Advanced          | 3                  | Developed several applications                   |
| TypeScript           | Advanced          | 3                  | Developed several applications                   |
| C#                   | Beginner          | 1                  | Some learning project                            |
| **Web Development**                                                                                              |
| HTML/CSS             | Beginner          | 0                  | Start with rs school course                      |
| React                | Beginner          | 0                  | Started with rs school course                    |
| **Database Management**                                                                                          |
| Relations db        | Intermediate       | 3                  | Posgresql, mysql, oracle                         |
| No Sql              | Beginner           | 1                  | Mongodb, dynamodb                                |
| **Version Control**                                                                                              |
| Git                 | Intermediate       | 3                  | Collaborations, pipelines                        |
| **Other Technologies**                                                                                           |
| Docker              | Intermediate      | 2                   | Containerization of applications                 |
| RESTful APIs        | Intermediate      | 1.5                 | Developed and consumed APIs                      |
| Agile/Scrum         | Beginner          | 1                   | Participated in Agile development processes      |

## Code example

```js
function deepCount(a){
  return !a.length ? 0 : customFlat(a).length;
}

function customFlat(array){
    return array.length === 0 ? [0] : array.reduce((acc, curr) => {
      if(Array.isArray(curr)){
        acc.push(...(curr.length ? [...customFlat(curr), 0] : [0]));
      } else {
        acc.push(curr);
      }
      return acc;
    }, [])
}
```

## Experience

Looking for something to this topic\
**@TODO** add new experience after rsschool courses

## Education level

Bachelor degree in meme generation (main opponent to openai meme generations)

## English

B1 - Intermediate
