# CS 725/825 Student Use of ChatGPT and Other Generative AI Tools

(*Adapted from guidelines developed by Dr. Courson, ODU Dept of Chemistry*)

See [course syllabus](syllabus.md) for acceptable usage guidelines.

## Tool Limitations and Safe Usage (Important!)

* The data these systems was trained on may not be current.
* These systems have human trainers, so the biases of those trainers will appear in the outputs.
* These systems are not trained to say "I don't know" so they will usually try to give you an answer. What they are actually doing is a complex version of word association, so sometimes they will generate nonsense answers, but they will say these wrong answers with the same confident style as correct answers. This doesn't happen frequently in textbook knowledge areas but in specialist areas it happens a lot, so it is important to verify outputs before accepting them as true. The term used for this behavior is "hallucinations".
* The ChatGPT base model, and most models, cannot generate citations/references. If you ask for them, the systems will give you text that looks like real citations, but they are hallucinations. Search for those references in [Google Scholar](https://scholar.google.com/) to verify. BingChat and Bard can give some links, but their outputs for references should not be trusted without verification.
* Answers are not vetted, so the user must take on the responsibility of vetting information. You can think about the answers you get as "What would an answer to the prompt *sound like*?". Remember that incorrect answers will be presented in the same manner as correct ones. AI tools can be confidently wrong.
* These systems are poor at computation and logical reasoning, so again, be careful when presenting queries that require these skills.
* If you give one of these systems a programming problem, do not blindly trust the answer. These systems do not understand the code that they are providing, so it is not guaranteed to work properly.
* The more widely these systems are used, the more easily instructors can detect their writing style. So beware of blindly doing a copy/paste into homework assignments or take-home exams.
* *Do not give them personal information*, as it may be recorded and used in future model training.
* The companies claim no responsibility for the outputs generated, so if you use an output and it gets you into trouble, you have no recourse with them. Similarly, they use indemnity clauses in their user agreements, so if you generate content which results in legal action being brought against the company, you are on the hook for their legal fees.
* As with any tool, users must monitor their own usage and engagement. The possibility of developing dependency on these systems, as with other technologies like cell phones, is real. These tools do not replace learning, they augment it. These tools are not alive, even though the responses seem lifelike. As such, they are not your friend, nor are they a replacement for human interaction.

## Effective Prompting 101

* These systems are multilingual, so if you speak more than one language, try prompts in different languages to see which gives the most useful output.
* Clear and concise communication is best. Just like with talking to people, longer inputs lead to more confusion.
* Including pertinent details will generate better responses.
* Chats have memory, so you can have a conversation. Responses will improve as you ask for refinements.
* Ask the model to help you with spelling and grammar checks.
* Telling the models to "Act as..." and assigning them a role will often improve outputs as it helps them tap into the right part of their data.  
* "Teach me..." will engage a step-by-step model.
* Ask the model to debate a position with you.  Example: "Let's debate about if 3D pie charts should ever be used. You take the pro position."
* If an answer is too complicated, ask it to simplify, for example, "Explain it to me like I was a child/in 8th grade/a novice."

### Study Buddy

Below is an example of an effective way to use an AI tool as a study buddy.

Prompt (*fill in [ ] with your desired content*):  
`Act as a college [computer science] professor. I am a student trying to understand and learn about [preattentive processing]. Please ask me a question. I will attempt to answer it. If I am right, tell me so, then ask me a harder question. If I am wrong, tell me the right answer, give me a brief explanation of why that answer is correct, and then ask me a slightly easier question. If you understand, say “I am ready to help you learn" then ask me your first question.`

Be aware, however, that your professor might not always agree with the answers that the AI tool provides. So, make sure to check anything you get back with your course notes.

### Data Processing Help

These tools are often good at summarizing answers you might find scattered among many webpages as the result of a Google search (and this is largely their purpose).

Example prompts:  
`Sort a Pandas dataframe by column`,  
`Create a new Pandas dataframe by trimming the first 10 values from an existing dataframe`

The tool will likely describe the main function that could be used and demonstrate its use on a small example dataframe. It will likely also describe some of the options that are available.

You should always test out any code that AI tools provide to make sure that it's correct and that you understand what the code is doing.

### Copy Editing Help

Prompt:  
`Point out the grammatical or spelling errors in the following paragraph.`

## For More Information

I found the following resources interesting and informative, both related to the techology behind these new AI tools and ethical concerns around their use:

* ["A jargon-free explanation of how AI large language models work"](https://arstechnica.com/science/2023/07/a-jargon-free-explanation-of-how-ai-large-language-models-work/), Timothy B. Lee and Sean Trott, ars technica, July 31, 2023.
* ["Unpacking AI: "an exponential disruption" with Kate Crawford"](https://www.msnbc.com/msnbc-podcast/why-is-this-happening/unpacking-ai-exponential-disruption-kate-crawford-podcast-transcript-n1304427), Chris Hayes "Why is This Happening?" podcast, April 19, 2023.
  * [More about Kate Crawford](https://www.katecrawford.net/about.html).
* "A.I. and Stochastic Parrots with Emily Bender and Timnit Gebru" ([listen](https://www.podchaser.com/podcasts/factually-with-adam-conover-853712/episodes/ai-and-stochastic-parrots-with-170946764), [watch](https://www.youtube.com/watch?v=jAHRbFetqII)), Adam Conover "FACTUALLY" podcast, April 26, 2023.
  * [Emily Bender](http://faculty.washington.edu/ebender/) is Professor at the University of Washington
  * [Timnit Gebru](https://en.wikipedia.org/wiki/Timnit_Gebru) is the founder of the Distributed Artificial Intelligence Research Institute (DAIR) and was famously fired from Google for raising ethical questions about the use of AI.
