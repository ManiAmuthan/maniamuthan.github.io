## Electronics Shop

# Code

"": {
  "prefix": "",
  "body": [
    "function getMoneySpent(keyboards, drives, budget) {",
    "    let finalArr = []",
    "    const keyBoardLen = keyboards.length",
    "    const drivesLen = drives.length",
    "    for(let i = 0;i<keyBoardLen; i++){",
    "        const keyBoardValue = keyboards[i]",
    "        for(let j = 0; j< drives.length; j++){ ",
    "            const drivesValue = drives[j]",
    "            const total = keyBoardValue + drivesValue",
    "            if(total <= budget){",
    "                finalArr.push(total)",
    "            }",
    "        }",
    "    }",
    "    const finalSortedArr = finalArr.sort(function(a, b){return a-b});",
    "    return finalSortedArr.length <= 0 ? -1 : finalSortedArr.pop()",
    "}"
  ],
  "description": ""
}
