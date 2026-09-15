# My 3 "ah-ha" moments about GitHub and Markdown

**GitHub** and **Markdown** are two topics that I was eager to revisit and dive deeper into.
I have limited experience with both.

**Two goals for this class:**

> Be able to, from memory, use `Markdown` at any time.
> 
> I would like to have a reason to continue using `GitHub` after this class.

The first week and a half has already given me a few learnings that will stick with me.
They may be minor but they have made an "ah ha" moment for me, which has made it stick with me more.

## The GitHub Preview Tab

Perhaps one of the most basic functions in GitHub: using the **preview tab** vs the
**commit function** was a big ah-ha moment for me. Now, as I look back on my
first assignment, it's embarrassing seeing the 20+ unnecessary commits.

I've realized that:

1. Commits should not be used as *saving* or *viewing* the change.
1. It should be used for *meaningful* changes.
1. Having the unecessary amount of commits would also be bad practice when you're working in a team.

> [!NOTE]
> I usually would not use the **ordered list** in the above list but I wanted to try both kind of lists.

## It's all about the 1s

My next ah-ha learning moment was the approach to **ordered lists**. The fact that you do not need
to number them 1, 2, 3, 4, etc. is an important thing to know. I remember seeing Markdown in the past
that had all 1s and I was really confused.

***Such a simple piece of learning that clears up confusion.***

This got me researching about what the best practice was. From from what I found, a best practice (or maybe just a "common" practice)
is to use all 1s. By using all 1s, if your developer needed to add a step, you don't have to redo the numbers.
Another benefit is the log change will not look like you changed 15 lines, when you were just trying to swap *one* number.

## Docs as Code: Separating content and Presentation

I was introduced to this concept before but hearing it again, and learning more about Markdown
with that concept in mind, puts things into perspective. 

For example:

- Using all 1s is reinforcing that idea. The **1.** is an identifier that a structure is being used.
- So the 2, 3, 4 isn't needed. The 1, 2, 3, 4 are actually more of the "presentation" vs "content".

## Bonus takeaway: I love the block coding

Probably my favorite Markdown code has been using the back ticks for code. Whether it's inline code using a
backtick for words like `HTML` and `CSS` or if it's a true block of code where you use code fencing:

```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Lorem Ipsum - All the facts - Lipsum generator</title>
<meta name="keywords" content="Lorem Ipsum, Lipsum, Lorem, Ipsum, Text, Generate, Generator, Facts, Information, What, Why, Where, Dummy Text, Typesetting, Printing, de Finibus, Bonorum et Malorum, de Finibus Bonorum et Malorum, Extremes of Good and Evil, Cicero, Latin, Garbled, Scrambled, Lorem ipsum dolor sit amet, dolor, sit amet, consectetur, adipiscing, elit, sed, eiusmod, tempor, incididunt" />
<meta name="description" content="Reference site about Lorem Ipsum, giving information on its origins, as well as a random Lipsum generator." />
<meta name="viewport" content="width=device-width,initial-scale=1.0" />
<meta http-equiv="content-type" content="text/html; charset=utf-8" />
<!-- PLACE THIS SCRIPT INSIDE OF YOUR HEAD TAGS -->
<script data-cfasync="false" type="text/javascript">
....
</script>
```
