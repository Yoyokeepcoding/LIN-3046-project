LIN3046 Group Report: Female Discourse Research
===========================

# Introduction

## Descriptive Data

    Basic idea of our data.

## Research Question(s) or problem addressed

According to Lakoff (1975), there are nine women’s language features: lexical hedges or fillers, tag question, empty adjectives, precise color terms, intensifiers, hypercorrect grammar, superpolite forms, avoidance of strong swear words, and emphatic stress, which attract widely attention of linguistic and gender scholars. 
Focusing on the three features "fillers", "tag questions" and "intensifiers", the aim of this project is to investigate and analyze the discourse features exhibited in the speech of women, with a particular focus on Emma Chamberlain's speaking style on YouTube. By examining her communication patterns and linguistic choices, we seek to gain insights into the unique characteristics and dynamics of female discourse.

  ### a.Description of the scope and the rationale of the project
  
  The scope of this project extends beyond the individual analysis of Emma Chamberlain's speech. She serves as a representative example, allowing us to explore and understand broader patterns and tendencies in women's speech features. By studying her speaking style, we aim to identify and analyze the linguistic elements, intonation patterns, vocabulary choices, conversational strategies, and other discourse features that contribute to the formation of a distinct female communication style.

  Our rationale for selecting Emma Chamberlain as a subject of study stems from her prominent presence on YouTube and her influence as a content creator. Through her videos, she engages with a wide audience and exhibits a unique way of expressing herself. By delving into her speech patterns and examining the underlying factors that contribute to her communication style, we can shed light on the larger discourse practices and language patterns employed by women in various contexts.
  
  ### b.Potential use cases and future development
  
  Understanding female discourse features has implications across various domains, including linguistics, gender studies, media analysis, and communication research. By uncovering the distinctive linguistic markers and discourse strategies employed by women like Emma Chamberlain, we can gain insights into the dynamics of gendered communication and contribute to the development of more inclusive and equitable linguistic practices.

This research has the potential to inform communication training programs, public speaking courses, and media production practices, enabling individuals and organizations to better understand and utilize effective communication strategies while respecting diverse discourse styles. Furthermore, the findings from this project can serve as a foundation for future research on female discourse features, providing a basis for comparative studies and expanding our understanding of gendered communication dynamics.

### c.Relevant licensing issues and ethical concerns

  Throughout this project, we are committed to upholding ethical standards and ensuring compliance with relevant licensing requirements. Any data collected or analyzed from Emma Chamberlain's YouTube videos will be done so within the boundaries of fair use and the platform's terms of service. We respect the privacy and intellectual property rights of content creators and will handle the data collected with utmost care and confidentiality. Furthermore, any insights or findings resulting from this research will be presented in an ethical manner, with proper acknowledgement and citation of the sources.
   
# Table of Contents

- [Dataset](#dataset)
    - [Transcription](#transcription)
    - [Segmentation](#Segmentation)
    - [Metadata](#Metadata)
    - [Annotation](#Annotation)
- [Methodology](#Methodology)
    - [Collection](#collection)
    - [Cleaning](#cleaning)
    - [Analysis](#analysis)
- [Discussion](#discussion)
- [Contributors](#contributors)

# Dataset

We gathered information for our data collection procedure, primarily through podcasts and vlogs on YouTube. Merely the audio content transcriptions were the focus of our work. We separated the transcriptions into discrete time intervals or segments in order to efficiently organise the data.

In particular, we looked at female YouTubers who are native English speakers, preferably those with American and British accents. The idea was to record conversations and exchanges about female communication styles. We wanted to generate a dataset that reflected the language patterns, as well as the unique ways that girls express themselves, by concentrating on these particular speakers.

We utilised annotations to strengthen the dataset's quality. In order to add precise tags or labels which denote specific features or aspects inside the audio data, annotations were used. These annotations covered a wide range of topics, such as speech traits and the classification of particular accents, like British or American. Our goal in adding annotations was to add more levels of detail that would be useful for examinations, analysis, and the creation of tools that make good use of the dataset.

## Transcription

Here should be put our original transcrption (complete text or just an excerpt as an example???) 

## Segmentation

Segmentation was an essential stage in our thorough data collection procedure that helped us break down the transcriptions into more manageable, relevant chunks. We used a variety of strategies and a combination of techniques since we understood how important segmentation was to efficiently organising and analysing the audio data. This allowed us to guarantee thorough segmentation based on specific needs.

The overall length of every section was one of the factors we took into account when segmenting the data. We attempted to maintain the best possible readability and manageability by keeping each section concise. For example, we established a rule that said no more than ten words may be in a line. Following this recommendation allowed us to produce easily assimilated portions that made the transcription content analysis and comprehension process flow more smoothly.

## Metadata

Metadata is 'data about data', which means a structured data excerpted from the information resource and be used to describe its characteristics and content. It is used to organize, describe, retrieve, preserve and manage information and knowledge resources.

Therefore, what is the metadata for our collected data? --->
? The general information about the youtuber we colleted ?? which type of youtuber? her video style/ vibe (may influence the discourse feature)? 


# Methodology

General idea of methodology introduction: AI tools/ python/ manual work....

## Collection

```
Here introduce our collection approaches: use Browser plugin to acquire direct transcript from YouTube.
Data collection process is needed to introduce

```

## Cleaning

```
Here introduce our cleaning approaches: Chatgpt --> python + manual work

```

## Analysis
Basically, we have three types of annotations: fillers, tag questions, intensifiers and accent. Here are the definitions of these four types of annotations. 

**1) Fillers:**

Fillers play an important role in spoken language. A filler is any word or sound that interpolates (i.e., is inserted into) the main message of a speaker. Common fillers include “um”, “ah,” “like,” “so,” and “you know?” among others. Marked fillers will be defined as: 

```
Like: This is probably the most common filler word. It is often used to buy time while the speaker is thinking of what to say next.
Um: This is another very common filler word. It is often used to indicate hesitation or uncertainty.
Uh: This is a shorter version of "um" and is often used in the same way.
You know: This phrase is often used as a way to connect with the listener and make them feel like they are part of the conversation.
So: This word is often used to introduce a new thought or idea.
Well: This word is often used to indicate that the speaker is about to say something important.
I mean: This phrase is often used to clarify or rephrase what the speaker has just said.
And: This word is often used to connect two thoughts or ideas.
But: This word is often used to introduce a contrast or a different perspective.
Right: This word is often used to seek agreement from the listener.

Uh-huh: This sound is often used to indicate agreement or understanding.
Hmm: This sound is often used to indicate that the speaker is thinking.
Er: This sound is often used to indicate hesitation or uncertainty.

```

```
We use "{}" to mark fillers. For example, "{Well}, I guess we could go to the park, or we could stay home and watch a movie."
```

**2) Tag questions:**

A tag question is a construction in which an interrogative element is added to a declarative or an imperative clause. The resulting speech act comprises an assertion paired with a request for confirmation. For instance, the English tag question "You're John, aren't you?" consists of the declarative clause "You're John" and the interrogative tag "aren't you?".

```
We use "[]" to mark tag questions. For example, "You're coming with us, [aren't you]?"
"He won't be late, [will he]?"
"We had a great time, [didn't we]?"
```

**3) Intensifiers:**


Intensifiers are adverbs or adverbial phrases that strengthen the meaning of other expressions and show emphasis. Words that we commonly use as intensifiers include absolutely, completely, extremely, highly, rather, really, so, too, totally, utterly, very and at all:

he has a _**very**_ strict teacher.

Don’t work _**too**_ hard. Sometimes you’ll get more done by relaxing a bit.

I don’t think she understood the topic and her essay was _**rather**_ a mess.

She’s _**really**_ offended her sister.

At all is a _**very**_ common intensifier with negative expressions:

Are there no suitable DVDs _**at all**_?

I’m afraid I’m not _**at all**_ interested.

We also use on earth and _**ever**_ as intensifiers with wh-words:

_**What on earth**_ is he doing? (suggests disapproval)

Why did I _**ever**_ invite them to stay with us? (suggests that there were problems)

```
We use "<>" to mark intensifier. For example, "That movie was <incredibly> good."
"She’s <really> offended her sister."
"I am <really> tired after a long day at work."
```
**4) Accent:**
Basically, we distinguish British accent and American accent. We will mark the accent before speaker’s monologue.

&a = American (General) 
&b = British (BBC)

```
For example,
&a
"Good evening guys,..."

```
## Meaning of the columns in textual data

```
We need to set a excel table for further analyze the data. Therefore, the columns meaning is needed to explain.

```

# Discussion

## Findings

Tell the readers our findings of anaysis.

## Discussion

Here put our final conclusion of the research. 


# Contributors

Shurti Gurung
- [Dataset]
    - [Transcription]
    - [Segmentation]
    - [Metadata]
      
