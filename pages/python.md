*Processing JSON*

sample_dict = { "office": 
    {"medical": [
      { "room-number": 100,
        "use": "reception",
        "sq-ft": 50,
        "price": 75
      },
      { "room-number": 101,
        "use": "waiting",
        "sq-ft": 250,
        "price": 75
      },
      { "room-number": 102,
        "use": "examination",
        "sq-ft": 125,
        "price": 150
      },
    ]},
    "parking": {
      "location": "premium",
      "style": "covered",
      "price": 750
    }
} 

import json

#The JSON module is mainly used to convert the python dictionary above into a JSON string that can be written into a file.
json_string = json.dumps(datastore)

#The JSON module can also take a JSON string and convert it back to a dictionary structure:
datastore = json.loads(json_string)

#read from file
from pprint import pprint

with open('filename.json') as f:
    data = json.load(f)

pprint(data)
print(data["attribute"])

#write to file
# Writing JSON data
with open(filename.json, 'w') as f:
    json.dump(data, f)
   
