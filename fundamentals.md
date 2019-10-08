# Coupling 

The degree of interdependency between modules.

*The 4 factors tha influence coupling*

- 1. type of connection
    - minimally connected
    - normally connected
    - pathologically connected
- 2. complefixy of interface
    - usually the number of parameters
- 3. type of information flow
    - data
    - control
    - hybrid
- 4. bining time
    - the later the better

*Common Environment Coupling*

Indirect coupling caused by shared data repo.

*De-Coupling*

- Make necessary API explicit
- standardization of connections
- buffers between modules
- location of common environment
    - means partitioning the common environment, so modules don't share
      common areas

# Cohesion

The degree of functional relatedeness of the elements of a module.

*The 7 levels of cohesion*

- 1. coincidental association: there is little or no constructive relationship among the elements of a module
- 2. logical association: same logical class of similar or related functions (e.g. the "formatting" module)
- 3. temporal association: all occurrences of all elements of the module occur within the same limited period of time
- 4. procedural association: elements of a common procedural unit (such as loop)
- 5. communicational association: all elements operate on the same input data set and/or produce the same output data
- 6. sequential association: the output from one element serve as input for the next processing element
- 7. functional association: every element of processing is an integral part of, and is essential to, the performance of a single function

*More on functional*

Some modules have simple purpose as viewed from the outside; they have a
single, simple function; they are highly cohesive. These are three ways of
saying essentially the same thing.

*Using English to figure out level of cohesion*

- functional: describe its operational fully in an imperative sentence of
  simple structure, usually with a single transitive verb and a specific
  non-plural object.

*Scores for each level of cohesion*

- 1. coincidental: 0
- 2. logical: 1
- 3. temporal: 3
- 4. procedural: 5
- 5. communicational: 7
- 6. sequential: 9
- 7. functional: 10
