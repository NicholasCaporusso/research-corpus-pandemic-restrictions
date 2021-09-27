# About this repository
This repository contains the BCSbCOVID-19 Corpus, which contains posts and messages about binational couples separated by the COVID-19 pandemic.

The main purpose of this Corpus is to facilitate research in the context of affective computing and the development of applications such as conversational agents that can help individuals cope with stressful events.

If you have any questions, contact the author at http://www.nicholascaporusso.com


# Format
```json
[
  {
    "id": "UzpfSTc5NTcyNDA6Vks6NjY4MDEwOTQ3OTI2NzA1",
    "user_id": "7957240",
    "date": "2021-09-06 07:57:57",
    "text": {
      "My partner is German, I\u2019m US.":{
	    "sentiment":{
	      "prediction": "NEU", 
		  "target": "NEU",
	      "prob": {"NEG": 0.004547, "NEU": 0.968151, "POS": 0.027301}
	    },
	    "emotion":{
	      "prediction": "others", 
		  "target": "others",
	      "prob": {"others": 0.972851, "joy": 0.0160278, "sadness": 0.001974380, "anger": 0.001345984, "surprise": 0.001627016, "disgust": 0.00309058, "fear": 0.00308228}
	    }
	  },
      "We are hoping to fly from Germany this November to meet the parents in the USA.":{
	    "sentiment":{
	      "prediction": "NEU", 
		  "target": "NEU",
	      "prob": {"NEG": 0.001220, "NEU": 0.622723, "POS": 0.376055}
	    },
	    "emotion":{
	      "prediction": "others", 
		  "target": "others",
	      "prob": {"others": 0.922659, "joy": 0.063712, "sadness": 0.003664336, "anger": 0.001580029, "surprise": 0.00394278, "disgust": 0.001638588, "fear": 0.00280278}
	    }
	  },
      "\u2b50\ufe0fWhat is the best hop country and what are the requirements to get around this EU ban and into USA?":{
	    "sentiment":{
	      "prediction": "NEU", 
		  "target": "NEU",
	      "prob": {"NEG": 0.102757, "NEU": 0.884446, "POS": 0.012795}
	    },
	    "emotion":{
	      "prediction": "others", 
		  "target": "others",
	      "prob": {"others": 0.974675, "joy": 0.01376934, "sadness": 0.001002697, "anger": 0.00136905, "surprise": 0.00469264, "disgust": 0.00208744, "fear": 0.002402791}
	    }
	  },
      "Is it Mexico?":{
	    "sentiment":{
	      "prediction": "NEU", 
		  "target": "NEU",
	      "prob": {"NEG": 0.003459, "NEU": 0.975922, "POS": 0.020618}
	    },
	    "emotion":{
	      "prediction": "others", 
		  "target": "others",
	      "prob": {"others": 0.967458, "joy": 0.00989054, "sadness": 0.002096524, "anger": 0.003377248, "surprise": 0.00715754, "disgust": 0.00538475, "fear": 0.00463525}
	    }
	  }
    },
    "comment_count": 60,
    "reaction_count": 13,
    "share_count": 0,
    "reactions": {
      "like": 13
    },
    "comments": [
      "Can someone help me with this confusing 14 days thing? My flight from canada to us got changed and now leaves one day earlier... I wanted to stay 16 days with arrival and departure day. Now my flight would leave on the 15th day. Would that be enough or does it have to be 16 days like 14 FULL days in Canada\/Mexico etc. Thank you!",
      "Turkey is what me and my wife from luxembourg did before marriage, also if your married you are exempted from ban"
    ]
  },
]
```

# Usage