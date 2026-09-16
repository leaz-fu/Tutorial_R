# Tutorial_R

Welcome to the R Tutorial **TutorialR**. This package contains self-learning R tutorials developed for students in political science.

The aim of the package is to teach R to students with self-learning modules, so they can go through the material on their own computer at their own pace.

The examples in these tutorials are from political science, but no prior knowledge is needed to follow along.

There are quizzes and coding exercises included in the tutorials, which will be useful to check your progress.

## Installation

To start the course, please follow these steps:

1. **Download R** (https://cran.r-project.org/) and install it. Get the newest version that fits your operating system. You don't have to ever open R, just download it.

2. **Download RStudio** (https://posit.co/download/rstudio-desktop/) and install it. Again, get the newest version that fits your operating system.

3. **Open RStudio.**

4. **Install the package `devtools`**, which is needed to install the tutorial from GitHub. After opening RStudio, copy the following code into the console and hit enter. The installation may take a while, during which there may be a lot of red text in the console. Don't panic. This is normal. You might also be asked to update some packages if you already had R installed previously.

```r
install.packages("devtools")
```

5. **Install the tutorial** by running the following code in the same way:

```r
devtools::install_github("leaz-fu/Tutorial_R")
```

The installation may take a while. You may see some warnings or red text in the console. This does not necessarily mean that something went wrong.

## Start the tutorials

6. **Start the first lesson:**

```r
learnr::run_tutorial("1_Intro_R", "TutorialR")
```

7. **Start the second lesson:**

```r
learnr::run_tutorial("2_Visualizations", "TutorialR")
```

You can start the tutorials in any order, but it is recommended to begin with **1_Intro_R**.
