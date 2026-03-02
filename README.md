# ADV-FORMS


## You have reached the ADV-FORMS dataset...





ZIP-folder split.zip contais CSV-files with the names of the images used for training, test and validation.

ADV-FORMS_annotations_cleaned.json contains JSON objects for each annotated image file:

"objects" contains a list of bounding boxes.

"objects['category']['name']" is the label of the bounding box.

"objects['tags']" contains the transcriptions of the bounding box.



Here is an example structure of the JSON:

```json
[
  {
    "image": {
      "fileName": "q033_033_0195_R.jpg",
      "details": {
        "folderName": "train",
        "width": 1966.0,
        "height": 1197.0,
        "depth": 3
      }
    },
    "objects": [
      {
        "bndbox": {
          "minX": 0.23802,
          "minY": 0.645713,
          "maxX": 0.63937,
          "maxY": 0.903189
        },
        "category": {
          "name": "mark_omission",
          "color": "#F13A58"
        },
        "tags": [],
        "parts": []
      },
      {
        "bndbox": {
          "minX": 0.17603,
          "minY": 0.250711,
          "maxX": 0.886644,
          "maxY": 0.394737
        },
        "category": {
          "name": "answer_handwritten",
          "color": "#D4495F"
        },
        "tags": [
          "Kirchwerhfest an"
        ],
        "parts": []
      },
      {
        "bndbox": {
          "minX": 0.059093,
          "minY": 0.380764,
          "maxX": 0.961406,
          "maxY": 0.507685
        },
        "category": {
          "name": "answer_handwritten",
          "color": "#D4495F"
        },
        "tags": [
          "Martini - Märtes Kerb."
        ],
        "parts": []
      },
      {
        "bndbox": {
          "minX": 0.05379,
          "minY": 0.2414,
          "maxX": 0.964438,
          "maxY": 0.515152
        },
        "category": {
          "name": "answer_multiline_container",
          "color": "#3248D2"
        },
        "tags": [],
        "parts": []
      },
      {
        "bndbox": {
          "minX": 0.595239,
          "minY": 0.028664,
          "maxX": 0.648219,
          "maxY": 0.096229
        },
        "category": {
          "name": "location_ID_part2",
          "color": "#F5AEA5"
        },
        "tags": [
          "30"
        ],
        "parts": []
      },
      {
        "bndbox": {
          "minX": 0.699952,
          "minY": 0.030711,
          "maxX": 0.774746,
          "maxY": 0.088039
        },
        "category": {
          "name": "location_ID_part3",
          "color": "#8D2556"
        },
        "tags": [
          "11 c"
        ],
        "parts": []
      },
      {
        "bndbox": {
          "minX": 0.446897,
          "minY": 0.021498,
          "maxX": 0.780355,
          "maxY": 0.101348
        },
        "category": {
          "name": "location_ID_full",
          "color": "#F7DD20"
        },
        "tags": [
          "151 30 11c"
        ],
        "parts": [
          {
            "bndbox": {
              "minX": 0.45313,
              "minY": 0.030711,
              "maxX": 0.527924,
              "maxY": 0.101347
            },
            "category": {
              "name": "location_ID_part1",
              "color": "#FAF6FC"
            },
            "tags": [
              "151"
            ],
            "parts": []
          }
        ]
      },
      {
        "bndbox": {
          "minX": 0.844554,
          "minY": 0.037877,
          "maxX": 0.928075,
          "maxY": 0.103395
        },
        "category": {
          "name": "location_region_ID",
          "color": "#0E6556"
        },
        "tags": [
          "UF"
        ],
        "parts": []
      }
    ]
  }
]
```

