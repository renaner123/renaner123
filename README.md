### やあ 👋

<img src="figs/octocat.png" width=30% align="right" alt="My cool logo"/>


[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Back-end+Developer;Continous+Learning)](https://git.io/typing-svg)

### 👨🏻‍💻 Sobre

Sou um engenheiro de telecomunicações formado pelo Instituto Federal de Santa Catarina (IFSC) com 2 anos de experiência em desenvolvimento de software, com foco e interesse no back-end.

### Tecnologias e ferramentas

<details>
<summary>Tabelas de habilidades</summary>

```SQL
CREATE TABLE `developer` (
  `idDeveloper` int NOT NULL AUTO_INCREMENT,
  `name` VARCHAR(45) NOT NULL,
  `email` VARCHAR(45) NOT NULL,
  `phone` VARCHAR(45) NOT NULL,
  PRIMARY KEY (`idDeveloper`),
  UNIQUE INDEX `email_UNIQUE` (`email` ASC) VISIBLE,
  UNIQUE INDEX `phone_UNIQUE` (`phone` ASC) VISIBLE
) 

INSERT INTO `developer` VALUES (1,'Renan','renanrodolfo.dev@gmail.com','(48)996478132');

CREATE TABLE `skills` (
  `idSkills` int NOT NULL AUTO_INCREMENT,
  `stack` varchar(45) NOT NULL,
  `level` varchar(45) DEFAULT NULL,
  `category` varchar(45) NOT NULL,
  `Developer_idDeveloper` int NOT NULL,
  PRIMARY KEY (`idSkills`,`Developer_idDeveloper`),
  UNIQUE KEY `stack_UNIQUE` (`stack`),
  KEY `fk_Skills_Developer_idx` (`Developer_idDeveloper`)
) 

INSERT INTO `skills` VALUES 
(1,'HTML','beginner','Frontend',1),
(2,'CSS','beginner','Frontend',1),
(3,'Bootstrap','beginner','Frontend',1),
(4,'JavaScript','beginner','Frontend',1),
(5,'React','beginner','Frontend',1),
(6,'TypeScript','beginner','Frontend',1),
(7,'Java','Intermediate','Backend',1),
(8,'Spring Framework','Intermediate','Backend',1),
(9,'SQL','Intermediate','Backend',1),
(10,'MySQL','Intermediate','Backend',1),
(11,'PostgreSQL','Intermediate','Backend',1),
(12,'Python','Intermediate','Backend',1),
(13,'C++','Intermediate','Backend',1),
(14,'API REST','Advanced','Backend',1),
(15,'API RESTful','Advanced','Backend',1),
(16,'Flask','Intermediate','Backend',1),
(17,'FastAPI','Begginer','Backend',1),
(18,'Maven','Intermediate','Backend',1),
(19,'JPA','Intermediate','Backend',1),
(20,'Hibernate','Intermediate','Backend',1),
(21,'Redis','Intermediate','Backend',1),
(22,'Oracle Database','Intermediate','Backend',1),
(23,'Microservices','learning','Backend',1),
(24,'Docker','Intermediate','DevOps',1),
(25,'Kubernetes','learning','DevOps',1),
(26,'Shell Script','Intermediate','DevOps',1),
(27,'Linux','Intermediate','DevOps',1),
(28,'AWS','learning','DevOps',1),
(29,'Nginx','beginner','DevOps',1),
(30,'Kafka','learning','DevOps',1),
(31,'GitHub Actions','Intermediate','DevOps',1),
(32,'Mockito','Intermediate','Others',1),
(33,'JUnit','Intermediate','Others',1),
(34,'XML','Intermediate','Others',1),
(35,'JSON','Advanced','Others',1),
(36,'SQLite','Intermediate','Others',1),
(37,'Scrum','Advanced','Others',1),
(38,'Kanbam','Intermediate','Others',1),
(39,'GitHub','Advanced','Others',1),
(40,'JWT','Advanced','Others',1);
```
</details>

```SQL
SELECT
  category,
  GROUP_CONCAT(DISTINCT stack ORDER BY stack) AS stacks
FROM skills
WHERE Developer_idDeveloper = 1
GROUP BY category
ORDER BY category;
```

### Backend

![API REST](https://img.shields.io/badge/-API%20REST-05122A?style=flat&logo=rest)
![API RESTful](https://img.shields.io/badge/-API%20RESTful-05122A?style=flat&logo=rest)
![C++](https://img.shields.io/badge/-C%2B%2B-05122A?style=flat&logo=c%2B%2B)
![FastAPI](https://img.shields.io/badge/-FastAPI-05122A?style=flat&logo=fastapi)
![Flask](https://img.shields.io/badge/-Flask-05122A?style=flat&logo=flask)
![Hibernate](https://img.shields.io/badge/-Hibernate-05122A?style=flat&logo=hibernate)
![Java](https://img.shields.io/badge/-Java-05122A?style=flat&logo=java)
![JPA](https://img.shields.io/badge/-JPA-05122A?style=flat&logo=jpa)
![Maven](https://img.shields.io/badge/-Maven-05122A?style=flat&logo=apache-maven)
![Microservices](https://img.shields.io/badge/-Microservices-05122A?style=flat&logo=microservices)
![MySQL](https://img.shields.io/badge/-MySQL-05122A?style=flat&logo=mysql)
![Oracle Database](https://img.shields.io/badge/-Oracle%20Database-05122A?style=flat&logo=oracle)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-05122A?style=flat&logo=postgresql)
![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)
![Redis](https://img.shields.io/badge/-Redis-05122A?style=flat&logo=redis)
![Spring Framework](https://img.shields.io/badge/-Spring%20Framework-05122A?style=flat&logo=spring)
![SQL](https://img.shields.io/badge/-SQL-05122A?style=flat&logo=sql)

### DevOps
![AWS](https://img.shields.io/badge/-AWS-05122A?style=flat&logo=amazon-aws)
![Docker](https://img.shields.io/badge/-Docker-05122A?style=flat&logo=docker)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-05122A?style=flat&logo=github-actions)
![Kafka](https://img.shields.io/badge/-Kafka-05122A?style=flat&logo=apache-kafka)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-05122A?style=flat&logo=kubernetes)
![Linux](https://img.shields.io/badge/-Linux-05122A?style=flat&logo=linux)
![Nginx](https://img.shields.io/badge/-Nginx-05122A?style=flat&logo=nginx)
![Shell Script](https://img.shields.io/badge/-Shell%20Script-05122A?style=flat&logo=gnu-bash)

### Frontend
![Bootstrap](https://img.shields.io/badge/-Bootstrap-05122A?style=flat&logo=bootstrap)
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=css3)
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=html5)
![JavaScript](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript)
![React](https://img.shields.io/badge/-React-05122A?style=flat&logo=react)
![TypeScript](https://img.shields.io/badge/-TypeScript-05122A?style=flat&logo=typescript)

### Others
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)
![JSON](https://img.shields.io/badge/-JSON-05122A?style=flat&logo=json)
![JUnit](https://img.shields.io/badge/-JUnit-05122A?style=flat&logo=junit)
![JWT](https://img.shields.io/badge/-JWT-05122A?style=flat&logo=json-web-tokens)
![Kanban](https://img.shields.io/badge/-Kanban-05122A?style=flat&logo=kanban)
![Mockito](https://img.shields.io/badge/-Mockito-05122A?style=flat&logo=mockito)
![Scrum](https://img.shields.io/badge/-Scrum-05122A?style=flat&logo=scrum)
![SQLite](https://img.shields.io/badge/-SQLite-05122A?style=flat&logo=sqlite)
![XML](https://img.shields.io/badge/-XML-05122A?style=flat&logo=xml)


### 📭 Entre em contato comigo! 

<div>
<a href = "mailto:rrenanrds@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/renanrodolfo/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
</div>    