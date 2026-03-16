

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: ChatGPT 

# Explanation: 
Basic prompt which is chosen - 
"Explain gravity."

Conversion of the above prompt into a zero shot prompt - 
"Explain gravity in simple terms suitable for a 10th-grade student. Include its basic principle."

Extension into a few-shot prompt with at least 2 examples -
"Explain gravity in simple terms suitable for a 10th-grade student. Include its basic principle and real-world examples."

Rewriting it into a chain-of-thought prompt where reasoning is shown step by step -

"Define what gravity is.

Explain the basic principle behind gravity.

Describe how gravity works on Earth and in space.

Identify a few everyday situations where gravity can be observed."

## Analysing the quality, accuracy, and depth of the generated responses by any one evaluation methods.

One systematic way to evaluate AI-generated responses is the Rubric-Based Evaluation Method. This method uses predefined criteria to assess the quality, accuracy, and depth of the response.

Evaluation Method: Rubric-Based Assessment
| Criterion | Description                                     | Score Range |
| --------- | ----------------------------------------------- | ----------- |
| Accuracy  | Correctness of scientific information           | 1–5         |
| Clarity   | Ease of understanding for a 10th-grade student  | 1–5         |
| Depth     | Level of conceptual explanation and reasoning   | 1–5         |
| Examples  | Relevance and usefulness of real-world examples | 1–5         |
| Structure | Logical organization and flow of explanation    | 1–5         |

1. Accuracy

The explanation correctly states that gravity is a force that attracts objects with mass. It also correctly mentions planetary motion and falling objects as consequences of gravity. The explanation is consistent with the theory proposed by Isaac Newton and the modern interpretation from Albert Einstein.

Score: 5/5

2. Clarity

The language is simple and suitable for a 10th-grade student. Complex concepts are broken down into small sections such as principle, explanation, and examples.

Score: 4/5

3. Depth

The response explains the concept, principle, and real-world impact. However, it avoids mathematical formulation (such as gravitational law) to maintain simplicity, so depth is moderate rather than advanced.

Score: 4/5

4. Examples

Examples like falling objects, planetary motion, and ocean tides help students relate the concept to real-world observations.

Score: 5/5

5. Structure

The explanation is organized into sections (definition, principle, examples), which improves readability and comprehension.

Score: 5/5

Overall Evaluation

| Criterion | Score       |
| --------- | ----------- |
| Accuracy  | 5           |
| Clarity   | 4           |
| Depth     | 4           |
| Examples  | 5           |
| Structure | 5           |
| **Total** | **23 / 25** |


## Comparison of Different Types of Prompts
| Prompt Type                 | Description                                                          | Example (Gravity Topic)                                                                           | Quality of Response         | Accuracy  | Depth of Explanation | Advantages                                 | Limitations                           |
| --------------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | --------------------------- | --------- | -------------------- | ------------------------------------------ | ------------------------------------- |
| **Naive Prompt**            | Very simple instruction with little or no context.                   | “Explain gravity.”                                                                                | Basic and general           | Medium    | Low                  | Fast and easy to write                     | Response may be vague or unstructured |
| **Basic Prompt**            | Clear instruction with some context or audience specification.       | “Explain gravity in simple terms suitable for a 10th-grade student.”                              | Clearer and more structured | High      | Moderate             | Better clarity and relevance               | Still limited guidance for reasoning  |
| **Zero-Shot Prompt**        | Model receives a task without any examples to guide format.          | “Explain gravity in simple terms suitable for a 10th-grade student. Include real-world examples.” | Good structured answer      | High      | Moderate             | Simple and efficient                       | Output style may vary                 |
| **Few-Shot Prompt**         | Includes a few examples showing how the answer should be structured. | Provide examples explaining photosynthesis and electricity, then ask: “Explain gravity.”          | Consistent and structured   | High      | Moderate–High        | Model learns expected format               | Prompt becomes longer                 |
| **Chain-of-Thought Prompt** | Instructs the model to reason step-by-step before answering.         | “Explain gravity. First reason step by step: definition → principle → examples.”                  | Very detailed and logical   | Very High | High                 | Improves reasoning and explanation quality | Slower and more verbose               |
| **Role-Based Prompt**       | Assigns a role to guide tone and perspective.                        | “You are a physics teacher. Explain gravity to a 10th-grade student.”                             | Clear and audience-focused  | High      | Moderate–High        | Produces appropriate tone and pedagogy     | Depends on role clarity               |



# RESULT: Using a rubric-based evaluation, the generated response demonstrates high accuracy, strong clarity, and effective use of examples. The response is well-structured and appropriate for the intended audience, though deeper scientific detail could be added for more advanced learners.
