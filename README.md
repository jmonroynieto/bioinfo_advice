Last updated 2022-04-06

Selected pieces of advice from [this tweet](https://twitter.com/nilshomer/status/1511586109658046474).
Advice that is trusted either by repetition or self-evidence is not attributed to the original authors.
Pull request accepted to keep it up to date: gh jmonroynieto/bioinfo_advice

#### Be scientific
- Remain skeptical.
- Positive and negative controls.
- Think about the question.
- "Think about project structure and reproducibility from day \[one\]" @jessenleon
- "Every finding is an artifact until proven otherwise" @thomasliuksiala.

#### Explore your data
- Visualize everything

#### Read and understand (as much as you can)
- Read the documentation.
- Read the tutorials.
- Read the papers.
- Read the logs.
- Read the code.
- Understand the theory of the tools you use \[enough to be able to be critical and competent\].
- "Check your assumptions and those of the methods you use" @MDMorgan_cam
- "Don't be afraid to ask questions and engage with others in the field. The more prospective \[*sic*\] about how others do things, the more you learn" @wessidepraxis

#### Document
- Write it down.
- Take notes
- Make memos.
- Explain.
- Comment your code.
- Log your activities, inquiries, and reading.
- Save your commands.
- Did you write that down?
- Fingerprint inputs.
- Write down everything about your datasets.
- Make it easy for future self to understand what you are doing.
- NO! You will NOT remember.
- Documenting code is also software development.
- Notes are your friends.
- Can you write more? Please?
- There better be a note open while you work.
- Write it down.
- Unwritten results are immaterial; they shall become inconsequential and will require rework. You have been warned.
- Take notes, please.
- Start with a README.md
- Just write it!

#### Technical
- First and foremost, learn string manipulation (sed, awk,)
- No special characters in names.
- Make scripts generic to be run on different machines.
- Use workflow languages (@Nextflow seems to be the favorite in this crowd...mine too).
- Back up your data.
- Make original data read-only.
- Set specific seeds to ensure reproducibility.
- Use reproducible environments (i.e. containers or conda environments).
- Write tests for your code/analyses.
- Don't trust any tool blindly. Not all limitations are documented.
- Learn a bit of sysadmin, and learn how to install things without privileges.
- GO categories are based on lab work that might not be conclusive (paraphrasis) @HansonM90
- "You don't have enough sanity checks, \[sic\] add more." @constantAmateur
- "Don't trust the sample manifests, \[sic\] genotype everything yourself." @constantAmateur 
- "An hour eyeballing raw data can save 10 hours of coding." @ppgardne
- "If you are doing work for someone else, make sure you get them to write a project summary and sample list before you do \[absolutely\] anything. This will preemptively solve a lot of problems." @mdziemann
- "Be a good accountant" @watsonhaigh \[i.e. Track your read counts\] "Then ask, is that what I expected" ibid. Cor: This also applies to samples/processes and other countable.


#### Coding A.K.A mental health
- git
	- small commits
- If something else is published and it works, start there.
- Beware of ordered data structures: They might start at 0 or 1. (Read the documentation).
- Think well before using `rm -rf`, `rename`, or `mv`.
- Write tests for your code. *So that you can trust basic functions*
- Become an expert in one language and barely competent in the other ones you use.
- Factors (numerical representation of categories) are a necessary danger.
- "Installing software, making sure it works, creating pipelines etc. isn't the stuff you do to get to the bioinformatics. It is the bioinformatics. Doing it well is time well-spent, even if it can be frustrating" @jgreener64 


#### Integrity
- Don't allow external pressure to turn you into a P-hacker.
- The perfect is the enemy of the good enough +  delivered.
- You don't become a bioinformatician because you code but because you analyze. It's okay not to write tools. (See: learn Nextflow)
- Say no regularly.

#### Carrer
- In academia, you are evaluated on the writing you produce; in other spaces, the quality of your code might be important.
- Your career should fit your life, not the other way around.
- If you want to make money get out of academia.
- "Lab work sucks when you are pregnant. if you want to start a family and want flexibility, join us on the dark side of tech!" @Jillianerowe
- "Have your ideas and work in the open. \[...\] Demonstrate how you think through problems. Repost to other publications. \[...\]" @jillianerowe
- "Find your superpower and exploit it mercilessly" @jillianerowe
- "Never let your employer take over your life. Always have an exit plan." @jillianerowe
- For further advice on motherhood, fair labor, and life/work balance, see other replies by @jillianerowe


#### Resources:
- Statistical rethinking (FREE) https://xcelab.net/rm/statistical-rethinking/
