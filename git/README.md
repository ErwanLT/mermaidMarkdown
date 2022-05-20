```mermaid
gitGraph:
    options
    {
        "nodeSpacing": 400,
        "nodeRadius": 10,
        "mainBranchName": 'master',
        "showBranches": true
    }
    end
   commit id: "init project"
   commit
   branch develop
   commit id: "init branch dev"
   checkout develop
   branch feature_1
   checkout feature_1
   commit id: "new feature"
   commit id: "add test feature"
   checkout develop
   merge feature_1
   commit id: "validation" tag:"v1"
   commit id: "prepare new iteration"
   checkout develop
   branch feature_2
   checkout feature_2
   commit

```
