# Course project requirements, topics, and guidelines

Requirements for the course project consist of 3 parts:

1. Proposal (20%)
2. Progress report (20%)
3. Presentation (60%)

## Proposal (due Feb. 25th)
For this part, you must write a 2-page proposal explaining:
  - The topic of your project, including a basic description and any equations or algorithms that you will focus on
  - What references you plan to use (paper(s), textbook(s), etc.)
  - What the expected results of the project are.  This should include both the concepts that you will understand and explain, as well as (in most cases) code that you will write.

The main purpose of the proposal is to ensure that the topic is appropriate and the scope is neither too simple nor too extensive/difficult.  A list of suggested
topics is given below, but you may choose your own.  The only restriction is that you cannot use a topic for which you are already getting credit
in another course (such as directed research or thesis work).

## Progress report (due March 29th)
This is a written report of no more than 4 pages, meant to help ensure that you're making adequate progress on the project.
You should explain ideas that you have learned so far, and describe any modifications you've had to make to the original project plan and scope.
It's also a good idea to include some preliminary numerical results (since you have hopefully made at least a preliminary implementation
of any algorithms involved).

## Presentation (last week of class)
You will give a presentation to the class which should take 25 minutes, leaving 5 minutes for questions.  The objective of the presentation is to teach
the topic of your project to the other students in the course.  In most cases, you should include computational results from your own code as illustrations
or examples.



## Suggested topics
A course project could involve a deeper dive into almost any of the topics we cover in the course, or
a study of some related topic that we don't cover at all.  If you have something in mind but don't know
where to find resources on it, I can help you.  Here are a few examples.

- **Neural ODEs**: We can view a deep neural network as a discretization of some unknown differential equation. It then can make sense to use ODE solvers within the neural network.  One of the early papers (and the most well-known) is [here](https://proceedings.neurips.cc/paper/2018/hash/69386f6bb1dfed68692a24c8686939b9-Abstract.html).  [This recent review](https://doi.org/10.1016/j.dte.2025.100060) is more up-to-date and general.
- **Mixed-precision numerical methods**:  Single- and half-precision floating point operations are becoming more and more important in computing, but so far ODE solvers aren't really taking advantage of them.  Some very interesting theory is developed in [this paper](https://link.springer.com/article/10.1007/s10915-022-01801-2).  There are several other interesting papers that cite it.
- **Multiderivative methods**: See e.g. [this paper for an older more general discussion](https://link.springer.com/article/10.1007/s11075-009-9349-1) or [this one for a recent development of specialized methods](https://epubs.siam.org/doi/abs/10.1137/21M1403175).
- **Quantum computing algorithms for ODEs**: I don't know almost anything about this but it would be a great project topic!  There seems to be [quite a bit of work on the topic](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=quantum+algorithms+for+odes&btnG=).
- **ODE solvers in optimization**: Many optimization methods can be interpreted as the application of a numerical method to a differential equation.  You could start for instance with [this paper](https://proceedings.neurips.cc/paper/2017/file/bf62768ca46b6c3b5bea9515d1a1fc45-Paper.pdf).
- **General linear methods**: A good starting point is the [Acta Numerica review paper by Butcher](https://doi.org/10.1017/S0962492906220014).  You could focus on general ideas, or on a specific class of methods within the bigger set.
- **Control theory and step size selection**:  We touched on this in class but the theory goes much deeper.  See e.g. [this paper](https://www.sciencedirect.com/science/article/pii/S0168927405000954).
- **Patankar methods**: These are a special class of Runge-Kutta-like methods designed to maintain positivity.  Look at the work of Andreas Meister and his collaborators to start.
- **Differential equations coming from a particular application**: I won't try to make a list, but if you are interested in a specific application, that can also be an appropriate direction for a project.
