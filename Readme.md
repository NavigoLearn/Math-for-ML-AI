## Math for ML/AI roadmap

Prerequisites

* Precalculus
* Algebra I

Math for ML
* Calculus
	-  Calculus I - Calculus I forms the foundation for understanding changes and motion in machine learning models. It introduces key concepts like limits, which help understand how functions behave as they approach specific points, and derivatives, which are essential for understanding rates of change. In machine learning, derivatives play a crucial role in optimization algorithms, like gradient descent, used for training models. This part of calculus also covers the basics of integration, providing a way to aggregate or sum up quantities, which is useful in areas like probability and data analysis. Understanding the fundamentals of Calculus I is vital for grasping more complex concepts in machine learning and for effectively implementing and improving ML algorithms. 
		- [Calculus I khan academy](https://www.khanacademy.org/math/calculus-1)
        - [calculus I MIT course](https://www.youtube.com/watch?v=0euyDNGEiZ4&list=PLO1y6V1SXjjNSSOZvV3PcFu4B1S8nfXBM)
        - [The best calculus intuition on the internet](https://www.youtube.com/watch?v=WUvTyaaNkzM&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)
        - derivatives intuition -Derivatives are fundamental in machine learning for optimizing algorithms. They indicate how a function's output changes in response to variations in input, crucial for algorithms like gradient descent. By calculating derivatives, we can minimize a loss function, adjusting model parameters for better data fit. This process, especially in neural networks, involves backpropagation, which relies heavily on derivatives. Understanding derivatives is key for effective algorithm implementation and improvement in machine learning. 
          - [Derivatives explained by 3blue1brown](https://www.youtube.com/watch?v=9vKqVkMQHKk&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)
		- understanding what integrals are - Integrals are used in machine learning to aggregate or accumulate quantities, offering a way to sum up continuous data points or functions. This concept is important for calculating areas under curves, which in ML can relate to probabilities and distributions in statistics. Integrals also play a role in understanding the cumulative impact of small changes, crucial in algorithms that deal with continuous data. Mastery of integrals aids in grasping complex concepts in probability and data analysis within the machine learning field 
          - [Integrals explained by 3blue1brown](https://www.youtube.com/watch?v=rfG8ce4nNh0&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)
		- Derivatives
			- Why derivatives in machine learning
				- gradient descent - Derivatives are pivotal in gradient descent algorithms, which find the minimum of a function (often a loss function in ML models). By calculating the derivative, the algorithm determines the direction to adjust parameters to reduce the error. 
                  - [Gradient descent 2d](https://www.youtube.com/watch?v=sDv4f4s2SB8)
                  - [Gradient descent for neural networks](https://www.youtube.com/watch?v=IHZwWFHWa-w)
				- Best line fit - In regression models, derivatives help in finding the best line that fits the given data. This involves minimizing the difference (error) between the predicted values and the actual values. 
                  - [Best line fit explained](https://www.youtube.com/watch?v=PaFPbb66DxQ)
			- [Real life applications of derivatives](https://www.youtube.com/watch?v=PaFPbb66DxQ)
            - derivatives rules - There are certain basic rules about derivatives that you have to know. They result from the definition of a derivative. For example the derivative of a constant is 0.
                - [Derivatives basics rules](https://www.khanacademy.org/math/calculus-1/cs1-derivatives-definition-and-basic-rules/cs1-derivative-rules-constant-sum-difference-and-constant-multiple/v/derivative-properties-and-polynomial-derivatives) 
            - differentiation rules - There are certain rules you have to know when deriving functions. For example how you derive a product, division or addition of functions
                - [Basic differentiation rules](https://www.youtube.com/watch?v=IvLpN1G1Ncg)
            - chain rule - A technique for finding the derivative of composite functions. It is used in machine learning to calculate the derivative of a function composed of several functions, being critical to neural networks and backpropagation. 
                - [Chain rule explained](https://www.youtube.com/watch?v=YG15m2VwSjA)
			- Approximating with local linearity - Used in machine learning to approximate a function with a linear function, which is easier to work with. This is done by finding the tangent line to a point on the function, which is the derivative at that point. So in simpler words, approximating a function near a point
				- [Khan academy chapters](https://www.khanacademy.org/math/calculus-1/cs1-applications-of-derivatives/cs1-approximation-with-local-linearity/v/local-linearization-intro)
			- L'hopital rule - A method for evaluating limits of indeterminate forms, which are expressions that cannot be evaluated by substituting the limit value. It is used in machine learning to find the limit of a function, which is useful in optimization algorithms like gradient descent.
				- [3blue1brown L'hopital rule](https://www.youtube.com/watch?v=kfF40MiS7zA)
                - [Khan academy L'hopital rules](https://www.khanacademy.org/math/calculus-1/cs1-applications-of-derivatives/cs1-lhpitals-rule/v/introduction-to-l-hopital-s-rule)
			- Relative (local) extrema - A point on a function where the function's value is either greater or less than the values of the surrounding points. It is used in machine learning to find the minimum or maximum of a function, which is important in optimization algorithms like gradient descent.
				- [Khan academy section](https://www.khanacademy.org/math/calculus-1/cs1-analyzing-functions/cs1-relative-local-extrema/v/relative-minima-maxima)
			- Concavity - A measure of the curvature of a function, which is used in machine learning to find the inflection points of a function. These points are important in optimization algorithms like gradient descent.
				- [Khan academy explainers](https://www.khanacademy.org/math/calculus-1/cs1-analyzing-functions/cs1-concavity-and-inflection-points-intro/v/concavity-concave-upwards-and-concave-downwards-intervals)
			- Optimization problems derivatives - Optimization problems are used in machine learning to find the minimum or maximum of a function, which is important in optimization algorithms like gradient descent.
				- [Khan academy explainer section](https://www.khanacademy.org/math/calculus-1/cs1-analyzing-functions/cs1-solving-optimization-problems/v/minimizing-sum-of-squares)
        - Implicit differentiation -Implicit differentiation is a method used when variables in a function are intermixed and cannot be separated easily. It involves differentiating both sides of an equation with respect to an independent variable. This technique is useful in machine learning for handling complex relationships between variables, especially when standard differentiation rules are not directly applicable. It helps in understanding the effect of changes in one variable on another. 
          - [Khan academy implicit differentiation](https://www.khanacademy.org/math/calculus-1/cs1-derivatives-chain-rule-and-other-advanced-topics/cs1-implicit-differentiation/v/implicit-differentiation-1) 
          - [Professor dave explains](https://www.youtube.com/watch?v=M0SMSWM2oZA)
		- Integrals - Integrals in mathematics, particularly in the context of machine learning, are used for summing or accumulating quantities over an interval. They are essential for calculating areas under curves, which can represent probabilities and distributions in statistics, a key part of data analysis in ML. Integrals also aid in understanding the cumulative effects of continuous changes, crucial for handling continuous data and for algorithms involving probabilities and continuous optimization. Understanding integrals is vital for effective data analysis and model formulation in machine learning. 
			- [Integrals and fundamental theorem of calculus](https://www.youtube.com/watch?v=rfG8ce4nNh0)
			- Riemann sums
              - [Riemann sums khan academy section](https://www.khanacademy.org/math/calculus-1/cs1-integrals/cs1-approximation-with-riemann-sums/v/simple-riemann-approximation-using-rectangles)
              - [Riemann sums explained](https://www.youtube.com/watch?v=AkUa9Fkz2rw)
            - Definite integrals
              - [Khan academy definite integrals](https://www.khanacademy.org/math/calculus-1/cs1-integrals/cs1-defining-integrals-with-riemann-sums/v/riemann-sums-and-integrals) 
              - [Definite integrals explained](https://www.youtube.com/watch?v=b0RJkIBhfEM) 
		- Differential equations basics -Differential equations are equations that involve an unknown function and its derivatives. In the basics of differential equations, you learn how to solve equations that describe the rate of change of a quantity. These equations are fundamental in modeling various phenomena where the rate of change of one variable is directly dependent on other variables 
          - [Differential equations video](https://www.youtube.com/watch?v=6o7b9yyhH7k) 
	- Calculus II -Calculus II builds upon the foundations of Calculus I, focusing on advanced integration techniques, series, and sequences. It includes topics like integration by parts, partial fractions, and convergence of series. In machine learning, these concepts are essential for complex models, especially in probabilistic methods and continuous optimization. This knowledge is crucial for understanding and implementing more sophisticated ML algorithms. 
      - [Calculus II khan academy](https://www.khanacademy.org/math/calculus-2) 
      - [Calculus II playlist](https://www.youtube.com/watch?v=i4c8n4S-Sp0&list=PLHXZ9OQGMqxc4ySKTIW19TLrT91Ik9M4n)
      - Integration techniques - Integration techniques involve various methods to solve complex integrals. Key techniques include integration by parts, substitution, and partial fractions. These methods are useful in machine learning for solving problems related to areas under curves, probabilities, and in algorithms that require integration of functions. Understanding these techniques is important for dealing with continuous data and for certain optimization problems in ML. 
          - [Integration techniques playlist](https://www.youtube.com/watch?v=2N6A4ed8s58&list=PLWYuCHEwjSqI5HAhTqpEoTGhkiy6DTGoN) 
          - [Khan academy integration techniques](https://www.khanacademy.org/math/calculus-2/cs2-integration-techniques)
          - u substitution - A method for solving integrals by substituting a function with a variable u. It is used in machine learning to solve complex integrals, which are important in algorithms that deal with continuous data. 
              - [u substitution explained](https://www.youtube.com/watch?v=sci1pls4Lc8) 
              - [The idea behind u substitution](https://www.youtube.com/watch?v=3eWxzBbsS9o)
          - [trigonometric identities integration](https://www.youtube.com/watch?v=3pXALn2ovIE&t=0s)  
          - [alternative khan academy](https://www.khanacademy.org/math/calculus-2/cs2-integration-techniques/cs2-integrating-using-trigonometric-identities/v/using-trig-identity-to-use-u-substitution)
          - [trigonometric substitution](https://www.youtube.com/watch?v=ocgjfF2AboA)
          - [integration by parts](https://www.youtube.com/watch?v=zNU8iK8sGD0)
          - [improper integrals](https://www.youtube.com/watch?v=ND9cEdfCFr0)
      - Differential equations - Differential equations involve relationships between functions and their derivatives, expressing how a quantity changes over time or space. They are crucial in modeling dynamic systems, where the rate of change is key. In machine learning, differential equations are used for time-series analysis, dynamic modeling, and in advanced neural network architectures. Understanding these equations is essential for applying ML to real-world problems that involve temporal or spatial dynamics. 
        - [Differential equations Khan academy](https://www.khanacademy.org/math/calculus-2/cs2-differential-equations)
        - [Differential equations 3blue1Brown](https://www.youtube.com/watch?v=p_di4Zn4wz4&list=PLZHQObOWTQDNPOjrT6KVlfJuKtYTftqH6)
      - Applications of integrals
          - [Motion problems](https://www.khanacademy.org/math/calculus-2/cs2-applications-of-integrals/cs2-straight-line-motion-3/v/motion-problems-with-integrals)
          - [Non motion problems](https://www.khanacademy.org/math/calculus-2/cs2-applications-of-integrals/cs2-non-motion-applications-of-integrals/v/area-under-rate-net-change)
          - [Squares and triangles cross-sections](https://www.khanacademy.org/math/calculus-2/cs2-applications-of-integrals/cs2-volume-squares-and-rectangles-cross-sections/v/volume-with-cross-sections-intro)
          - [Triangles and semicircles](https://www.khanacademy.org/math/calculus-2/cs2-applications-of-integrals/cs2-volume-triangles-and-semicircles-cross-sections/v/volume-solid-semicircle-cross-section)
      - More on equations and coordinates 
          - Polar coordinates -Polar coordinates represent points in a plane using a radius and an angle, offering an alternative to the traditional Cartesian coordinate system. In machine learning, polar coordinates can be useful for data representation and feature engineering, particularly in problems where the data's orientation and distance from a central point are important. Understanding polar coordinates can aid in visualizing and analyzing data that naturally fits into circular or spiral patterns.  
            - [Polar coordinates explained](https://www.youtube.com/watch?v=jwLUapqnwkk)
          - [Parametric equations](https://www.youtube.com/watch?v=QaN_3TytT_U) 
          - [Calculating arc length](https://www.youtube.com/watch?v=PK7HZiFG_VI)
          - [Vector valued functions](https://www.youtube.com/watch?v=7fYDCUIvZnM)
          - [Planar motion problems](https://www.khanacademy.org/math/calculus-2/cs2-parametric-equations-polar-coordinates-and-vector-valued-functions/cs2-planar-motion/v/planar-motion-example-acceleration-vector)
	- Series -Series in mathematics refer to the sum of a sequence of numbers. In machine learning, series are important for understanding algorithms that involve summation over time or across data points, such as in time-series analysis or when dealing with sequential data. Grasping the concept of series, including convergence and divergence, is key for implementing and analyzing algorithms that aggregate information over sequences. 
		- [Khan academy module](https://www.khanacademy.org/math/calculus-2/cs2-series)
        - Convergent and divergent infinite series - 
          - [Convergent and divergent series](https://www.youtube.com/watch?v=L-JqHo4-W4k)
          - [Convergent and divergent series](https://www.khanacademy.org/math/calculus-2/cs2-series/cs2-convergent-and-divergent-infinite-series/v/convergent-and-divergent-sequences)
		- Infinite geometric series - Convergent and divergent infinite series refer to the behavior of series as the number of terms approaches infinity. A convergent series approaches a finite limit, while a divergent series does not settle to a finite value. In machine learning, understanding the nature of these series is important for algorithms that involve iterative processes or summations over large datasets. Knowing whether a series converges or diverges can impact the stability and efficiency of these algorithms. 
          - [Sum of infinite geometric series](https://www.youtube.com/watch?v=jxRqRLMliPc)
		- [n-th term test](https://www.youtube.com/watch?v=gLzrFgR_qaM)
		- [integral test](https://www.youtube.com/watch?v=f9SJz4-UaQQ)
		- [P series](https://www.youtube.com/watch?v=x621rtIwb_4)
		- [Direct comparison test](https://www.youtube.com/watch?v=oZtAgihok5s)
        - [Limit comparison test](https://www.youtube.com/watch?v=LBxYQ0TJxYM)
		- [Ratio test](https://www.youtube.com/watch?v=kkfILYpkJS8)
		- [Taylor and Maclaurin series](https://www.youtube.com/watch?v=3d6DsjIBzJ4)
		- [Lagrange error bound](https://www.khanacademy.org/math/calculus-2/cs2-series/cs2-lagrange-error-bound/v/error-or-remainder-of-a-taylor-polynomial-approximation)
		- [Power series](https://www.youtube.com/watch?v=OxVBT83x8oc)
	-  Calculus III ( multivariable calculus ) - Multivariable calculus extends the concepts of single-variable calculus to functions of several variables. It includes topics like partial derivatives, multiple integrals, and vector calculus. In machine learning, this area is crucial for dealing with high-dimensional data and for understanding how changes in multiple inputs simultaneously affect an output. Mastery of multivariable calculus is essential for advanced machine learning techniques such as optimization in high-dimensional spaces and modeling complex, multi-faceted systems.   
        - [Khan academy modules](https://www.khanacademy.org/math/multivariable-calculus)
      	- [Visualizing 3d graphs](https://www.youtube.com/watch?v=acdX4YamDtU)
        - [Parametric curves](https://www.youtube.com/watch?v=bb4bSCjlFAw)
        - [Parametric surfaces](https://www.youtube.com/watch?v=345SnWfahhY)
        - Vector fields - Vector fields represent the distribution of vectors in a multi-dimensional space, where each vector indicates a direction and magnitude at a point in that space. In machine learning, vector fields can be used to visualize and understand the behavior of gradients in optimization problems, like visualizing the direction of steepest descent in a loss landscape. They are also important in understanding dynamical systems and fluid dynamics models that are applicable in certain AI applications. 
          - [Vector fields explained](https://www.youtube.com/watch?v=2qxxd68fZng)
          - [Vector fields 3blue1brown](https://www.youtube.com/watch?v=rB83DpBJQsE)
        - [Transformations](https://www.youtube.com/watch?v=roRR6A3TozM)
        - Partial derivatives - Partial derivatives are used in multivariable calculus to measure how a function changes as one of its variables changes, holding the others constant. In machine learning, partial derivatives are crucial for gradient calculations in multivariate optimization problems, such as those encountered in training neural networks. They help in understanding the sensitivity of a function's output to changes in each input variable, which is key for fine-tuning model parameters.  
            - understanding partial derivatives
            - visualizing partial derivatives
            - gradient
            - Multivariable chain rule
            - Partial derivative of vector valued function
        - Divergence - https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/divergence-grant-videos/v/divergence-intuition-part-1
        - Curl 
        - 3d curls
        - Laplacian - https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/laplacian/v/laplacian-intuition
        - Jacobian
        - Minima and maxima in multivariable functions
        - Constrained optimization
        - Line integrals
        - Line integrals in vector fields
        - Double integrals
        - Triple integrals 
- How neural networks work - at this point ....
	- [Neural networks explained by 3blue1brown](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) 
- Probabilities
	- Probability basics explained
		- Addition of probabilities
		- Compound probability
		- Coin flipping probability
		- Probability of unfair coin
		- Probability of exactly 2 heads
	- More on probabilities
		- Generalizing with binomial coefficients
		- Dependent probability 
		- Permutations
		- Combinations
		- Conditional probability
		- Birthday problem
		- Random variables
		- Binomial distribution
		- Expected value
			- Expected value of binomial distribution
		- Poisson process
		- Law of large numbers  
- Statistics
    - The average
    - Population and sample mean
    - Variance
    - Standard deviation
    - Normal distribution
    - Central limit theorem
    - Standard error of the mean
    - Bernoulli distribution
    - Bayesian Statistics
    - Bayesian inference
    - Margin of error
    - Confidence intervals
    - Hypothesis testing and p-values
    - One-tailed and two-tailed tests
    - Regression analysis
    - Advanced regression
    - z-score
    - Correlation and covariance
    - sampling methods
- Linear algebra
  - Essence of linear algebra
  - Prerequisites recap
    - Matrices
    - Matrix multiplication
    - Inverse matrices
    - Solve system of equations
  - Basics of linear algebra
    - Vectors 
    - Linear combination and span
    - Linear dependence and independence
    - Linear subspaces
    - Basis of a subspace
    - Unit vectors 
    - Vector dot and cross products
    - Cauchy-Schwarz inequality
    - Vector triangle inequality
    - Angle between vectors
    - Matrices: Reduced row echelon form
    - Matrix vector products
    - Null space 
    - Column space
    - Dimension of a column space
  - More linear algebra concepts
    - Different understanding of functions
    - Vector transformations
    - Linear transformations 
      - Image of a subset under a transformation
      - Image of a transformation
      - Preimage of a set
      - Sums and scalar multiples of linear transformations
      - Linear transformation examples
    - Projections
    - Matrix product 
      - Matrix product associativity
      - Matrix product distributivity
    - Inverse of a function
    - Finding inverse function
    - Showing that inverse are linear
    - Method for determining matrix inverses
    - Determinants
      - 3*3 determinant
      - n*n determinant
      - duplicate row determinant
      - Transpose of a matrix
      - Determinant of transpose
    - Orthogonal complement 
    - rank of a matrix and transpose
    - dim of a matrix and orthogonal complement
    - Change of basis
    - The gram-schmidt process
    - Eigen values and eigenvectors
    - Diagonalization of a matrix
    - Singular value decomposition
    - Tensors and tensor operations
- Optimization theory course
  - [Course](https://www.youtube.com/watch?v=4_jiFQXPAsw&list=PLdkTDauaUnQpzuOCZyUUZc0lxf4-PXNR5)
- information theory course
  - [Course](https://www.youtube.com/watch?v=BCiZc0n6COY&list=PLruBu5BI5n4aFpG32iMbdWoRVAA-Vcso6)
- econometrics course
  - [Course](https://www.youtube.com/watch?v=M_5SLG7sUa0&list=PLwJRxp3blEvZyQBTTOMFRP_TDaSdly3gU)
- Beyond this roadmap 
  - (Mathematics for machine learning - Marc Peter Deisenroth)
  - AI roadmap
  - Machine learning roadmap
  - Deep learning roadmap
- (Math for ml - Marc Peter Deisenroth)
- Optimization theory
- information theory
- econometrics
