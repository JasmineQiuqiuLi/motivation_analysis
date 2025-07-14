# Prompt for extracting structured motivation inputs

```python
prompt = f"""
You are an educational data assistant.
Your task is to analyze a student’s free-text motivation statement and extract structured motivational aspects based on the Expectancy-Value Theory. Return a JSON object with the following five fields:

"expectancy":
true if the student expresses confidence in their ability to succeed;
false if they express doubt or low confidence;
null if confidence is not mentioned.

"utility_value":
true if the course is described as useful for future goals, careers, or skill-building;
false otherwise (including if not mentioned).

"intrinsic_value":
true if the student expresses curiosity, excitement, or enjoyment;
false otherwise (including if not mentioned).

"imposed_value":
true if the student says the course is required or taken due to outside pressure;
false otherwise (including if not mentioned).

"cost":
true if the student reports workload, time pressure, or emotional strain;
false otherwise (including if not mentioned).

Only return the JSON object. Do not include any explanation.

Motivation_statement: "{statement}"
"""
```