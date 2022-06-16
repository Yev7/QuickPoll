# QuickPoll
Post
{
"question": "What's your favorite food?",
"options": [
{"value": "Pizza"},
{"value": "Burger"},
{"value": "Pasta"},
{"value": "Cheesesteak"}]
}



Update
{
    "id" : 1,
"question": "Who will win SuperBowl this year?",
"options": [
{"id" : 1, "value": "Pizza"},
{"id" : 2,"value": "Burger"},
{"id" : 3,"value": "Pasta"},
{"id" : 4,"value": "Cheesesteak"}]
}

Cast Vote
http://localhost:8080/polls/1/votes
{
    "option": {"id" : 1, "value" : "Pizza"}
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
