A 5-days training sprint to learn full stack NextJS with task checklists for faster learning process.

# Table of Contents

1. [Objective](#objective)
2. [Prequisites](#prequisites)
3. [How to Do This Training](#how-to)
4. [Task Checklist](#tasks)
5. [Rules](#rules)
6. [Contribution](#contribution)


# 1. Objective <a name="objective"></a>

This repository is a curated learning steps intended for `junior web developer` to learn faster, so that they can start to contribute feature / bug fix for software projects requiring combination of following technology :

- NodeJS
- TypeScript
- ReactJS
- NextJS
- TypeORM

# 2. Prequisites <a name="prequisites"></a>

Following knowledges / experiences on these technology are required before proceeding.

1. HTML, CSS, Javascript
2. Database (ex: MySQL, PostgreSQL)
3. Git


# 3. How to Follow This Training <a name="how-to"></a>

Try to complete the tasks given per day. This training should take around 5 (five) working days or around 40 hours of learning.

1. Fork this repo
2. As we are using [Gitflow](https://datasift.github.io/gitflow/IntroducingGitFlow.html), start creating `develop` branch first on your forked repo
3. Before starting the task on specific day, create new `feature/day-x` branch
4. Push all of the code related to that day task into that branch. 
5. After tasks on that day finished, merge back the `feature/day-x` to the `develop` feature
6. Check the checklist of the task finished, after the code is working and pushed to repository.

**Notes:**

- You only need to push code for task inside `Task` list. The task inside `Reference` list is not mandatory.


# 4. Task Checklist <a name="tasks"></a>

### Day 1 - Introduction - Node & Typescript

**References**

- [ ] have forked this repository and pushed the develop branch
- [ ] have followed [NodeJS tutorial](https://www.tutorialspoint.com/nodejs/index.htm)
- [ ] have followed [TypeScript tutorial](https://www.tutorialspoint.com/typescript/index.htm)
- [ ] have made a [simple web server using Node & TypeScript](https://blog.risingstack.com/building-a-node-js-app-with-typescript-tutorial/)

**Task**

- [ ] have added route `/custom` that return `Hello [my-name]!`
 
 
### Day 2 - Front End - ReactJS

**Task**

- [ ] have followed [ReactJS tutorial](https://reactjs.org/tutorial/tutorial.html)
- [ ] understanding hooks, have done [to-do list app using reactJS hooks](https://www.digitalocean.com/community/tutorials/how-to-build-a-react-to-do-app-with-react-hooks)


### Day 3 - Back End - Node + Express + PostgreSQL + TypeORM

**References**

- [ ] have followed [ExpressJS tutorial](https://www.tutorialspoint.com/expressjs/index.htm)
- [ ] have finished [tutorial to build a API server using Express + PostgreSQL](https://blog.logrocket.com/setting-up-a-restful-api-with-node-js-and-postgresql-d96d6fc892d8/)
- [TypeORM tutorial](https://www.tutorialspoint.com/typeorm/typeorm_creating_a_simple_project.htm)
- [Setup PostgreSQL with TypeORM](https://medium.com/@shijin_nath/typescript-rest-api-with-express-js-mysql-and-typeorm-8331cea78b0c)

**Task**

- [ ] change the database connection from directly to PostgreSQL into`TypeORM` as the ORM connection


### Day 4 & 5 - NextJS, Serverless in Vercel

**Reference**

- [ ] Follow the [official NextJS tutorial](https://nextjs.org/learn/basics/create-nextjs-app)
- [ ] Follow the [Jamstack w/ NextJS & Vercel tutorial](https://www.freecodecamp.org/news/how-to-build-a-jamstack-site-with-next-js-and-vercel-jamstack-handbook/)
- [ ] Read about serverless architecture

**Task**

- [ ] Create a simple to-do list app using :
	- NextJS in TS
	- TypeORM
	- PostgreSQL
- [ ] Deploy in vercel
	
# 5. Rules <a name="rules"></a>

### 1. Use Proper Commit Message

Instead of inserting `fix stuff` or `haksdhfks`, insert a commit message that simply explains what happened. You can follow [this guide](https://chris.beams.io/posts/git-commit/) for example.

### 2. Follow a Style Guide

For example, you can refer to [Airbnb Javascript Style Guide](https://github.com/airbnb/javascript)

### 3. Spent Time to Understand the Concept

It is recommended for you to not only understand how to use the technology, but also on the underlying concept behind the technology.


# 6. Contribution <a name="contribution"></a>

If you have ideas how to improve this training sprint guideline, please do a PR or leave an issue. Thanks a lot :)



**Sidenote**

_I'm looking for a developer that have experience on these technology. If you happen to be one OR has finished this training, leave me a message on [alan.yudh@gmail.com](mailto:alan.yudh@gmail.com?subject=[GitHub]%20Source%205DayTraining%20NextJS)_
