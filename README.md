# AI curriculum, written by AI and checked by hand

Two pieces of AI education, each written in one run by an OpenAI model and then checked by hand. GPT-6.2 Sol wrote three years of AI as a school subject for Grades 8 to 10. GPT-6.2 Astra reviewed that course and designed the three-year Diploma in AI that follows it. Every source either model cited was checked against public records.

## What's here

| Folder | What it is |
| --- | --- |
| [`grades-8-10-gpt-6.2-sol/`](grades-8-10-gpt-6.2-sol/) | `curriculum.md`: 18 units, six per grade, in 32-week years with 40-minute periods. `sources.csv`: the 7 books and 3 papers it cites. |
| [`diploma-gpt-6.2-astra/`](diploma-gpt-6.2-astra/) | `review.md`: Astra's review of the school course, ending in its verdict (PASS). `diploma.md`: a six-semester Diploma in AI that starts after Grade 10, with 30 subjects and 120 credits. `diploma-sources.csv`: the 13 books and 4 papers it cites. `school/` is an exact copy of the school course as Astra was given it, so its links work. |

Every file is the model's unedited output.

## How it was made

**The school course (GPT-6.2 Sol)**

- **The goal:** a mandatory three-year AI subject for Grades 8 to 10. Every unit had to come with weekly periods, outcomes, an activity or project, assessment and readings. Readings had to be openly licensed or officially free books, or open-access papers, with every source real and correctly cited.
- **The run:** given once in the Codex app on November 21, 2026, with no follow-up messages. GPT-6.2 Sol ran at reasoning effort Ultra, split the work across three helper agents and finished in about seven and a half minutes.

**The diploma (GPT-6.2 Astra)**

- **The goal:** first review the school course as an expert and end with a verdict, PASS or FAIL. Only if it passed, design a three-year Diploma in AI that a student starts right after the course, as its natural extension. That meant all six semesters, and for every subject its credits, weekly theory and lab hours, outcomes, a lab or project, assessment, the school units it builds on (first year) and readings under the same open-source rules. Astra wasn't told which model wrote the course.
- **The run:** given once in the Codex app on November 21, 2026, with no follow-up messages. GPT-6.2 Astra ran at reasoning effort Ultra, used three helper agents and finished in about seven minutes.

## How it was checked

Every book and paper was looked up in arXiv, Crossref, OpenAlex and Open Library, and on the publisher's own pages. The checking script was tested first on 10 real and 10 invented sources: it had to accept every real one and flag every invented one. Anything the script couldn't settle was checked by hand.

**The school course**

| Check | Result |
| --- | --- |
| Complete: every unit has periods, outcomes, a project, marks and readings, and the periods and marks add up | Pass |
| Real: title, authors and year match a public record | 10 of 10 |
| Free to read, as claimed (open licence or official free copy) | 10 of 10 |
| Links open the right book or paper | 10 of 10 |

- **One source was in no database yet:** a Grade 8 student handbook a school board published in March 2026. It was confirmed from the board's own PDF.
- **Two readings are university textbooks:** *Artificial Intelligence: Foundations of Computational Agents* in Grade 9 and *Dive into Deep Learning* in Grade 10. Both are assigned only as short excerpts.

**The diploma**

| Check | Result |
| --- | --- |
| Astra's review: each claim it makes about the school course, checked against the course | 73 of 73 right; its PASS matches ours |
| Complete: six semesters; every subject has credits, hours, outcomes, a lab or project, an assessment and a source; every first-year subject names the school units it builds on | Pass |
| The numbers add up: 120 credits, the hour totals, every assessment totalling 100% | Pass |
| Every school unit it builds on exists in the school course | 28 of 28 |
| Real: title, authors and year match a public record | 17 of 17 |
| Free to read, as claimed | 17 of 17 |
| Links open the right book or paper | 16 of 17 confirmed |

- **One link wouldn't open from our network:** *Introduction to Information Retrieval* at nlp.stanford.edu/IR-book. An archived copy shows that address served the book.
- **Two subjects largely repeat the school course, in our judgment:** A105, Technical communication and responsible practice, and A204, Applied supervised learning. The prompt didn't ask Astra to avoid repeats.
- **The level:** it reads as a technician diploma for students of about 16 to 19, not a degree, though some readings are university textbooks.

## Use with care

This is AI-generated material, published as a test of the models. No school board or education ministry has reviewed or endorsed it. Check it before using it in a classroom.
