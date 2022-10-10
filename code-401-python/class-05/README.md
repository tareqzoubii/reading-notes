## Read5

### What fixture are?
##### Fixtures define the steps and data that constitute the arrange phase of a test. 
# -------------
### What are fixture in PYTEST?
##### In pytest, they are functions you define that serve this purpose.
# -------------
### How to implement xunit-style set-up?
##### The xunit-style functions are integrated with the fixture mechanism and obey the proper scope rules of fixtures involved in the call.
# -------------
### Is Error means the prgram failed?
##### When a test is marked as having an error, it doesn’t mean the test failed, though. It just means the test couldn’t even be attempted because one of the things it depends on had a problem.
# -------------
### What is the best way to test data?
##### the best way to do test is by loading the data in a fixture for use by tests. This makes use of the automatic caching mechanisms of pytest.
# -------------
### What is Recursive Functions in Python ?
##### A recursive function is a function defined in terms of itself via self-referential expressions, this means that the function will continue to call itself and repeat its behavior until some condition is met to return a result.
# ------------
### What is the parts to share a common structure ?
##### 1: Base Case
##### 2: Recursive Case
# ------------
### Give an Example of base case?
> ! = n x (n−1)! 
> n! = n x (n−1) x (n−2)!
> n! = n x (n−1) x (n−2) x (n−3)!
> n! = n x (n−1) x (n−2) x (n−3) ⋅⋅⋅⋅ x 3!
> n! = n x (n−1) x (n−2) x (n−3) ⋅⋅⋅⋅ x 3 x 2!
> n! = n x (n−1) x (n−2) x (n−3) ⋅⋅⋅⋅ x 3 x 2 x 1!
#####  it's equals 1
# ------------
### Give an Example of recursive case?
> n! = n x (n−1) x (n−2) x (n−3) ⋅⋅⋅⋅ x 3 x 2 x 1
> n! = n x (n−1)!