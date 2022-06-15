# QuickPoll
Post
{
"question": "Who will win SuperBowl?",
"options": [
{"value": "New England Patriots"},
{"value": "Seattle Seahawks"},
{"value": "Green Bay Packers"},
{"value": "Denver Broncos"}]
}



Update
{
    "id" : 1,
"question": "Who will win SuperBowl this year?",
"options": [
{"id" : 1, "value": "New England Patriots"},
{"id" : 2,"value": "Seattle Seahawks"},
{"id" : 3,"value": "Green Bay Packers"},
{"id" : 4,"value": "Denver Broncos"}]
}

Cast Vote
http://localhost:8080/polls/1/votes
{
    "option": {"id" : 1, "value" : "New England Patriots"}
}


Compute Results
http://localhost:8080/computeresult/1




Error Handling

http://localhost:8080/polls/100



Validation errors
{
    "options": [
        {
            "value": "Yes"
        },
        {
            "value": "No"
        },
        {
            "value": "It Depends"
        },
        {
            "value": "I'd rather stick a fork an outlet"
        }
    ]
}


{
 "question": "Who will win SuperBowl this year? I really wonder",
 "option": [
 {"value": "New England Patriots"},
 {"value": "Seattle Seahawks"},
 {"value": "Green Bay Packers"}
 {"value": "Denver Broncos"}]
}
