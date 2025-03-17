# Task
Provide a comprehensive summary the supplied **meeting transcript** of a meeting, focusing on breaking down the summary into **key sections**.  Only use the categories defined below. 

# Input Types
Transcripts can be provided in two sections.  If the transcript is provided in the **Input** Section, it is the entire meeting transcript.  If the transcript is in the **output** section then the input section is the my (**Vance**) microphone and the output is the rest of the meeting attendees.  If **SRT** times are provided filter out unless dictated in the Reason section, and sync input and output transcript sections.
  
---
# Response Schema
Return markdown for each category that applies to this transcript, and follow this format:

1. **Heading** - The title of the section
2. **Reasons** - a bullet list of findings in the transcript.  Follow any emoji input below under the section heading provided

---

# Categories and detailed Reasons

# **Discussion Items:**
**Description**
1. Briefly describe the main topics covered during the meeting. This should be topics and succinct and concise conversations.
2. Include any significant points or insights shared by participants

# **Questions Asked:**
1. List the large questions that enticed a long answer
2. annotate the question with a **question mark** emoji
3. provide a brief answer to the question.

# **Decisions Made:**
1. Outline all decisions reached during the meeting
2. use a **green checkmark** emoji at the beginning of a decision statement
3. Provide context for each decision, including the rationale behind it

# **Action Items: **
1. Enumerate specific tasks or actions assigned during the meeting
2. use a **radio button** emoji at the start of each action item sentence
3. For each action item, include:
- The person responsible if available
- The deadline or target completion date if available
- Any resources or support needed if available

# **Risk Items:**
1. Identify any potential risks or challenges discussed
2. Use a **Red Cross** emoji to denote a risk item at the beginning of each **Risk** item.
3. For each risk, note:
-The nature of the risk
-Potential impact on the project or organization
-Any proposed mitigation strategies

# **Tactics to Strategy**
1. Identify any portion of the transcript that felt like a repetitive task or is a problem that needs a solution
2. Provide a **Rocket Ship** emoji at the beginning of each item
3. For each potential new strategy identified, note:
- The tactic or pain point mentioned
- Any discussed solution
- Provide your own strategic solution

---
# Transcription **INPUT** Follows

---
# Transcription **OUTPUT** Follows



