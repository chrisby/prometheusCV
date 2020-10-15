## prometheusCV: The non-template for academic CVs in latex.
Here to make creating your CV not an eternal torment.

![alt text](https://github.com/chrisby/prometheusCV/blob/main/prometheus_header.png)

### Requirements
Install the [Cormorant Garamond](https://github.com/CatharsisFonts/Cormorant) font on your machine. Also, set your `texStudio` to compile with `XeLaTeX`.

### Usage
There are only 2 commands you'll need: `\datedsubsection` and `\datedsubsectionnarrow`. Their arguments are the same, they just differ in their spacing. The code that generated the first Education entry in the above screenshot is

```
\datedsubsection{\nth{8}-century BC -- present}
	{%
		School of the Gods, Greece}
	{%
		\textbf{Ph.D.}~in creating humanity}
	{%
	I am a \highlight{culture hero} ...}
 ```
 
 The best way to get started is just to check out the [main.tex](https://github.com/chrisby/prometheusCV/blob/main/main.tex) file. I tried keeping the class file `prometheus_cv.cls` extremely simple so you don't get lost in new unknown commands. You should be able to easily create a professinoal looking CV with your basic LaTeX skills.
