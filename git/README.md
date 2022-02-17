```mermaid
gitGraph:
options
{
    "nodeSpacing": 150,
    "nodeRadius": 10
}
end
commit
branch branchTest
checkout branchTest
commit
branch branchFeature
checkout branchFeature
commit
commit
merge branchFeature
checkout branchTest
checkout master
commit
commit
merge branchTest

```
