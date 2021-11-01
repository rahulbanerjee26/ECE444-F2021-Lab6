Name: Rahul Banerjee

This app was created by following the turoial at https://github.com/mjhea0/flaskr-tdd

Deployed APP URL: https://dry-scrubland-14934.herokuapp.com/search/

## Unit Tests 
### Flask
[test_be.py](https://github.com/ECE444-2021Fall/project1-education-pathways-group-9-erlenmeyer/blob/Lab6-Rahul/carbon_be/src/test_be.py#L41) - From Line 41 

### React
[App.test.js](https://github.com/ECE444-2021Fall/project1-education-pathways-group-9-erlenmeyer/blob/Lab6-Rahul/carbon_fe/src/App.test.js)

[HomePage.test.js](https://github.com/ECE444-2021Fall/project1-education-pathways-group-9-erlenmeyer/blob/Lab6-Rahul/carbon_fe/src/components/Home/HomePage.test.js)

## Pros and Cons of TDD

### Pros
Following TDD will ensure that the code is virtually bug free since the developer has to spend time before writing any code to come up with edge cases. This also makes developing the actual feature easier since you know what to expect and test cases you need to pass. Less time will be spent of debugging and more time can be spent on actually developing the features. It also makes it easier to document the code. It also helps reduce Dead Code since any code which is written is to help pass an unit test.

### Cons 
It is a time consuming process. Before devloping any feature, a good amount of time has to spent thinking of edge cases. If the devloper writes the unit tests and the code to pass them, it might introduce bias since the developer might have forgotten an edge case. No program can be bug-free, although TDD reduces the chances of bugs it can not guarantee bug-free code. Before updating any feature, the corresponsing unit-test will have to be updated. This might lead to higher development times when making an important bug-fix or updating some feature.