# AI Lead Analysis

## Objective

Analyze incoming sales leads using Google Gemini AI and classify them based on business potential.

## AI Model

* Google Gemini (Free API)
* Basic LLM Chain in n8n

## Prompt Strategy

The AI receives lead information including:

* Name
* Email
* Company
* Budget
* Message

The model returns a structured JSON response containing:

* Lead Score
* Confidence
* Reason
* Next Action

## Sample Output

```json
{
  "lead_score": "Hot",
  "confidence": 95,
  "reason": "Lead has expressed a clear need for AI automation and provided a specific budget of 10000.",
  "next_action": "Schedule a discovery call."
}
```

