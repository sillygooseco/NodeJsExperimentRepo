# Node.Js and Mongo Experiment Repo
This repo includes experiments and test code for the following

* node.js (v 14.15.1).
* mongoDB (v 4.4)
* ES5 to ES6+ migration
* Complex Data structures
* Microservices and Domain Driven Architecture
</br></br>

## Purpose

The main purpose of this exercise is to set up some groundwork, experiment, explore development methods, assess the viability of technologies and architectures for a large scale Open Public API 

**Working title : Project [Astrolabe](https://en.wikipedia.org/wiki/Astrolabe)**

That requires

1. Flexibility and Scalability 
2. Secure but Publically and freely accessible
3. Robustness against downtime
4. Data integrity, validation & certification, and trust is paramount (Blockchain is not an option)
5. Complex and loosely coupled data structures
6. Multiple overlapping data references both at the core and meta-data level
7. Ease of access and navigation 
8. Simple and visual flow of data relationships (for reference tracing and verification)
9. high information density for access by deep divers (research staff and academics)
10. A LOT MORE

The secondary goal is to acquire fluency on requisite technologies ( _starting from this README_ ) and to develop applications with native code and base frameworks with a minimum, preferably no, dependency on external libraries. Technologies required would include

1. Git Repos and Standards
2. Node JS
3. MongoDB 
4. Docker Containers and Orchestration
4. Experimenting with Domain-Driven architecture and
5. Micro-Services
 
Initially

_``All knowledge acquired through this experimentation will be combined for a large-scale freely accessible Public API project that's in the research and design phase. More information will be added down the line``_

</br></br>

## SCOPE

The Scope of this repo will initially include 

1. __Node.JS__
    * RESTFUL APIs (Security include JWT tokens and the like)
    * Web GUI (Ingesting the APIs and Creating Web interface)
    * CLI (this will be purely for exploration purposes *SO FAR*)
    * Unit Tests
    * Performance and Scalability 
    * Private Server / Cloud Deployment automation ( *Haven't decided yet*)
    * All initial code will be written in ``ES5`` and a file with ``ES6+`` will be subsequently added for comparison with notes

2. __Mongo DB__ 
    * Data Structures
    * Working with Large scale data sets
    * Complex and Multi-tiered relationships with loose coupling
    * Aggregation pipelines
    * Sharding and Replica Sets
    * Use of Atlas or other cloud NoSQL providers ( *Cost might be a factor here we'll see*)

3. __Combination__
    * Mongo DB with Node JS API
    * Experimentation with Microservices & DD Arch
    * API Documentation

4. __Containerization and deployment__

5. __Some Basic Linux__

  __The scope might change as We go along__

All work will be posted with Code, inline comments, and readme files
Scripts for Mongo DB will be posted as well so they can be replicated
Docker and Automation scripts will be posted as well 

_all link to be added as it comes along or in the readme of the project_

</br></br>

# Participation

All are welcome to participate with us on this repo, use it anyway they like, comment, raise issues, provide feedback, and help improve it.

Here are some branching and commenting standards
</br></br>

## Branching

The main branches will be. 

1. main (master branch)
2. develop (internal development)
3. publicdev (public development)

each project will have its own branch which will be deleted once the project is completed and merged into the main branch

the branching order for branching out will always be 

> main -> develop -> project branch 

the pull-request structure will follow that in reverse to prevent breaking anything and to facilitate anyone who would like to play around in this repo i.e.

> project branch -> develop -> main 

or

> xyz-branch -> public-develop -> develop -> main 

It's imperative that the branches are tested and do not break anything as the pull-requests happen. 
For all others who want to play around with the code, **branch out from ``develop`` or ``master`` but create pull-requests into ``public-dev``**. but in case you want to fork it, all the power to you.

__All public pull-requests to develop branch directly will be rejected__

_``disclaimer: This repo is purely for learning and experimentation include authentication and security, please modify it as you like for your own needs, we always recommend  that you use standard security libraries and practices.``_
</br></br>

## Comments

All code should include inline comments and should follow standard coding conventions without [code smells](https://en.wikipedia.org/wiki/Code_smell)

Do update the read me files.
</br></br>

## Versioning


Update versioning where applicable, with the standard [semantic versioning 2.0.0](https://semver.org/) or simply put

```
<version core> ::= <major> "." <minor> "." <patch>

<major> ::= <non-leading-zero numeric identifier>
<minor> ::= <non-leading-zero numeric identifier>
<patch> ::= <non-leading-zero numeric identifier>
```

For instance: 

| Description    | Example       | 
| -------------  |:-------------:| 
| Current Version| 2.5.0         | 
| patch Version  | 2.5.1         | 
| Minor Feature  | 2.6.0         | 
| Major Feature  | 3.0.0         | 

</br></br>

## Commits

All Commits messages will be suffixed by the purpose of the commit

| Prefix    | Description                                | Example                    | 
| --------- |:-------------------------------------------|:---------------------------| 
| feat      | Feature additions                          |``` git commit -m feat: added api end-point to accept batch customer address update requests```| 
| fix       | Fix to a problem or an error               |``` git commit -m fix: fixed "header cannot set" error on order end-point```| 
| perf      | performance, optimization, and refactoring |``` git commit -m perf: Improved data aggregation pipeline response time```|
| clean     | Code cleanups and other housekeeping       |``` git commit -m clean: renamed variables names to meaningful names, fixed spelling mistakes and indentations```|
| docs      | Comments, documentation and readme         |``` git commit -m docs: added inline comments on discount function and updated readme file```|
| revert    | Reverting code                             |``` git commit -m revert: reverted commit a422bsd to a777856,  order parts API crash after PR 12 merge  ```| 
| merge     | Branch mergers                             |``` git commit -m merge: merge branch master to develop  ```| 

</br></br>
Though merge and revert are mostly handled  by Git itself, it's a good idea to add a bit of extra information for the reasons and all merges should have comments. **no commits without comments**
</br></br>

# Contact and Social

If you are following this, hope you enjoy our journey. this will be documented. you can always follow us on our Instagram [@grimravenx25](https://www.instagram.com/grimravenx25/) code tips and some nice nom nom pics [@sillygoose.co](https://www.instagram.com/sillygoose.co/) for some cool graphics and other fun stuff.

you can always message me directly on my Instagram (the code profile not the silly one :P )

