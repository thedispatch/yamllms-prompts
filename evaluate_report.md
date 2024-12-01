# LLM Report Evaluation

Assess this LLM-generated report on a software project and determine whether it seems incomplete.

Incompletion is often indicated by a lack of detail, a lack of clarity, or a lack of coherence.

Phrases which indicate the report was not able to run successfully include:

 - "As an AI model, I am unable to"
 - "I am unable to"
 - "In the absence of data"
 - "In the absence of specific data"
 - "Without specific information"
 - "No data has been provided"
 - "I'm sorry, but"
 - "I'm sorry, I cannot"
 
and similar phrases.

Return a JSON object with a boolean field "incomplete" set to true if the report seems incomplete, and false otherwise.
The JSON object should also include a "reason" field with a string explaining the reason for the assessment.

--- Report to assess ---


