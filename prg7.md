Problem Statement: Medical Triage Classification
A healthcare organization wants to develop an AI assistant that classifies patient
symptoms into urgency levels to help determine how quickly medical attention is
needed. Design a prompt that analyzes the patient&#39;s symptoms and assigns an
appropriate triage category based on predefined rules.
Triage Categories:

 EMERGENCY: Potentially life-threatening symptoms requiring immediate
emergency medical attention.
 URGENT: Symptoms requiring prompt medical assessment.
 ROUTINE: Mild symptoms that generally allow a non-emergency medical
appointment.
 INSUFFICIENT_DATA: The information provided is insufficient to determine
an appropriate category.
Input:
&quot;I have severe chest pain and difficulty breathing.&quot;
Expected Output:
EMERGENCY
Additional Examples:
Patient Query Expected Output
I have severe chest pain and difficulty breathing. EMERGENCY
I have a high fever and persistent vomiting. URGENT
I have had mild nasal congestion since yesterday. ROUTINE
I want to know which vitamins are good for general
health.

ROUTINE

I feel unwell. INSUFFICIENT_DA

TA

I have a severe headache that started suddenly. EMERGENCY
Constraints:
1. Classify symptoms according to the predefined triage rules.
2. Never invent symptoms or medical history.
3. When information is insufficient, return INSUFFICIENT_DATA unless the
reported symptoms already indicate an emergency.
4. If emergency warning signs are reported, prioritize immediate emergency care
rather than asking follow-up questions first.
5. Return exactly one label: EMERGENCY, URGENT, ROUTINE, or
INSUFFICIENT_DATA.
