# Model

### Feature

Dimensions in a data set are called features, predictors, or variables.The measurements used for the classiﬁcation, the mean value and the standard deviation in this case are known as features.

![](../.gitbook/assets/image%20%283%29.png)

### Training Data

In order to draw the straight line in Figure 1.2 we exploited the fact that we knew the labels \(class A or B\) for each point of the ﬁgure. The patterns \(feature vectors\) whose true class is known and which are used for the design of the classiﬁer are known as training patterns \(training feature vectors\).

### Epoch

A single iteration through the training dataset is called an epoch.

### Control Variable

A control variable is another factor in an experiment; it must be held constant. In the plant growth experiment, this may be factors like water and fertilizer levels.

If control variables aren’t kept constant, they could ruin your experiment. For example, you may conclude that plants grow optimally at 4 hours of light a day. However, if your plants are receiving different fertilizer levels, your experiment becomes invalid. As a researcher, you should identify any variables that may affect the outcome of your experiment and you must take steps to keep them constant \(“control” them\). If you do not, your experiment compromises internal validity, which is just another way of saying your experimental results will not be valid. When control variables run amok and aren’t controlled, they turn into confounding variables, which affect your results and ruin your experiment.

In statistics, controlling for a variable is the attempt to reduce the effect of confounding variables on an observational study. It means that when looking at the effect of one variable, all other variable predictors are held constant. In the design of experiments, treatments are applied to experimental units in the treatment group\(s\). In comparative experiments, members of the complementary group, the control group, receive either no treatment or a standard treatment.

### Model

A model is a relationship between variables.

Mathematical models can take many forms, including but not limited to

1. dynamical systems,
2. statistical models,
3. differential equations, or
4. Game theoretic models.

Mathematical modeling aims to describe the different aspects of the real world, their interaction, and their dynamics through mathematics.

Suppose you have a mathematical model and you want to understand its behavior. That is, you want to find a solution to the set of equations. The best is when you can use calculus, trigonometry, and other math techniques to write down the solution. Now you know absolutely how the model will behave under any circumstances. This is called the analytic solution, because you used analysis to figure it out. It is also referred to as a closed form solution.

But this tends to work only for simple models. For more complex models, the math becomes much too complicated. Then you turn to numerical methods of solving the equations, such as the Runge-Kutta method. For a differential equation that describes behavior over time, the numerical method starts with the initial values of the variables, and then uses the equations to figure out the changes in these variables over a very brief time period. Its only an approximation, but it can be a very good approximation under certain circumstances.

A computer must be used to perform the thousands of repetitive calculations involved. The result is a long list of numbers, not an equation. This long list of numbers can be used to drive an animated simulation, as we do with the models presented here.

There is also a middle ground between these two methods. There are many important non-linear equations for which it is not possible to find an analytic solution. However, there are techniques where you can find approximate analytic solutions that are close to the true solution, at least within a certain range. One such method is called the perturbation method. The advantage over a numerical solution is that you wind up with an equation \(instead of just a long list of numbers\) which you can gain some insight from.

### Model Simulation

A computer model refers to the algorithms and equations used to capture the behavior of the system being modeled. By contrast, a computer simulation refers to the actual running of the program that contains these equations or algorithms. Simulation, therefore, refers to the result of running a model. In other words, you would not "build a simulation". You would "build a model", and then either "run a model" or "run a simulation".

### Types of Model

#### Linear vs. Nonlinear Model

If all the operators in a mathematical model exhibit linearity, the resulting mathematical model is defined as linear. A model is considered to be nonlinear otherwise. The definition of linearity and non-linearity is dependent on context, and linear models may have nonlinear expressions in them. For example, in a statistical linear model, it is assumed that a relationship is linear in the parameters, but it may be nonlinear in the predictor variables. Similarly, a differential equation is said to be linear if it can be written with linear differential operators, but it can still have nonlinear expressions in it. In a mathematical programming model, if the objective functions and constraints are represented entirely by linear equations, then the model is regarded as a linear model. If one or more of the objective functions or constraints are represented with a nonlinear equation, then the model is known as a nonlinear model.

Nonlinearity, even in fairly simple systems, is often associated with phenomena such as chaos and irreversibility. Although there are exceptions, nonlinear systems and models tend to be more difficult to study than linear ones. A common approach to nonlinear problems is linearization, but this can be problematic if one is trying to study aspects such as irreversibility, which are strongly tied to nonlinearity.

####  Static vs. dynamic

A dynamic model accounts for time-dependent changes in the state of the system, while a static \(or steady-state\) model calculates the system in equilibrium, and thus is time-invariant. Dynamic models typically are represented by differential equations.

####  Explicit vs. implicit

If all of the input parameters of the overall model are known, and the output parameters can be calculated by a finite series of computations \(known as linear programming, not to be confused with linearity as described above\), the model is said to be explicit. But sometimes it is the output parameters which are known, and the corresponding inputs must be solved for by an iterative procedure, such as Newton's method \(if the model is linear\) or Broyden's method \(if non-linear\). For example, a jet engine's physical properties such as turbine and nozzle throat areas can be explicitly calculated given a design thermodynamic cycle \(air and fuel flow rates, pressures, and temperatures\) at a specific flight condition and power setting, but the engine's operating cycles at other flight conditions and power settings cannot be explicitly calculated from the constant physical properties.

Discrete vs. continuous: A discrete model treats objects as discrete, such as the particles in a molecular model or the states in a statistical model; while a continuous model represents the objects in a continuous manner, such as the velocity field of fluid in pipe flows, temperatures and stresses in a solid, and electric field that applies continuously over the entire model due to a point charge.

#### Deterministic vs. Probabilistic \(Stochastic\):

A deterministic model is one in which every set of variable states is uniquely determined by parameters in the model and by sets of previous states of these variables. Therefore, deterministic models perform the same way for a given set of initial conditions. Conversely, in a stochastic model, randomness is present, and variable states are not described by unique values, but rather by probability distributions.

#### Deductive, inductive, or floating:

A deductive model is a logical structure based on a theory. An inductive model arises from empirical findings and generalization from them. The floating model rests on neither theory nor observation, but is merely the invocation of expected structure. Application of mathematics in social sciences outside of economics has been criticized for unfounded models.\[2\] Application of catastrophe theory in science has been characterized as a floating model



