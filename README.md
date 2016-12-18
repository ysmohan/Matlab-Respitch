#
Introduction

MATLAB is a programming language used extensively for data analysis in science and engineering.Unlike other programming languages, MATLAB is primarily made for research activities. This means that there are certain functions that MATLAB performs really well. On top of this, coding in MATLAB is really simple.

In this chapter, we will learn to do two activities that every reseracher needs to perform at some point- data analysis and data visualisation- using MATLAB. In order to perform these activities, we will learn the following basics in MATLAB:

## Learning Objectives:

- Be Familiar with the MATLAB environment.
- Be able to write and run code from the command window.
- Be able to perform simple calculations on Vectors.
- Be able to plot graphs using the Plots tab.

<hr> </hr>

<h4> Contents:</h4>

The rest of this chapter is set out as follows-
<p><ul>
<li> <a href="#context"> Context </li>
<li> <a href="#bg"> Background </li>
<li> <a href="#ex"> Example </li>
<li> <a href="#TheMAT"> The MATLAB environment </li>
<li> <a href="#Challenge1"> Challenge #1 </a> </li>
<li> <a href="#MatnVec"> Matrices and Vectors </li>
<li> <a href="#Challenge2"> Challenge #2 </a> </li>
<li> <a href="#plot"> Plotting </li>
<li> <a href="#Challenge3"> Challenge #3 </a> </li>
<li> <a href="#Mast"> Master Challenge</a> </li>
<li> <a href="#Plen"> Plenary </a> </li>
</ul></p>

<hr> </hr>

<h2 id="context"> Context </h2>

### Pre-requisites

Prior to beginning this chapter, please ensure that you have MATLAB installed on your computer. Installation instructions can be found here: LINK.

<hr></hr>

<h2 id="bg"> Background </h2>

As mentioned earlier, MATLAB is a tool used extensively in research for data analysis. However, unlike other programming languages, MATLAB is primarily made for research activities. This means that there are certain functions that MATLAB performs really well. This also means that there are certain other functions that MATLAB doesn't very well. For example, while MATLAB is excellent at processing numbers, it does not do so well when it comes to letters. However, MATLAB does provide an environment where we can perform multiple functions that are required by researchers which makes it relevant and useful.

Coding in MATLAB is also really simple. MATLAB has a thriving online community as well as people paid specifically to work on developing applications and toolboxes. This means that whatever your needs are, there is probably a toolbox for you. And if you are unable to find a toolbox, someone has written the code you need.
If your needs are specific, then you can write your own code and have I mentioned coding in MATLAB is incredibly simple. This was one of the main reasons I began coding in MATLAB. In my lab, we had some pre-existing MATLAB code and I needed to write my own code as well to successfully complete my research. So armed with a set of YouTube videos and a dataset, I set off to try and wrangle meaningful results from my data.

<hr> </hr>
<h2 id="ex"> Example </h2>
Other researchers around the world have used MATLAB analysis and data visualisation. Some of you may have seen the climate spiral- a graph of spiralling temperatures from the late 1800s to now, showing an increase in global temperature. For those of you who haven't, you can find it here: LINK. The researchers in this s-study used MATLAB for data analysis and visualisation and here is what they had to say about it.
“ I use MATLAB for data analysis because it can handle the very large datasets produced in climate science. “ – Dr. Ed Hawkins
Without futher ado, let's begin our MATLAB journey.
<hr> </hr>

<h2 id="TheMAT"> The MATLAB environment </h2>

When opening the MATLAB environment, we will find the following tabs (See image below):

- The command window with the blinking cursor- this is where we type instructions to the computer <br>
```Try typing 2+3 in your command window. We can essentially use this part of MATLAB as a calculator.```
- The WorkSpace- where all our matrices and vectors live.
- The current directory- we can only access files in this folder. If we want to use files that are not in our current directory, we can change the current directory using the ```cd``` command followed by the location of the folder we want to change it to. For example if I want to change my working directory to a folder in C drive called 'MatExample', I would type in:

```cd 'C:\MatExample' ```

- We will also be using the PLOTS tab which can be found in the top left corner of the MATLAB environment.

![](Respitch.png)

<h3 id= "Challenge1"> Challenge #1 </h3>

<pre> <code>
% Create a folder called MasterChallenge folder on the desktop. Change your current working directory to the MasterChallenge folder.
</code></pre>

<hr> </hr>


<h2 id="MatnVec"> Matrices and Vectors</h2>

A matrix is the basic data structure in MATLAB. It has horizontal rows and vertical columns just like a spreadsheet. A matrix that has only one column or only one row is called a vector. In this sub-section, we are going to do some basic matrix and vector operations.


![](RowsandColumns.PNG)

We can simply add two matrices or vectors by using the ```+``` sign or subtract them using the ```-``` sign. To multiply and divide we use ```.*``` and ```./```. We use the ```.``` terminology to make sure the operation we are performing applies to each individual element in our matrix or vector.

##### Note: When performing operations such as addition, subtraction, multiplication or division on two matrices, then need to be of the same size.

<h3 id= "Challenge2"> Challenge #2 </h3>

<pre><code>% Copy and paste the following code into the command window.
X= [1:5];
Y= [1:2:10]; % We are making two vectors and calling them X and Y. These will appear in our workspace.

% Add the two vectors.
% Now multiply them.
</code></pre>

<hr> </hr>

<h2 id= "plot"> Plotting </h2>

We created two vectors, X and Y. We can plot them individually by clicking on the vector in the workspace, going to the plots tab and clicking plot.

![](plotting.png)

<h3 id= "Challenge3"> Challenge #3 </h3>

<pre><code>% Use the scatter plot option in the PLOTS tab to make a scatter plot of X and Y.
</code></pre>


You are now ready to do the [master challenge](https://ysmohan.gitbooks.io/matlab_respitch/content/masterchallenge.html).


