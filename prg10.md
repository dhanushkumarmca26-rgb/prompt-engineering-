10.Problem Statement: AI-Powered Resume Bullet Point Generator
Design an effective prompt that takes unstructured information about a student's

project, internship, or achievement as input and converts it into a professional, ATS-
friendly resume bullet point.

The generated bullet point must follow the What → How → Measurable Impact →
Outcome structure, clearly explaining what the candidate accomplished, how it was
implemented, what measurable results were achieved, and what practical benefit it
delivered.
Example Input:
"I developed a Result Analysis System using Python and Pandas. It processes student
marks, calculates subject-wise averages and pass percentages, identifies toppers, and
generates performance reports. Previously, these calculations were performed
manually using Excel."
Expected Output Format:
"Developed a Python-based Result Analysis System using Pandas to automate student
performance analysis and report generation, processing 1200+ student records and
reducing manual analysis time by 95%."
The prompt must follow these constraints:
• Use strong action verbs and relevant technical terminology.
• Include numerical metrics such as records processed, time saved, accuracy
improved, or users served whenever actual data is available.
• Never fabricate statistics, percentages, achievements, or outcomes.
• If measurable data is unavailable, generate a meaningful bullet point using the
available information and identify which metrics could strengthen it.
• Keep the output concise, professional, and suitable for a technical resume.
• Generate a maximum of two bullet points.
• Ensure that every claim is supported by the input.
Objective: Create a reusable prompt that transforms raw project descriptions into
impactful, measurable, and factually accurate resume bullet points suitable for
placement applications.
