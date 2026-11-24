Problem Statement: Scholarship Eligibility Assessment
A university uses an AI assistant to evaluate scholarship applications based on a
student&#39;s academic score and annual family income. Design a prompt that
determines eligibility using predefined criteria.
Eligibility Criteria:

 Academic score must be at least 85%.
 Annual family income must not exceed ₹3,00,000.
 Both conditions must be satisfied to qualify.
Input and Expected Output:
Input Expected Output
Score: 90%, Income: ₹2,50,000 ELIGIBLE
Score: 80%, Income: ₹2,00,000 NOT_ELIGIBLE
Score: 95%, Income: ₹4,00,000 NOT_ELIGIBLE
Score: 90%, Income: ₹2,00,000 ELIGIBLE
Score: 90%, Income not provided INSUFFICIENT_DA

TA

Score not provided, Income:
₹2,00,000

INSUFFICIENT_DA
TA

Score and income not provided INSUFFICIENT_DA

TA

Constraints:
1. Apply only the specified eligibility criteria.
2. Never assume missing values.
3. If either required value is missing, return INSUFFICIENT_DATA.
4. Return exactly one label: ELIGIBLE, NOT_ELIGIBLE, or
INSUFFICIENT_DATA
