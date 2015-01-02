Multiple Correspondence Analysis
========================================================

# 1. Optimal Scaling:
--------------------------------------------------------
### * Assign scales to the levels of categorical variables 
### * The projections of the vertices onto the 1st principal axis provide the optimal scaling 
### * The scale of the levels of the 1st variable is optimal in terms of distinguishing between the behavior of the levels of the 2nd variable in association to the 1st
### * The projections of the profile points onto the 1st principal axis provide the score of the profile
### * Assumptions: avg of optimal scaling = 0 ; variance = 1
### * Transformation of Optimal scaling: to fix 2 end-points (0=disagree, 100=strongly agree)

# 2. Row and Column Analyses
--------------------------------------------------------
### * Similarities:
+ The percentage of inertia accounted by the first principle axis is the same for both 
+ The dimension of the subsapce where the row point clouds and the column point clouds exist are the same
+ The dimension of the projection subspaces of row profiles and column profiles are the same
+ On the projection subspace - first principle axis, **Transform coordinates from:**

|Projection of Column Profiles | Projection of Column Vertices |
|------------------------------|-------------------------------|
|  **$\tilde{\omega}$**        | **$\sqrt{\frac{1}{p}}\tilde{\omega}$**|


|Projection of Row Profiles | Projection of Row Vertices    | 
|-------------------------- |-------------------------------| 
|           **$\tilde{v}$** |**$\sqrt{p}\tilde{v}$**        |

**$p$ = percentage of inertia the first priciple axis accounts for** $\leftarrow$ the $scaling factor^2$ on the first pinciple axis

### * Linear Algebra Background: 
+ Row Space and Column Space of Matrix
+ Change of Basis

? Total inertia: = the amount of dispersion in a set of profiles relative to the outer vertices
