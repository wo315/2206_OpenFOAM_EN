# English

```{warning}
keep modifing
```

## 2206 Introduction to CFD based on OpenFOAM®

## Introduction

> The use of computational fluid dynamics (CFD) theory, combined with modern computer
hardware and programming languages (C++, Fortran), to numerically simulate prevalent
natural phenomena such as flow and heat transfer, has become an obvious science.
Therefore, many students also want to master CFD theory better to serve their research and
production work. However, due to the difficulty of CFD theory, it is difficult to understand
the true meaning of it using commercial software, and the cost of commercial software
copyright is too expensive for the average individual user to afford, until the emergence of
OpenFOAM software, which was developed by Imperial College in the last century on the
Linux platform using the modern C++ language, and open source in the new millennium, and has
been derived from many versions. Therefore, users can solve practical problems through
OpenFOAM only if they have a good theoretical foundation, understand the Linux operating
system, and master the basic C++ syntax. Through self-learning, the learning curve is steeper,
and the time cost is larger, which can easily lead from getting started to giving up. The
purpose of this course is to solve the difficult problem of getting started with OpenFOAM in
**ten weeks**.

 
## The course is suitable for
1. First-year postgraduate or fourth-year university students who are interested in further work
in CFD.
2. First and second year Ph.D students who intend to work on solver development in the
future.
3. Those who are interested in further development of CFD related work


## Course start time
```{tip}
June 20, 2022, Peking time
```
## Course duration
```{tip}
10 weeks
```

## Course schedule
|date|time |remark|
|---|---|---|
|MON|`19:00-21:00`|teaching|
|WED|`19:00-21:00`|teaching|
|FRI|`19:00-21:00`|teaching|
|SUN|`19:00-21:00`|**TA**|


## Course contents
1. Pre-processing, geometry, and meshing
2. Discrete methods: finite volume method
3. Sparse matrix algorithms: introduction to direct/iterative method, conjugate gradient, and
multi grid method.
4. Post-processing, with a focus on python and ParaView.

Each unit of the course is designed along these four lines as much as possible, with a
progressive relationship between the units

%```{admonition} Here's my title
%:class: warning

%Here's my admonition content
%```

```{attention}
1. The course hardly involves compressible flow. The difference between compressible flow
and incompressible flow is huge, and the system of lectures and solution methods are also
different. So compressible flow just stays in the nomenclature stage.
2. For complex flow cases, this course does not cover them. For example: complex geometry,
complex mesh, complex physical scenario, complex boundary conditions
3. For turbulence, this course only calls on the existing turbulence models in OpenFOAM and
does not teach any turbulence-related theory.
```

## Course Syllabus


### Part 1. Linux

#### Linux OS installation
```markdown
Ubuntu 20.04 LTS
```
#### Linux file system
```console
.
├── bin -> usr/bin
├── boot
├── cdrom
├── dev
├── etc
├── home
├── lib -> usr/lib
├── lib32 -> usr/lib32
├── lib64 -> usr/lib64
├── libx32 -> usr/libx32
├── lost+found
├── media
├── mnt
├── opt
├── proc
├── root
├── run
├── sbin -> usr/sbin
├── snap
├── srv
├── swapfile
├── sys
├── tmp
├── usr
└── var

24 directories, 1 file

```
#### Linux command line: basic commands
```console
$ sudo
$ ls
$ copy
$ move
$ touch
$ mkdir
$ cat
$ less
$ more
$ tail
```
#### Linux command line: advanced commands
```console
$ find
$ grep
$ sed
$ awk
```
#### Shell scripts
```markdown
1. Sequence
2. Conditions
3. Loop
4. Function
```
----------------------
### Part II. Introduction to CFD with OpenFOAM

#### 1 Introduction

#### 2 Fluid mechanics governing equations and three types of boundary conditions

#### 3 Finite volume method: the diffusion equation

#### 4 Finite volume method: the advection-diffusion equation

#### 5 Finite volume method: the steady flow SIMPLE algorithm

#### 6 Finite volume method: the unsteady flow PISO algorithm


## References


```{bibliography} 
---
all:
---
```



## Course Fee

```{attention}
Original price: <strike> 1499 Euro</strike>

Current price: 899 Euro
```

## Contact
wechat：IAM315

email：yangwang206@whut.edu.cn

## Payment method



