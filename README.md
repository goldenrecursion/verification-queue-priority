# verification queue priority

The priority.json file contains a list of rules considered when selecting the priority for a verification queue item. The first rule that matches sets the priority. If no rule is matched, the default priority is set (see the "default_priority" field). The priority number can be between 1 and 20 and a verification item with a smaller priority number will always be served in the verification queue before a verification item with a higher priority number.

To understand the file format please check *priority.schema.json* which is a *jsonschema* that describes all the used fields. You can find more details about jsonschema on https://json-schema.org/.

test