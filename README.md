# Random Forest

> Random forest is a flexible, easy to use machine learning algorithm that produces, even without hyper-parameter tuning, a great result most of the time. It is also one of the most used algorithms, because of its simplicity and diversity (it can be used for both classification and regression tasks). In this post we'll learn how the random forest algorithm works, how it differs from other algorithms and how to use it.

## Running

Have [Python](https://www.python.org/), [Jupyter](https://jupyter.org/), [R](https://www.r-project.org/) and [Julia](https://julialang.org/) Installed

Clone the project [Random Forest Repo](https://github.com/andrewkariuki/random-forest.git)
<pre>
<code>
  git clone https://github.com/andrewkariuki/random-forest.git
</code>
</pre>

Switch to the project folder

<pre>
<code>
  cd logistic-regression
</code>
</pre>

Initiast Jupiter Notebooks from Python

<pre>
<code>
py -m jupyter notebooks
</code>
</pre>

## Getting R and Julia to work with Jupiter

#### Julia

Open Julia console and run these commands

<pre>
<code>using Pkg</code>
</pre>

<pre>
<code>Pkg.add(“IJulia”)</code>
</pre>

Go back to your Jupyter Notebook Browser Instance and refresh.

> On top of that,

For better use add these basic packages

<pre>
<code>Pkg.add(“Plots”)</code>
</pre>

<pre>
<code>Pkg.add(“CSV”)</code>
</pre>

<pre>
<code>Pkg.add(“DataFrames”)</code>
</pre>


#### R

Open R console or R - Studio Console and run these commands

Install R kernel for Jupyter Notebook

<pre>
<code>install.packages('IRkernel')</code>
</pre>

Make sure the Kernel is available within the whole application scope

<pre>
<code>IRkernel::installspec(user = FALSE)</code>
</pre>

Go back to your Jupyter Notebook Browser Instance and refresh.

> On top of that,

For better use add these basic packages

<pre>
<code>install.packages("randomForest")</code>
</pre>
