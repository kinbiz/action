# action

1. Read from setting file (*.json)
```
{
  "actions": [
    {
      "name": "Action 1",
      "type": "button",
      "conditions": "{field_1} > {field_2} AND {field_2} = {field_3}",
      "action": "view/add/update/delete",
      "api": {
        "view": "",
        "add": "",
        "update": "",
        "delete": ""
      },
      "from": {
        "appId": 1,
        "apiToken": "",
        "username": "",
        "password": ""
      },
      "to": {
        "appId": 1,
        "apiToken": "",
        "username": "",
        "password": ""
      },
      "mapping":[
        {"from": "field_1", "to": "other_field_1"},
        {"from": "field_2", "to": "other_field_2"},
        {"from": "field_3", "to": "other_field_3"},
        {"from": "field_4", "to": "other_field_4"},
        {"from": "field_5", "to": "other_field_5"},
        {"from": "field_6", "to": "other_field_6"}
      ]
    }
  ]
}
```
2. Creating an action 
- Button action
- Trigger action
