# Code Era v1.0

Simple spring boot application for providing basic algorithms and data structures coding questions with compiler facility.

## Getting Started

1) Clone this project into your local.
2) Create database in mysql with name 'CodeEra' [Make sure mysql running on 3306 port]
3) Create table question as

| questions | CREATE TABLE `questions` (
  `id` int(11) NOT NULL,
  `info` varchar(255) DEFAULT NULL,
  `input_test_case` varchar(255) DEFAULT NULL,
  `output_test_case` varchar(255) DEFAULT NULL,
  `question_name` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=MyISAM DEFAULT CHARSET=utf8 |

### Prerequisites
1) Spring
2) Maven
3) Mysql
4) Java 1.8

### Installing/Running the application

After cloning the project in you local repository. Simply go into the folder of springBootApplication.

execute on command line.

```
./mvnw springboot:run
```

## Running on browser

Once the spring boot application is up with no error. Just go to normal browser and execute:

```
localhost:8081/test
```

## Authors

* **Anuj Kumar Vishwakarma** - [Anuj Kumar Vishwakarma](https://github.com/anujvishwakarma)

## License

This project is open source. 
