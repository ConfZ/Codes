```{.C  .numberLine}
while (true)
       {
           IdentityOpsMap::iterator nextIt = identity_ops.find(it->second);
           if (nextIt != identity_ops.end())
                 it = nextIt;
             else
                   break;
         }
```
