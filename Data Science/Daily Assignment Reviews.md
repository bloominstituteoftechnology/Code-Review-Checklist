# DS Daily Assignment Code Review Guide

## FAQ
### Why?
Daily Assignment Code Reviews (DACRs) are the time to catch issues and help students who don't understand concepts from a given module. A thorough, instructive code review should take roughly 15 minutes. [1] Especially if you batch them together and boost your efficiency! Code Reviews represents a great opportunity to push and challenge students technically. It also represents a great opportunity to support and help students who require it, ahead of the Sprint Challenge. 

### Ok. But I haven't seen this material in >= 20 weeks...
That's alright! Part of the benefit of being a PM is that revisiting the material once more affords you an opportunity to deepen your understanding. Moreover, that material has probably been iterated _to your benefit_. You will also be receiving Solution Notebooks every day for every Module. These will allow you to answer questions on topics you may not remember all that well. Touch base with your Unit Instructor to ensure a timely delivery of these as the curriculum changes may require them to be updated. While you are not allowed to share the entire notebook with students, you may use snippets of code to shape your feedback in a students pull request. 

### Examples?
But of course!



## Suggested Workflow
#### some context....

1. Students **must** submit their assignments sometime between the end of Project Time (3:45PM Lambda) and the start of class the following day (8:00AM Lambda) via Pull Request on Github (just like you used to!). [2]
2. 

Set this expectation early on with your group, and enforce it regularly. They will fall into rythmn soon and then everything will be in lock-step, making your life much easier. :thumbsup:

#### Note: while this method has seen success and is recommended by previous PMs, you're free to experiment with your own! So long as you provide Daily Code reviews on a timely manner to your students. 




## Part I - Review Assignments

Review each project, including assignments, personal projects, or Sprint Challenges since the last code review. At a minimum, review the code for the following:

1. Each project is pushed to GitHub with clear, detailed commit messages.
2. Each project is feature complete and works as expected.
3. There are no exceptions or warnings in your console or Chrome Developer Tools.
4. Code follows consistent naming conventions, language idioms, and style.
5. Code is written by the student.

## Part II - Review Objectives

Objectives from the Training Kit are written in our 'Student can...' format, and reflect the skills the student will have demonstrated in their project, assignment, or sprint challenge. Using the student's tracker, review each competency or objective in each sample of code, and determine a rating (0-3) on each one.

Ask to see examples of each objective in the project. Ask the student to explain the code and how it demonstrates their mastery.

#### Rating Scale

| Score | Description |
| :-- | :-- |
| 0       				| Not observable |
| 1       				| Does not understand, does not meet expectations |
| 2 <sup>*</sup>  | Understands with assistance, meets expectations |
| 3       				| Understands independently, exceeds expectations |

<sup>*</sup> `2` is the default score. A `3` should only be awarded when the student has demonstrably mastered the objective.

##### NOTE: Ratings are not grades, and there are no GPAs. Students and reviewers should come to a consensus rating to understand where the student excels, and where the student may need some extra attention or help.

## Part III - Review Past Objectives

Choose a handful of previous objectives to review or discuss. If the code review is happening in a peer mentoring setting, this will likely happen with one student reviewing another's code.

Focus on objectives where the student did not meet expectations. If the student has reviewed and improved, update the score. Otherwise, address the concerns in this step, or when making a plan.

## Part IV - Make a Plan

Make a plan. Focus on fixing deficiencies first, then focus on mastery, stretch goals, or other advanced work.

Plans should include videos, resources, or exercises the student will complete in order to improve their mastery.

## Part V - Address Any Additional Needs

If there are any specific needs or concerns with the student, share them with a PM or Instructor.

## Part VI - Student Pull Request Feedback Template

```markdown
## Great

## Requested Improvements

## Questions

## Rating: {1-3}

#### GitHub Contribution Graph
```

## Part VII - GitHub Contribution Graph

![Heat Map](img/contribution-graph-heat-map.png)

### UPDATE

We recommend against de-forking while in class - just so all the links submitted stay active. But, you don't really need to de-fork anything.

All the commit history lives in the `.git` folder in the local Git repo directory - you just need to get the project up to GitHub. This can be as simple as:

1. creating a new repo on GitHub,
2. giving it a unique name to help distinguish it in your GitHub repository list, and
3. pushing the project up to the new GitHub repository.

It might help to make a "Team" to keep the "active student" repositories separate from the ones pushed up for the heatmap.

Lambda School's 2019 [Git branching workflow](https://youtu.be/cSoHP7WSsEg) will result in contributions reflected in your GitHub heatmap.

Latest update: 2/8/2019

***


:one: Especially if you batch them together to boost efficiency! See the examples for more context.  
:two: The earlier the better! If you can start knocking out code reviews the same day, why not?
