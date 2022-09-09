---
layout: essay
type: essay
title: "Getting More Out of Your Questions"
# All dates must be 2022-08-31 format!
date: 2022-09-08
published: true
labels:
  - Learning
  - Smart Questions
---


## Asking Questions
When it comes to learning new things, asking questions is a proven way to learn new things. So, "Asking all questions is a good thing?" you might ask. Unfortunately, not all questions are created equally. This is especially true when asking questions online via things like Stack Overflow an online technical forum for programming. On this forum, you will see a wide variety of questions. Some questions are good and generate a desired answer by providing clear background information and context, shows that the question asker has done some research on it, but needs a little bit more clarification and the asker put time and effort to ask their question clearly and politely. This makes sense because the questions asker is essentially asking for a favor from the forum boards, so the asker should try their best to make the question easy and worthwhile to answer. A bad question on the other hand is often inconsiderate by providing very little information or just asking a question that has been asked a million times over on the forums. Considering the number of bad questions that exist on Stack Overflow, it is unfortunately evident that not everyone knows how to ask a good question.

## Smart Question
An example of a smart question would be this question <a href="https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array" target="_blank">here</a>. The question is asking why their program, that iterates through an array and sums the values if the value is greater than a number, is so much faster when the data is presorted compared to unsorted and the title is "Why is processing a sorted array faster than processing an unsorted array?" which is concise and applicable to the question. On the surface it seems quite strange because you would think that iterating through an array would take the same time regardless of the order of the data. The intrigue of the question adds to its value as a smart question because people generally don't want to answer the same boring question over and over again. The asker also provides their own theories as to why this might be the case. One being that it might be language specific or compiler black magic, so they try it again in Java instead of C++ and get a similar result. The asker put in effort in trying to find the solution. Because the author asked a smart question; they got an equally smart answer. The answer being a very well written explanation of branch prediction. After a quick Google search, I was able to find the explanation of branch prediction, but this question was asked 10 years ago, so maybe the information was not as available. Either way the, the question generated a lot of good answers, and this is most likely due to the question being a smart question.
<p>A snippet of code from the question on Stack Overflow</p>

```ruby    
// Test
    clock_t start = clock();
    long long sum = 0;
    for (unsigned i = 0; i < 100000; ++i)
    {
        for (unsigned c = 0; c < arraySize; ++c)
        {   // Primary loop
            if (data[c] >= 128)
                sum += data[c];
        }
    }
```


## Not So Smart Question
A classic archetype for a not so smart question is just copy pasting your homework problem and asking for a solution. An example of this type of question can be found <a href="https://stackoverflow.com/questions/35245296/calculating-an-average-with-an-array-in-java-homework" target="_blank">here</a>. This person has several basic computational problems in Java and is asking for a solution to find the average of a set of numbers. The asker just bluntly says they don't know how to find the average and does not show that they at least attempted the problem by showing their solution that does not work. It also does not help that the answer to this question could be found with a quick Google search. I understand that this question was asked by someone who is just getting into programming and that it is understandable to have questions that may seem simple to someone more practiced, but that does not change the fact that the information was already out there, and they couldn't be bothered to look for it. Because they asked such a low effort question, they get a low effort response as a result. The response being the two steps of finding the average in plain English. The question asker still does not know how to find the average of a set of numbers in Java and wasted the time of the answerer. All these combined makes this question a bad question. Also, if it is a homework assignment, why not just ask your teacher for help.
<p>Their attempt at the average</p>

```ruby
        int average = 0;                         Here
        for (int i = 0; i < nums.length; i++) {  |
            sum = sum + nums[i];                 |
        }
        System.out.println("Average value is " + average); and here.
```
