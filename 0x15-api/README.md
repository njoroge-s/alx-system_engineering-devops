### 0x15. API

#### description of the files
``0-gather_data_from_an_API.py``
Python script that uses the JSON returned from the "Fake Data For API's" link above to return information about a todo list.

``1-export_to_CSV.py``
Exports the data returned from ``0-gather_data_from_an_API.py`` into CSV

``2-export_to_JSON.py``
Exports the data returned from ``0-gather_data_from_an_API.py`` into JSON

``3-dictionary_of_list_of_dictionaries.py``
Reformats the data returned from ``0-gather_data_from_an_API.py`` into JSON: ``` { "USER_ID": [ {"username": "USERNAME", "task": "TASK_TITTLE", "completed": TASK_COMPLETED_STATUS}, {"username": "USERNAME", "task": "TASK_TITTLE", "completed": TASK_COMPLETED_STATUS}, ... ], "USER_ID": [ {"username": "USERNAME", "task": "TASK_TITTLE", "completed": TASK_COMPLETED_STATUS}, {"username": "USERNAME", "task": "TASK_TITTLE", "completed": TASK_COMPLETED_STATUS}, ... ]} ```
