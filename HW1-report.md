# HW 1 - CS 625, Spring 2025
Parth Patel
Due: January 26, 2025

## Git, GitHub

* <em> What is the URL of the GitHub repo that you created in your personal account? </em>
  
My personal GitHub repo for this assignment is located at: https://github.com/ppate010/CS625

* <em> What is pull vs clone in GitHub? </em>
  
Clone: Cloning a repository means creating a local copy of a remote repository on your local computer. It will download all files and commits from the remote to your local computer. 

Pull: Pulling is used when your local repo is setup it will fetch and merge changes from the remote repository into your local branch. 

* You have committed a change on your local machine/remote. However, you want to undo the changes committed. How would you do that?

If you committed a change and would like to undo the change committed the command to use would be git revert <commit-hash>.

## Markdown

 <em> Create a bulleted list with at least 3 items </em>
 
* Pokemon
* Yugioh
* Digimon


 <em> Write a single paragraph that demonstrates the use of italics, bold, bold italics, code, and includes a link. The paragraph must explain your favorite Olympic sport/game, the country that won the most number of olympic GOLD medals (Summer) in your favorite sport in 2020 (Japan) and 2024 (France). You are free to include more information. </em> 

My favorite Olympic sport is ***Judo*** which I personally find super exciting to watch. In 2020, ***<em>Japan</em>*** received the most gold medal in Judo but in 2024 ***<em>France</em>*** took the lead and claimed the most gold medals. For more information, visit the [official Olympic website](https://www.olympics.com/)

### My Favorite Olympic Sport (Judo)

<img src = "https://img.olympics.com/images/image/private/t_s_pog_staticContent_hero_xl_2x/f_auto/v1669453692/primary/swiwzmpywuhbh76it0bs" alt="Judo" width="300" />

## Tableau

![Least Medals by Continent](LeastMedal.png)

## Google Colab

*What is the URL of your Google Colab notebook?

[parth google Colab notebook](https://colab.research.google.com/drive/1v6o6HRT7CPeAqs-dCka4zpjuKlGUvSko?usp=sharing)

## Python/Seaborn
![scatter penguins](scatter_penguins.png)

* This figure shows the relationship between penguin bill length and bill depth across all species.

![bar penguins](bar_penguins.png)

* This figures compares the average body mass in grams across different penguin species to  different sex.

* What happened when you removed the outer parentheses from the code? Why?

Without the parentheses, nothing is displayed. Python doesn't treat the chain of method call as a single expression the code becomes separate statement rather than one final bar graph to render.

## Observable and Vega-Lite

What happens when you replace `markCircle()` with `markSquare()`?

* Changes every data point from a circle to a square

What happens when you replace `markCircle()` with `markPoint()`?

* Changes every data point from a circle to a point

What change do you need to make to swap the x and y axes on the scatterplot?

* To swap the axes switch the field reference MIles_per_Gallon  to vl.y() and Horespower to vl.x()

![VegaLite](VegaLite.png)

Why do you think this chart is the result of this code change?

* By removing Origin from the y-axis the chart is no longer groouped otgether by category and groups all data together into one bar.

## References

* [Markdown Basic Syntax](https://markdownguide.offshoot.io/basic-syntax/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Vega-Lite Document](https://observablehq.com/@observablehq/vega-lite)
* [Olympics](https://www.olympics.com/)
