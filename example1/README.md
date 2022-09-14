# Trying to output header/footer record attributes in the transformations 

Particulary:
```
"HDRSenderType": { "xpath": "../../../HDR/senderType" },
"GRHTransactionType": { "xpath": "../../GRH/transactionType" },
"GRTTransactionCount": { "xpath": "../GRT/transactionCount" },
"TRLGroupCount": { "xpath": "../../../TRL/groupCount" },
```

But keep getting following error for transformation: `GRHTransactionType`
```
Error: input 'CWR-TEST_001.V21' line 26: fail to transform. err: xpath query '../../GRH/transactionType' on 'FINAL_OUTPUT.GRHTransactionType' yielded more than one result
```

If I remove the transformation, I'm getting just `HDRSenderType` field filled. 
