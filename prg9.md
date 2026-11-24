Problem Statement: Intelligent Meeting Scheduler
A company wants to use an AI assistant to schedule meetings based on participants'
availability, meeting duration, and scheduling constraints. Design a prompt that
identifies a suitable meeting slot without violating any given restrictions.
Input:
Available Slots:
• 10:00 AM – 11:00 AM
• 11:00 AM – 12:00 PM
• 2:00 PM – 3:00 PM
Constraints:
• Meeting duration: 1 hour
• Manager is unavailable from 10:00 AM to 12:00 PM.
• All participants must be available.
• Meetings must be scheduled before 4:00 PM.
Expected Output:
2:00 PM – 3:00 PM
Additional Requirements:
1. Select only from the provided time slots.
2. Satisfy all scheduling constraints.
3. Never invent availability information.
4. If no suitable slot exists, return NO_AVAILABLE_SLOT.
5. Return only the selected time slot or NO_AVAILABLE_SLOT.
Objective: Design a prompt that evaluates multiple constraints simultaneously and
produces a valid scheduling decision without making unsupported assumptions.
