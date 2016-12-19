#
Introduction

MATLAB is a programming language used extensively for data analysis in science and engineering.Unlike other programming languages, MATLAB is primarily made for research activities. This means that there are certain functions that MATLAB performs really well. On top of this, coding in MATLAB is really simple.

In this chapter, we will learn to do two activities that every reseracher needs to perform at some point — data analysis and data visualisation — using MATLAB. In order to perform these activities, we will learn the following basics in MATLAB:

## Learning Objectives:

- Be Familiar with the MATLAB environment.
- Be able to write and run code from the command window.
- Be able to perform simple calculations on Vectors.
- Be able to plot graphs using the Plots tab.

<hr> </hr>

<h4> Contents:</h4>

The rest of this chapter is set out as follows:
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

As mentioned earlier, MATLAB is a tool used extensively in research for data analysis. However, unlike other programming languages, MATLAB is primarily made for research activities. This means that there are certain functions that MATLAB performs really well. On the other hand, there are certain other tasks for which MATLAB is not very well suited. For example, while MATLAB is excellent at working with numbers, it does not do so well with processing text. However, MATLAB does provide an environment where we can perform multiple functions that are required by researchers which makes it relevant and useful.

Whatever your needs are, there is probably a tool already available in MATLAB that can do what you want.
MathWorks, the parent company of MATLAB, pays people specifically to work on developing applications and toolboxes.
If you are unable to find an official toolbox, there is also a thriving online MATLAB community.
Often someone will have already written the code you need, and made it available to use for free.

If your needs are specific, then you can write your own code, and let me say, coding in MATLAB is incredibly simple. This was one of the main reasons I began coding in MATLAB. In my lab, we had some pre-existing MATLAB code and I needed to write my own code as well to successfully complete my research. So, armed with a set of YouTube videos and a dataset, I set off to try and wrangle meaningful results from my data.

<hr> </hr>
<h2 id="ex"> Example </h2>
Other researchers around the world have used MATLAB analysis and data visualisation. Some of you may have seen the climate spiral — a graph of spiralling temperatures from the late 1800s to now, showing an increase in global temperature. For those of you who haven't, you can find it here: LINK. The researchers in this study used MATLAB for data analysis and visualisation and here is what they had to say about it:

“I use MATLAB for data analysis because it can handle the very large datasets produced in climate science.” – Dr. Ed Hawkins

Without futher ado, let's begin our MATLAB journey.

<h2 id="TheMAT"> The MATLAB environment </h2>

When opening the MATLAB environment, we will find the following tabs (See image below):

- The command window with the blinking cursor — this is where we type instructions to the computer <br>
```Try typing 2+3 in your command window. We can essentially use this part of MATLAB as a calculator.```
- The WorkSpace — where all our matrices and vectors live.
- The current directory – we can only access files in this folder. If we want to use files that are not in our current directory, we can change the current directory using the ```cd``` command followed by the location of the folder we want to change it to. For example if I want to change my working directory to a folder in C drive called 'MatExample', I would type in:

```cd 'C:\MatExample' ```

- We will also be using the PLOTS tab which can be found in the top left corner of the MATLAB environment.

![](Respitch.png)

<h3 id= "Challenge1"> Challenge #1 </h3>

<pre> <code>
% Create a folder called MasterChallenge folder on the desktop. Change your current working directory to the MasterChallenge folder.
</code></pre>

<hr> </hr>


<h2 id="MatnVec"> Matrices and Vectors</h2>

Matrices are the basic data structure in MATLAB.
A matrix is a rectangular table of numbers.
Any rectangular table of numbers can be thought of as a matrix;
one example is a spreadsheet of numerical data.

The reason matrices are so important is because they can be used to encode
information about a lot of different types of mathematical objects.
There are also rules which let us combine matrices together,
called matrix operations.
Matrix operations are analogous to arithmetic between numbers,
and are even still called addition and multiplication.

A matrix that has only one column or only one row is called a vector.
In this sub-section, we are going to do some basic matrix and vector operations.


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


#
Master Challenge

###Bad Science!

You are a budding climate scientist. You wanted to make great changes to the world using science. But academia being the cruel mistress she is broke you. You decided to turn to industry ("the lucrative, dark side of science"). However, poor judgement on your part followed by numerous bad
decisions left you working for the Big Bad — Evil Corp, aka E-Corp, headed by CEO Big Frump. Now E-Corp was not a good organisation. They had numerous dealings in
non-renewable energy sources and rumour has it that their scientists practiced "Bad Science". Their key motto was "Correlation = Causation" —
the simple principle that just because two events are related, one must have caused the other. Their arguments frequently involved repeatedly
yelling "Wrong" and their favorite explanation was "Because I said so."
Seduced by the ease of non-reason and misinformation, you've have indeed turned to the dark side.

### The Task
In the face of damning evidence suggesting that global temperatures are indeed rising, Big Frump himself has decided to put together a task
force. You are a part of this task force of like-minded immoral "scientists". Your task is to come up with the worst possible climate hypothesis. You have trawled through the internet and found numerous data sets which can be found here and you need to use your MATLAB skills to find a relationship between them. Through this bad science you will help E-Corp perpetrate hate and fear. You will help Big Frump rule the post-apocalyptic wasteland that will be his one lasting legacy.
Mwahahahaha!



<pre><code>
In order to successfully complete the challenge, you need to do the following:

Step 1: Download the 'masterchallenge.mat' and 'variabledesc.txt' files into the MasterChallenge folder you created in challenge 1. variabledesc.txt contains a description of all the vectors you found on the Internet.
Step 2: Ensure that the folder MasterChallenge is your current working directory. Double click on masterchallenge.mat. This should populate your workspace with the different vectors that you found on the internet.
Step 3: Using scatter plots, find any relationship between the variables in your workspace.
Step 4: Tweet your hypothesis and tag #ResBaz

</code></pre>

# Plenary

At the end of this chapter, you would have learned how to:

- Change the current directory
- Load vectors/matrices into the workspace.
- Use the command window to perform simple arithmetic operations on your matrices and vectors.
- Use the Plots tab to perform some experimental data analysis.

If you want to learn more about using MATLAB, you can find course material here:
There are also easy to understand videos here:


