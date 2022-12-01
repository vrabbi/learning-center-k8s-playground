# Accelerator Log

## Options
```json
{
  "bsGitBranch" : "main",
  "bsGitRepository" : "github.com?owner=vrabbi&repo=learning-center-k8s-playground",
  "consoleVendor" : "octant",
  "difficulty" : "beginner",
  "dockerMemory" : 768,
  "dockerStorage" : 5,
  "duration" : "2h",
  "enableConsole" : true,
  "enableDocker" : true,
  "enableEditor" : true,
  "enableRegistry" : true,
  "enableTerminal" : true,
  "exercises" : [ "Using vCluster" ],
  "maxSessions" : 10,
  "memoryResources" : "1Gi",
  "namespaceBudget" : "small",
  "projectName" : "k8s-playground",
  "registryMemory" : 768,
  "registryStorage" : 5,
  "terminalLayout" : "split",
  "workshopDescription" : "A Kubernetes Playground based on vCluster",
  "workshopFilesUrl" : "github.com/vrabbi-tap/learning-center-k8s-playground",
  "workshopTitle" : "Kubernetes Playground"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ ┃ engine.transformations[0].validated.merge (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [resources/workshop.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml matched [resources/workshop.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"maxSessions":10,"bsGitBranch":"main","consoleVendor":"octant","enableDocker":true,"enableTerminal":true,"duration":"2h","dockerMemory":768,"exercises":["Using vCluster"],"workshopDescription":"A Kubernetes Playground based on vCluster","workshopFilesUrl":"github.com/vrabbi-tap/learning-center-k8s-playground","artifactId":"k8s-playground","registryStorage":5,"terminalLayout":"split","enableConsole":true,"artifactVersion":"0.0.1-beta","registryMemory":768,"workshopTitle":"Kubernetes Playground","bsGitRepository":"github.com?owner=vrabbi&repo=learning-center-k8s-playground","namespaceBudget":"small","memoryResources":"1Gi","difficulty":"beginner","enableEditor":true,"enableRegistry":true,"dockerStorage":5,"projectName":"k8s-playground"}
┃ ┃ ┃ ┃ ┗ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input1325288764644082901, --data-values-file, /tmp/accelerator-options3588415554893998345.json, --output-files, /tmp/ytt-output9765968420231463163]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [resources/training-portal.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml matched [resources/training-portal.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"maxSessions":10,"bsGitBranch":"main","consoleVendor":"octant","enableDocker":true,"enableTerminal":true,"duration":"2h","dockerMemory":768,"exercises":["Using vCluster"],"workshopDescription":"A Kubernetes Playground based on vCluster","workshopFilesUrl":"github.com/vrabbi-tap/learning-center-k8s-playground","artifactId":"k8s-playground","registryStorage":5,"terminalLayout":"split","enableConsole":true,"artifactVersion":"0.0.1-beta","registryMemory":768,"workshopTitle":"Kubernetes Playground","bsGitRepository":"github.com?owner=vrabbi&repo=learning-center-k8s-playground","namespaceBudget":"small","memoryResources":"1Gi","difficulty":"beginner","enableEditor":true,"enableRegistry":true,"dockerStorage":5,"projectName":"k8s-playground"}
┃ ┃ ┃ ┃ ┗ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input657794522365909556, --data-values-file, /tmp/accelerator-options7340730248750037181.json, --output-files, /tmp/ytt-output5359663002114326925]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [workshop/workshop.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml matched [workshop/workshop.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"maxSessions":10,"bsGitBranch":"main","consoleVendor":"octant","enableDocker":true,"enableTerminal":true,"duration":"2h","dockerMemory":768,"exercises":["Using vCluster"],"workshopDescription":"A Kubernetes Playground based on vCluster","workshopFilesUrl":"github.com/vrabbi-tap/learning-center-k8s-playground","artifactId":"k8s-playground","registryStorage":5,"terminalLayout":"split","enableConsole":true,"artifactVersion":"0.0.1-beta","registryMemory":768,"workshopTitle":"Kubernetes Playground","bsGitRepository":"github.com?owner=vrabbi&repo=learning-center-k8s-playground","namespaceBudget":"small","memoryResources":"1Gi","difficulty":"beginner","enableEditor":true,"enableRegistry":true,"dockerStorage":5,"projectName":"k8s-playground"}
┃ ┃ ┃ ┃ ┗ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input85422201017798651, --data-values-file, /tmp/accelerator-options15447563315467642602.json, --output-files, /tmp/ytt-output14327644759235129206]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [workshop/modules.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml matched [workshop/modules.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"maxSessions":10,"bsGitBranch":"main","consoleVendor":"octant","enableDocker":true,"enableTerminal":true,"duration":"2h","dockerMemory":768,"exercises":["Using vCluster"],"workshopDescription":"A Kubernetes Playground based on vCluster","workshopFilesUrl":"github.com/vrabbi-tap/learning-center-k8s-playground","artifactId":"k8s-playground","registryStorage":5,"terminalLayout":"split","enableConsole":true,"artifactVersion":"0.0.1-beta","registryMemory":768,"workshopTitle":"Kubernetes Playground","bsGitRepository":"github.com?owner=vrabbi&repo=learning-center-k8s-playground","namespaceBudget":"small","memoryResources":"1Gi","difficulty":"beginner","enableEditor":true,"enableRegistry":true,"dockerStorage":5,"projectName":"k8s-playground"}
┃ ┃ ┃ ┃ ┗ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input9522332108725730228, --data-values-file, /tmp/accelerator-options7193958547309324698.json, --output-files, /tmp/ytt-output11342458666819987685]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 0) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 0) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [workshop/content/exercises/0.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md matched [workshop/content/exercises/0.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [replace me-># Using vCluster]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'workshop/content/exercises/0.md' matched 'workshop/content/exercises/0.md' with groups {g0=workshop/content/exercises/0.md} and was rewritten to 'workshop/content/exercises/using-vcluster.md'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 1) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[6] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 2) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[7] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 3) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[8] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 4) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[9] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 5) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[10] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 6) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[11] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 7) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[12] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 8) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[13] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 9) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[14] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[14].include (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh]
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md matched [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> included
┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md matched [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> included
┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md matched [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> included
┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh matched [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> included
┃ ┃ ┃ ┗ ┗ Debug workshop/workshop.yaml didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setup.d/setup-resources.sh] -> excluded
┃ ┗ ┗ ╺ engine.transformations[0].validated.merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
