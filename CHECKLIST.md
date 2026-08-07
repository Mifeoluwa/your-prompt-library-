# Prompt Quality Checklist

## Scoring Rubric

| Dimension | Question | Excellent (3) | Adequate (2) | Poor (1) |
|-----------|----------|---------------|--------------|----------|
| Accuracy | Is the answer correct? | Correct with no major errors | Mostly correct | Incorrect or misleading |
| Clarity | Is it easy to understand? | Very clear | Mostly clear | Confusing |
| Tone | Is the tone appropriate? | Matches the task perfectly | Mostly appropriate | Inappropriate |
| Usefulness | Can the user use it immediately? | Ready to use | Needs minor edits | Needs major edits |
| Completeness | Did it answer everything? | Fully complete | Partially complete | Incomplete |

## Weights

- Accuracy: 30%
- Clarity: 20%
- Tone: 15%
- Usefulness: 20%
- Completeness: 15%

**Pass Threshold:** 80%

---

## Pre-flight Checklist

- [ ] Role defined
- [ ] Task clearly stated
- [ ] Constraints included
- [ ] Output format specified
- [ ] Example included (when needed)
- [ ] Negative constraints included
- [ ] Reliability instructions included

---

## Post-flight Checklist

- [ ] Output evaluated
- [ ] Weakness identified
- [ ] Prompt improved
- [ ] Changes committed to Git
- [ ] Regression test completed

### Score
| Dimension    | Score | Reason                                                                |
| ------------ | :---: | --------------------------------------------------------------------- |
| Accuracy     |   3   | The email correctly requests a meeting to discuss a project.          |
| Clarity      |   3   | The purpose, request, and next step are stated clearly and concisely. |
| Tone         |   3   | The language is professional, polite, and appropriate for a lecturer. |
| Usefulness   |   3   | It is ready to send after filling in the placeholders (name, etc.).   |
| Completeness |   3   | It includes a subject, greeting, body, closing, and signature fields. |

## Email Prompt – Round 2

### Improvement Made
Added a constraint requiring the subject line to be specific to the user's request.

### Result
The generated subject line became more descriptive and relevant.

### Conclusion
The prompt produced a more useful email after one targeted refinement.