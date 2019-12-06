Course: Messiah College CIS 411, Fall 2018<br/>
Instructors: [Joel Worrall](https://github.com/tangollama) & [Trevor Bunch](https://github.com/trevordbunch)<br/>

Name: Leah Shellenhamer<br/>

GitHub: [almp15](https://github.com/almp15)<br/>

# Fork this repository
- The URL of my forked repository
- The URL of my forked repository:
 https://github.com/almp15/cis411_lab3

# Clone your forked repository from the command line
- My GraphQL response from adding myself as an account on the test project
```
{
  "data": {
    "mutateAccount": {
      "id": "750a9f71-6a24-4908-a240-2b53f42fd474",
      "name": "Leah Shellenhamer",
      "email": "ls1463@messiah.edu"
    }
  }
}

@@ -26,7 +27,7 @@ GitHub: [almp15](https://github.com/almp15)<br/>

# Signup for and configure New Relic
- The chosen name of your New Relic ```app_name``` configuration
```
app_name: ['cislab']
```

# Explore your performance data

*Mutations ran rather quickly; however, queries seemed to take a larger amount of time to run. 
*Performance in run times seem to be rather uneven
*Queries are less performant.
* #retrieve all orders container the word everything request took the longest and performed the poorest of all the requests.

* The issue is the amount of time it takes to run. To shorten that only retireve the top 5-15 matching results. This should shorten the amount of time necessary to perform the task.
