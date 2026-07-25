# Example 1

## Input

Today's meeting focused on the website redesign.

Rahul will complete the homepage by Friday.

Priya will test the mobile version over the weekend.

The launch is planned for Monday.

A possible delay may occur if testing isn't completed.

---

## Output

{
  "meeting_summary":"Website redesign progress meeting.",
  "action_items":[
    "Complete homepage",
    "Test mobile version"
  ],
  "deadlines":[
    "Friday",
    "Weekend",
    "Monday"
  ],
  "owners":[
    "Rahul",
    "Priya"
  ],
  "risks":[
    "Testing delay"
  ],
  "priority":"High"
}

# Example 2

## Input

Marketing team finalized the Instagram campaign.

Ananya will prepare graphics before Wednesday.

Rohan will schedule all posts on Thursday.

Campaign goes live Friday.

---

## Output

{
  "meeting_summary":"Instagram campaign planning.",
  "action_items":[
    "Design graphics",
    "Schedule posts"
  ],
  "deadlines":[
    "Wednesday",
    "Thursday",
    "Friday"
  ],
  "owners":[
    "Ananya",
    "Rohan"
  ],
  "risks":[],
  "priority":"Medium"
}

# Example 3

## Input

Customer support reported frequent login failures.

Development team will investigate immediately.

Fix should be deployed tomorrow evening.

Users may experience temporary downtime.

---

## Output

{
  "meeting_summary":"Login issue investigation.",
  "action_items":[
    "Investigate login failures",
    "Deploy fix"
  ],
  "deadlines":[
    "Tomorrow Evening"
  ],
  "owners":[
    "Development Team"
  ],
  "risks":[
    "Temporary downtime"
  ],
  "priority":"Critical"
}
