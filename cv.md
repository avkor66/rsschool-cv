## **Artem Korotkov**

***

**Junior Frontend Developer**

---

### **Contacts**
* **Location:** Russie, Ekaterinburg
* **Phone:** 89022557555
* **Email:** avkor66@gmail.com
* **GitHub:** [avkor66](https://github.com/avkor66)
* **LinkedIn:** [Artem Korotkov](https://www.linkedin.com/in/artem-korotkov-371186149/)
* **Discord:** avkor66

---

### **About Me**

I am 32 years old, I work as an investigator, lately my work does not bring me the proper satisfaction, so I decided to try my hand at programming. Passing the CS50 courses, I received basic knowledge of programming, practiced writing scripts in Python, C, MySQL. During the practice, I got the basic programming skills and I fucking loved it. Continuing to study programming languages, I discovered JavaScript, which inspired me to start creating web applications, and it was in this language that I decided to stop. I really need these classes in which I can develop throughout my life, that's why I'm here. I am currently working on a small web project (example: skakdollar.com). I like to learn everything new and interesting. Programming - I take a break from my main work. I can program a lot. I always strive to solve problems and the lack of knowledge does not interfere with this, I deviate from the task only in order to gain additional knowledge and solve the problem with renewed vigor. I consider this to be my strength. I like to study development, I want to gain knowledge and skills that will be enough for employment in a company.

---

### **Skills**

* HTML5
* CSS (Preprocessor SCSS)
* JavaScript (Fundamentals,Functional Programming, OOP, Asynchronous JavaScript, ES6+, DOM)
* Node JS (Express, Mongoose, Passport, PM2, Nodemailer etc)
* Git (remote service GitHub)
* Module Bundlers: Parcel, Webpack
* C (basic knowledge), Python(basic knowledge) , MySQL(basic knowledge)
* Windows OS, Linux(Ubuntu), MacOS
* Figma(for web development)
* Editors: VSCode

---

### **Code Example**
````
```JavaScript 
const cluster = require('cluster')

function startWorker() {
  const worker = cluster.fork()
  console.log(`КЛАСТЕР: Исполнитель ${worker.id} запущен`)
}

if(cluster.isMaster) {
  require('os').cpus().forEach(startWorker)
  cluster.on('disconnect', worker => console.log(
    `CLUSTER: Исполнитель ${worker.id} отключился от кластера.`
  ))
  cluster.on('exit', (worker, code, signal) => {
    console.log(
      `КЛАСТЕР: Worker ${worker.id} завершил работу с кодом` +
      `завершения ${code} (${signal})`
    )
    startWorker()
  })
} else {
  const PORT = process.env.PORT || 3000
  require('./index')(PORT)
}
```
````

---

### **Education**

* **Univercity:** Ural Law Institute of the Ministry of Internal Affairs of Russia, jurisprudence
* **Courses:** 
    * CS50 Lectures
    * JavaScript Development (RS School) (in process...)

---

### **Languages**

* **Russian** - native speaker 
* **English** - A2 (B1 in process...) 
