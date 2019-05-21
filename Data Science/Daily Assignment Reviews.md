# DS Daily Assignment Code Review Guide

## FAQs
### Why?
Daily Assignment Code Reviews (DACRs) are the time to catch issues and help students who don't understand concepts from a given module. A thorough, instructive code review should take roughly 15 minutes. [1] Code Reviews represent a great opportunity to push and challenge students technically. They also represent a great opportunity to support and help students ahead of the Sprint Challenge. 

### Ok. But I haven't seen this material in <= 20 weeks...
That's alright! Part of the benefit of being a PM is that revisiting the material once more affords you an opportunity to deepen your understanding. Moreover, that material has probably been iterated _to your benefit_. You will also be receiving Solution Notebooks every day for every Module. These will allow you to answer questions on topics you may not remember all that well. Touch base with your Unit Instructor to ensure a timely delivery of these as the curriculum changes may require them to be updated. While you are not allowed to share the entire notebook with students, you may use snippets of code to shape your feedback in a students pull request. 

### Great. Examples?
#### But of course! Here's an example Code Review commented on a student's Pull Request:  


![alt text](../Data%20Science/IMGs/Code%20Review%20Example.jpg "Here's one way to do it.")

#### You can see additional examples [here](../Data%20Science/IMGs).


## Suggested Workflow:

1. Students **must** submit their assignments by EOD (5:00PM PST) via Pull Request on Github (just like you used to!). [2]
2. The next day, you batch them together during the first hour activities and through lecture. Use the provided Solution Notebook as a reference. Bear in mind that this notebook is not the _only_ solution. Organize your open tabs/windows to allow for easy switching between the student's Pull Request, their Assignment Notebook, and the Solution Notebook [3]. Once you complete your first Review, use its _format_ as a template for the rest to speed things up. Comment all Code Reviews to students' Pull Requests _by Lunchtime_. That way they have feedback before they start the next Assignment. 
3. Rinse and repeat through **Thursday**. By standup, send _each_ of your students a 1-3 line DM with suggested review topics ahead of the Sprint Challenge the following morning. Base this on your latest code review, and Thursday's assignment if it has been submitted [4].  
4. For Sprint Challenges on Fridays, complete Code Reviews of Thursday's assignments while the students are working on the Sprint Challenge. When Students DM you their submission, begin evaluating them. Prioritize a quick Pass/Fail evaluation to make sure any students that require another attempt are able to start as soon as Lunchtime ends. Coordinate with the SL on this. 
5. During 1:1s, go over the SC with each student and evaluate it together. Use that time to verbally deliver personalized feedback on their code, overall submission, and performance during the Sprint. This also represents an opportunity to suggest additional practice during the weekend should you feel it's necessary. 
6. Should a student not demonstrate mastery in their re-attempt of the SC, alert your SL so they can begin coordinating the Flex process with Student Success. 

Set the expectations early on with your group, and enforce them regularly. They will fall into rythmn soon and then everything will be in lock-step, making your life **much easier**. :thumbsup:

#### Note: while this method has seen success and is recommended by previous PMs, you're free to experiment with your own! So long as you provide Daily Code reviews on a timely manner to your students. 



## Additional Considerations

The following are useful things to look out for while you're reviewing assignments and the SC:

1. Each Assignment / SC is pushed to GitHub with clear commit messages.
2. There are no error messages in the output cells of a notebook.
3. Code follows consistent naming conventions, language idioms, and style.
4. Code is written _by the student_.

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

### Extra Resource:
Lambda School's 2019 [Git branching workflow](https://youtu.be/cSoHP7WSsEg) will result in contributions reflected in your GitHub heatmap.

Latest update: 5/21/2019

***


:one: Especially if you batch them together to boost efficiency! See the examples and suggested workflow for more context.  
:two: The earlier the better! If you can start knocking out code reviews the same day, why not?  
:three: Remember that Github comments have nearly identical keyboard shortcuts to Slack (emojis, lists, emphasis, etc).
:four: Again, this depends on students being on top of their assignments to work. Be sure to enforce this early on! Also, this is a great time to send out Calendly links to your students to schedule 1:1's post SC
