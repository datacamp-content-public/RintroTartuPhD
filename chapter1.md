---
  title: "Template Chapter 1"
  description: "This is a template chapter."
  v2: true

---
## Simple arithmetics

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: f44788f113



```

Simple arithmetic operations can be performed by typing in the expressions in the conventional way. For example:

- Addition , subtraction
                 34 + 87
                54 - 15
- Multiplication, division
          12*3
         545/5
- Power
      23^2
      2^5
- Combinations
   12 + 5*(45.6-43.1)^3

Suppose you need to calculate budget of a course you are organizing. 
The costs are: 
participants: 18 EUR for lunches and coffee breaks, 7EUR for course materials.
instructor: 320EUR for the flight ticket, 76 EUR per night at a hotel (2 nights needed)  and 50 EUR for other costs
Make some budget calculations by vaeying the number of participants 

`@instructions`
- Calculate the total catering and course material costs per participant
- Calculate the total costs for the instructor
- Calculate the total budget of the course with 20 participants
- Calculate the budget of the course with 15 participants and the course fee per participant, if the costs are divided equally between all

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`
```{r}
# Load datasets and packages here.

```
`@sample_code`
```{r}
# Costs per 1 participant
18 + 7
# Costs per instructor
320 + 2*76 + 50
# Budget with 20 participants

# Fee per participant with 15 participants
(320+ 2*76 +50 +  *(18+7))/

```
`@solution`
```{r}
# Costs per 1 participant
18 + 7
# Costs per instructor
320 + 2*76 + 50
# Budget with 20 participants
320+ 2*76 +50 +20*(18+7)
# Fee per participant with 15 participants
(320+ 2*76 +50 +15*(18+7))/15

```
`@sct`
```{r}
success_msg("Excellent! Now to the next steps")
```




