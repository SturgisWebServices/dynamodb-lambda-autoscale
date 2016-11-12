{
  "ReadCapacity": {
    "Min": 200,
    "Max": 1000,
    "Increment": {
      "When": {
        "UtilisationIsAbovePercent": 60
      },      
      "To": {
        "ConsumedPercent": 150
      }
    },
    "Decrement": {
      "When": {
        "UtilisationIsBelowPercent": 30,
        "AfterLastIncrementMinutes": 10,
        "AfterLastDecrementMinutes": 60,
        "UnitAdjustmentGreaterThan": 5
      },
      "To": {
        "ConsumedPercent": 75
      }
    }
  },
  "WriteCapacity": {
    "Min": 150,
    "Max": 1500,
    "Increment": {
      "When": {
        "UtilisationIsAbovePercent": 50
      },      
      "To": {
        "ConsumedPercent": 200
      }
    },
    "Decrement": {
      "When": {
        "UtilisationIsBelowPercent": 30,
        "AfterLastIncrementMinutes": 10,
        "AfterLastDecrementMinutes": 120,
        "UnitAdjustmentGreaterThan": 5
      },
      "To": {
        "ConsumedPercent": 50
      }
    }
  }
}
