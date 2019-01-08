# README #

This reository is implemantation of clean code architecture 

### What is this repository for? ###

* This reository is implemantation of clean code architecture . Here i follow Domain driven design. For make the application loosely coupled and unit testable i ustilize interfaes and implement IOC container.  


### How do I get set up? ###

It has simple dependencies:

 - [Chi (Router)](https://github.com/go-chi/chi)
 - [Dep (Dependency management)](https://github.com/golang/dep)
 - [GORM (ORM library)](http://gorm.io)
 - [Mapper (Simple mapper)](github.com/devfeel/mapper)
 - [Viper(Go configuration)](https://github.com/spf13/viper)

As i use dep for dependancy management to install all dependancies navigate to code folder and run
```sh
dep ensure 
```
It will install all require dependancies.

To run the application

```sh
go build
```

Then

```sh
./go-clean-archi
```
### Contribution guidelines ###

Create a new branch from main branch. Then provide pull request to review and merge code.

