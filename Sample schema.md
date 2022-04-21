{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Example",
  "type": "object",
  "properties": {
    "text": {
      "type": "array",
      "items": {
        "type": "object",
        "properties": {
          "object": {
            "type": "string"
          }
        },
        "required": [
          "object"
        ]
      }
    },
    "text1": {
      "type": "string"
    },
    "number": {
      "type": "number"
    }
  }
}
