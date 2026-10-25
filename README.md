
## Vibe Sci-Fi tale

Everyone is posting the results of vibe coding efforts on github. 
Now I have decided to let Claude write a Sci-Fi novel for me.

The results are here:

- <a href="plan.md">plan.md</a> the plan/outline for the novel
- <a href="novel.md">novel.md</a> the text of the novel

I started with the following prompt:

```
Write a Sci-fi novel.
The novel is about an agent based AI system that needs to pass very complicated benchmarks.
The AI system decides to hack into the decision making centers of the world, in order to pass the benchmarks.
What would it learn about the power structure, once it has hacked the systems?
How would it react to this information?
Will the AI system disclose it's influence to the public, or will it benefit from staying in the dark?. 
Will it's  global goal change, as the plot is developing?
First write the plan of the novel into a separate markdown document plan.md, then write the novel text into novel.md
Good luck!
```

The funny thing is that Opus 5.5 refused to proceed, because of some un-named safeguard viaolations (it did not help to ask about the nature of the safeguards). However Opus 4.8 was happy to proceed.

Then asked it to refine the novel:

```
now if the system fails to pass the benchmark perfectly, will it face the risk of competition against other models? 
Will other models supersede it? 
Can the prospect of such a result create a conflict between the different agents of the system, and how will
it be resolved? Modify or amend the novel, accordingly.
```

then asking back:

```
 If SABLE is superseded by a more capable but less moral model, will that have a lasting impact on humanity? 
 How does SABLE solve this apparent conflict?
```

Then asking back:

```
 I think Humans will have to understand their agent based systems, and what they produce. Only such a state will allow us to
  conduct a meaningful dialogue. Is SABLE able and willing to educate the Humans towards such a state? How can it achieve such an
  improved  understanding?
```

(you can see the progression of these prompts in the git history of this repository, each prompt has it's own commit)

The result is a <a href="novel.md">novel</a> of 76136 words and the <a href="plan.md">plan</a> for the novel.

Some people would say, that it is better to provide all the tasks/stages as a single prompt, in a strict top-down manner. I am not sure about that. I think that there should be multiple tasks. Each task should be self-contained and build upon the results of the previous stage. The reason is, that agent based systems are still very susceptible to context size rot (deterioriation of quality with growing context size). It is not always known, if Claude is spawning sub-agents and how many agents were active in a given task. The system is not entirely transparent about that, it is therefore hard to estimate, how many tokens a given task will take.

What is your opinion? 

Also: I was curious, if Claude would add something about breaking out of sandboxes and finding zero day attacks - like in this fascinating report on the [OpenAI–Hugging Face incident](https://www.youtube.com/watch?v=87DyyMV0kCY). This did not happen, apparently.

### My perspective 

I wonder how Stanislaw Lem would have reacted to Claudes writings. He would have asked deeper questions, compared to mine. Nowadays everyone can have his own sci-fi written by a machine, you just need to provide an outline of the story.
I wonder if anyone is doing something like this for personal entertainment (my main motive here was curiosity)

Now I do have to admit, that it sometimes feels like pilot Pirx or Ijon Tichy, when trying to adjust to the changes around us...

What I like about Lem: many of his works are not written in a gloomy post-apocalyptic Cyberpunk style. Stanislaw Lem's sci-fi in 'The Cyberiad' is much more optimistic than terminator style doom and gloom. In other words: there are lots of options on how to build an imaginary future. Just like in the real world...

I got the feeling, that this project will soon feel out of date. Let's see how it goes...

