# Lambda School Code Review Checklist

Code review is the time to catch issues and help students who don't understand concepts from the day or week. A thorough code review may take between 90-120 minutes, but you can do a condensed code review in about 30 minutes. Instructors, TAs, or peer mentors will use the code review as an opportunity to push and challenge you technically. While you should feel free to ask questions, you should also be ready to explain and defend your code.

## Part I - Review Projects

Review each project, including assignments, personal projects, or Sprint Challenges since the last code review. At a minimum, review the code for the following:

1. Each project is pushed to GitHub with clear, detailed commit messages.
2. Each project is feature complete and works as expected.
3. There are no exceptions or warnings.
4. Code follows consistent naming conventions, language idioms, and style.
5. Code is written by the student.

## Part II - Review Objectives

Objectives are written in our 'Student can...' format, and reflect the skills the student will have demonstrated in their project, assignment, or sprint challenge. Using the student's tracker, review each competency or objective in each sample of code, and determine a rating (0-3) on each one.

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

If there are any specific needs or concerns with the student, share them with a TA or Instructor.

## Part VI - Student Pull Request Feedback Template

```markdown
## Great

## Requested Improvements

## Questions

## Rating: {1-3}

#### GitHub Contribution Graph
If you'd like your work to count on your GitHub contribution graph, do the following:

1. Create a new empty repository with the name of the project. If you
   want it to match, rename or delete your GitHub repo. Don't worry,
   your local copy will be safe.
2. Add the new empty repo as a new remote to your local git repository.
3. Push the project to the new repo.
4. Optionally, delete the old GitHub repo.
```

![Make a NEW repository](img/new-repository.png)
![CREATE the new repository](img/create-new-repository.png)
![COPY the new repository's URL](img/copy-new-repository.png)

```console
$  git clone https://github.com/mixelpixel/CSS-Preprocessor-LESS.git
   Cloning into 'CSS-Preprocessor-LESS'...
   warning: You appear to have cloned an empty repository.
$  cd CSS-Preprocessor-LESS/
$  ls -al
   total 0
   drwxr-xr-x   3 mixelpix  staff    96 Feb 25 22:15 .
   drwxr-xr-x+ 89 mixelpix  staff  2848 Feb 25 22:15 ..
   drwxr-xr-x  10 mixelpix  staff   320 Feb 25 22:15 .git  <------- BINGO!
```
