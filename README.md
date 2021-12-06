2021-12-03T08:01:11.5629561Z Found online and idle hosted runner in the current repository's organization account that matches the required labels: 'ubuntu-latest'
2021-12-03T08:01:11.6168097Z Waiting for a Hosted runner in the 'organization' to pick this job...
2021-12-03T08:01:12.0905029Z Job is waiting for a hosted runner to come online.
2021-12-03T08:01:14.9956927Z Job is about to start running on the hosted runner: GitHub Actions 3 (hosted)
2021-12-03T08:01:18.8292308Z Current runner version: '2.285.0'
2021-12-03T08:01:18.8318193Z ##[group]Operating System
2021-12-03T08:01:18.8319035Z Ubuntu
2021-12-03T08:01:18.8319461Z 20.04.3
2021-12-03T08:01:18.8319852Z LTS
2021-12-03T08:01:18.8320292Z ##[endgroup]
2021-12-03T08:01:18.8320791Z ##[group]Virtual Environment
2021-12-03T08:01:18.8321387Z Environment: ubuntu-20.04
2021-12-03T08:01:18.8321916Z Version: 20211129.1
2021-12-03T08:01:18.8322849Z Included Software: https://github.com/actions/virtual-environments/blob/ubuntu20/20211129.1/images/linux/Ubuntu2004-README.md
2021-12-03T08:01:18.8324149Z Image Release: https://github.com/actions/virtual-environments/releases/tag/ubuntu20%2F20211129.1
2021-12-03T08:01:18.8324947Z ##[endgroup]
2021-12-03T08:01:18.8325522Z ##[group]Virtual Environment Provisioner
2021-12-03T08:01:18.8326137Z 1.0.0.0-master-20211123-1
2021-12-03T08:01:18.8326606Z ##[endgroup]
2021-12-03T08:01:18.8328415Z ##[group]GITHUB_TOKEN Permissions
2021-12-03T08:01:18.8329585Z Actions: read
2021-12-03T08:01:18.8330057Z Checks: read
2021-12-03T08:01:18.8330534Z Contents: read
2021-12-03T08:01:18.8330997Z Deployments: read
2021-12-03T08:01:18.8331502Z Discussions: read
2021-12-03T08:01:18.8331981Z Issues: read
2021-12-03T08:01:18.8332407Z Metadata: read
2021-12-03T08:01:18.8332912Z Packages: read
2021-12-03T08:01:18.8333344Z Pages: read
2021-12-03T08:01:18.8333834Z PullRequests: read
2021-12-03T08:01:18.8334376Z RepositoryProjects: read
2021-12-03T08:01:18.8334984Z SecurityEvents: read
2021-12-03T08:01:18.8335471Z Statuses: read
2021-12-03T08:01:18.8336018Z ##[endgroup]
2021-12-03T08:01:18.8338685Z Secret source: None
2021-12-03T08:01:18.8339452Z Prepare workflow directory
2021-12-03T08:01:18.8921671Z Prepare all required actions
2021-12-03T08:01:18.8931310Z Getting action download info
2021-12-03T08:01:19.2239768Z Download action repository 'actions/checkout@v2' (SHA:ec3a7ce113134d7a93b817d10a8272cb61118579)
2021-12-03T08:01:20.9615234Z Download action repository 'github/super-linter@v4' (SHA:563be7dc5568017515b9e700329e9c6d3862f2b7)
2021-12-03T08:01:21.7756859Z ##[group]Pull down action image 'ghcr.io/github/super-linter:slim-v4'
2021-12-03T08:01:21.7804879Z ##[command]/usr/bin/docker pull ghcr.io/github/super-linter:slim-v4
2021-12-03T08:01:22.9627383Z slim-v4: Pulling from github/super-linter
2021-12-03T08:01:22.9628574Z 97518928ae5f: Already exists
2021-12-03T08:01:22.9629201Z ccf0a854052d: Pulling fs layer
2021-12-03T08:01:22.9629723Z e1d00c971a15: Pulling fs layer
2021-12-03T08:01:22.9630415Z b383af4cd6d8: Pulling fs layer
2021-12-03T08:01:22.9630931Z 0676bc7ea9bf: Pulling fs layer
2021-12-03T08:01:22.9631441Z 4ea6790f8c4e: Pulling fs layer
2021-12-03T08:01:22.9631970Z 3fe800bac3a2: Pulling fs layer
2021-12-03T08:01:22.9632475Z f14db6a77ba7: Pulling fs layer
2021-12-03T08:01:22.9632968Z d3e87ff09f2d: Pulling fs layer
2021-12-03T08:01:22.9633469Z 9d663d20c84b: Pulling fs layer
2021-12-03T08:01:22.9633971Z e9b0cc5d3407: Pulling fs layer
2021-12-03T08:01:22.9634451Z b53577466a62: Pulling fs layer
2021-12-03T08:01:22.9635004Z 1cb8f9284bb1: Pulling fs layer
2021-12-03T08:01:22.9635493Z a53103dea484: Pulling fs layer
2021-12-03T08:01:22.9635992Z 1a0bbfd870a0: Pulling fs layer
2021-12-03T08:01:22.9636490Z fd2c9d26e918: Pulling fs layer
2021-12-03T08:01:22.9636992Z fa1fa62b20b5: Pulling fs layer
2021-12-03T08:01:22.9637483Z 9c491a9090d4: Pulling fs layer
2021-12-03T08:01:22.9637935Z 0676bc7ea9bf: Waiting
2021-12-03T08:01:22.9638382Z 4ea6790f8c4e: Waiting
2021-12-03T08:01:22.9638836Z 3fe800bac3a2: Waiting
2021-12-03T08:01:22.9639296Z f14db6a77ba7: Waiting
2021-12-03T08:01:22.9639750Z d3e87ff09f2d: Waiting
2021-12-03T08:01:22.9640182Z 9d663d20c84b: Waiting
2021-12-03T08:01:22.9640630Z e9b0cc5d3407: Waiting
2021-12-03T08:01:22.9641065Z b53577466a62: Waiting
2021-12-03T08:01:22.9641484Z 1cb8f9284bb1: Waiting
2021-12-03T08:01:22.9641922Z a53103dea484: Waiting
2021-12-03T08:01:22.9642372Z 1a0bbfd870a0: Waiting
2021-12-03T08:01:22.9642823Z fd2c9d26e918: Waiting
2021-12-03T08:01:22.9643280Z fa1fa62b20b5: Waiting
2021-12-03T08:01:22.9643709Z 9c491a9090d4: Waiting
2021-12-03T08:01:23.2725082Z b383af4cd6d8: Verifying Checksum
2021-12-03T08:01:23.2725801Z b383af4cd6d8: Download complete
2021-12-03T08:01:23.3579937Z ccf0a854052d: Verifying Checksum
2021-12-03T08:01:23.3580731Z ccf0a854052d: Download complete
2021-12-03T08:01:23.7379669Z 4ea6790f8c4e: Verifying Checksum
2021-12-03T08:01:23.7380317Z 4ea6790f8c4e: Download complete
2021-12-03T08:01:24.6129468Z 0676bc7ea9bf: Verifying Checksum
2021-12-03T08:01:24.6187865Z 0676bc7ea9bf: Download complete
2021-12-03T08:01:25.2183369Z f14db6a77ba7: Verifying Checksum
2021-12-03T08:01:25.2183968Z f14db6a77ba7: Download complete
2021-12-03T08:01:25.9319266Z d3e87ff09f2d: Verifying Checksum
2021-12-03T08:01:25.9323157Z d3e87ff09f2d: Download complete
2021-12-03T08:01:26.3481306Z 9d663d20c84b: Verifying Checksum
2021-12-03T08:01:26.3484624Z 9d663d20c84b: Download complete
2021-12-03T08:01:26.7338370Z e1d00c971a15: Verifying Checksum
2021-12-03T08:01:26.7341927Z e1d00c971a15: Download complete
2021-12-03T08:01:26.7483293Z e9b0cc5d3407: Verifying Checksum
2021-12-03T08:01:26.7487453Z e9b0cc5d3407: Download complete
2021-12-03T08:01:27.4336800Z 1cb8f9284bb1: Verifying Checksum
2021-12-03T08:01:27.4338320Z 1cb8f9284bb1: Download complete
2021-12-03T08:01:27.5423444Z b53577466a62: Verifying Checksum
2021-12-03T08:01:27.5424027Z b53577466a62: Download complete
2021-12-03T08:01:27.8888281Z 1a0bbfd870a0: Verifying Checksum
2021-12-03T08:01:27.8888912Z 1a0bbfd870a0: Download complete
2021-12-03T08:01:27.9225553Z a53103dea484: Verifying Checksum
2021-12-03T08:01:27.9229991Z a53103dea484: Download complete
2021-12-03T08:01:28.1507618Z fd2c9d26e918: Verifying Checksum
2021-12-03T08:01:28.1508336Z fd2c9d26e918: Download complete
2021-12-03T08:01:28.1940566Z fa1fa62b20b5: Verifying Checksum
2021-12-03T08:01:28.1941123Z fa1fa62b20b5: Download complete
2021-12-03T08:01:28.4454910Z 9c491a9090d4: Verifying Checksum
2021-12-03T08:01:28.4455418Z 9c491a9090d4: Download complete
2021-12-03T08:01:28.4455884Z 3fe800bac3a2: Verifying Checksum
2021-12-03T08:01:28.4456627Z 3fe800bac3a2: Download complete
2021-12-03T08:01:32.5094891Z ccf0a854052d: Pull complete
2021-12-03T08:01:43.9990762Z e1d00c971a15: Pull complete
2021-12-03T08:01:44.2492303Z b383af4cd6d8: Pull complete
2021-12-03T08:01:51.9544688Z 0676bc7ea9bf: Pull complete
2021-12-03T08:01:52.3082760Z 4ea6790f8c4e: Pull complete
2021-12-03T08:02:10.5449021Z 3fe800bac3a2: Pull complete
2021-12-03T08:02:12.1062883Z f14db6a77ba7: Pull complete
2021-12-03T08:02:12.8514632Z d3e87ff09f2d: Pull complete
2021-12-03T08:02:12.9220067Z 9d663d20c84b: Pull complete
2021-12-03T08:02:12.9769649Z e9b0cc5d3407: Pull complete
2021-12-03T08:02:19.1109327Z b53577466a62: Pull complete
2021-12-03T08:02:20.3496950Z 1cb8f9284bb1: Pull complete
2021-12-03T08:02:21.1534355Z a53103dea484: Pull complete
2021-12-03T08:02:21.2324217Z 1a0bbfd870a0: Pull complete
2021-12-03T08:02:21.3035104Z fd2c9d26e918: Pull complete
2021-12-03T08:02:21.3677626Z fa1fa62b20b5: Pull complete
2021-12-03T08:02:21.4708851Z 9c491a9090d4: Pull complete
2021-12-03T08:02:21.4745663Z Digest: sha256:f1cc4d33f7a6f14e289591a86e389ef0cef681097e3d78d6b8001ec6162ac33f
2021-12-03T08:02:21.4760952Z Status: Downloaded newer image for ghcr.io/github/super-linter:slim-v4
2021-12-03T08:02:21.4788536Z ghcr.io/github/super-linter:slim-v4
2021-12-03T08:02:21.4799581Z ##[endgroup]
2021-12-03T08:02:21.5071793Z ##[group]Run actions/checkout@v2
2021-12-03T08:02:21.5072316Z with:
2021-12-03T08:02:21.5072647Z   fetch-depth: 0
2021-12-03T08:02:21.5073161Z   repository: actions/virtual-environments
2021-12-03T08:02:21.5074059Z   token: ***
2021-12-03T08:02:21.5074395Z   ssh-strict: true
2021-12-03T08:02:21.5074834Z   persist-credentials: true
2021-12-03T08:02:21.5075243Z   clean: true
2021-12-03T08:02:21.5075554Z   lfs: false
2021-12-03T08:02:21.5075887Z   submodules: false
2021-12-03T08:02:21.5076239Z ##[endgroup]
2021-12-03T08:02:21.7460261Z Syncing repository: actions/virtual-environments
2021-12-03T08:02:21.7461681Z ##[group]Getting Git version info
2021-12-03T08:02:21.7463111Z Working directory is '/home/runner/work/virtual-environments/virtual-environments'
2021-12-03T08:02:21.7464499Z [command]/usr/bin/git version
2021-12-03T08:02:21.7564179Z git version 2.34.1
2021-12-03T08:02:21.7585298Z ##[endgroup]
2021-12-03T08:02:21.7591493Z Deleting the contents of '/home/runner/work/virtual-environments/virtual-environments'
2021-12-03T08:02:21.7595365Z ##[group]Initializing the repository
2021-12-03T08:02:21.7599345Z [command]/usr/bin/git init /home/runner/work/virtual-environments/virtual-environments
2021-12-03T08:02:21.7675776Z hint: Using 'master' as the name for the initial branch. This default branch name
2021-12-03T08:02:21.7676885Z hint: is subject to change. To configure the initial branch name to use in all
2021-12-03T08:02:21.7677798Z hint: of your new repositories, which will suppress this warning, call:
2021-12-03T08:02:21.7678605Z hint: 
2021-12-03T08:02:21.7679556Z hint: 	git config --global init.defaultBranch <name>
2021-12-03T08:02:21.7680162Z hint: 
2021-12-03T08:02:21.7680928Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2021-12-03T08:02:21.7682031Z hint: 'development'. The just-created branch can be renamed via this command:
2021-12-03T08:02:21.7682681Z hint: 
2021-12-03T08:02:21.7683309Z hint: 	git branch -m <name>
2021-12-03T08:02:21.7689735Z Initialized empty Git repository in /home/runner/work/virtual-environments/virtual-environments/.git/
2021-12-03T08:02:21.7699569Z [command]/usr/bin/git remote add origin https://github.com/actions/virtual-environments
2021-12-03T08:02:21.7769710Z ##[endgroup]
2021-12-03T08:02:21.7770916Z ##[group]Disabling automatic garbage collection
2021-12-03T08:02:21.7777346Z [command]/usr/bin/git config --local gc.auto 0
2021-12-03T08:02:21.7819048Z ##[endgroup]
2021-12-03T08:02:21.7823940Z ##[group]Setting up auth
2021-12-03T08:02:21.7830300Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2021-12-03T08:02:21.7862140Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2021-12-03T08:02:21.8180183Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2021-12-03T08:02:21.8211078Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2021-12-03T08:02:21.8413949Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2021-12-03T08:02:21.8449292Z ##[endgroup]
2021-12-03T08:02:21.8450746Z ##[group]Fetching the repository
2021-12-03T08:02:21.8458763Z [command]/usr/bin/git -c protocol.version=2 fetch --prune --progress --no-recurse-submodules origin +refs/heads/*:refs/remotes/origin/* +refs/tags/*:refs/tags/* +95f279b601ca18bb6a1d17b55a8485fe042273d8:refs/remotes/pull/4645/merge
2021-12-03T08:02:22.4418967Z remote: Enumerating objects: 27359, done.        
2021-12-03T08:02:22.4442414Z remote: Counting objects:   0% (1/4231)        
2021-12-03T08:02:22.4443139Z remote: Counting objects:   1% (43/4231)        
2021-12-03T08:02:22.4443687Z remote: Counting objects:   2% (85/4231)        
2021-12-03T08:02:22.4444926Z remote: Counting objects:   3% (127/4231)        
2021-12-03T08:02:22.4445486Z remote: Counting objects:   4% (170/4231)        
2021-12-03T08:02:22.4446055Z remote: Counting objects:   5% (212/4231)        
2021-12-03T08:02:22.4446548Z remote: Counting objects:   6% (254/4231)        
2021-12-03T08:02:22.4447030Z remote: Counting objects:   7% (297/4231)        
2021-12-03T08:02:22.4447509Z remote: Counting objects:   8% (339/4231)        
2021-12-03T08:02:22.4448007Z remote: Counting objects:   9% (381/4231)        
2021-12-03T08:02:22.4474202Z remote: Counting objects:  10% (424/4231)        
2021-12-03T08:02:22.4475585Z remote: Counting objects:  11% (466/4231)        
2021-12-03T08:02:22.4482428Z remote: Counting objects:  12% (508/4231)        
2021-12-03T08:02:22.4483409Z remote: Counting objects:  13% (551/4231)        
2021-12-03T08:02:22.4484232Z remote: Counting objects:  14% (593/4231)        
2021-12-03T08:02:22.4484814Z remote: Counting objects:  15% (635/4231)        
2021-12-03T08:02:22.4485361Z remote: Counting objects:  16% (677/4231)        
2021-12-03T08:02:22.4485959Z remote: Counting objects:  17% (720/4231)        
2021-12-03T08:02:22.4486483Z remote: Counting objects:  18% (762/4231)        
2021-12-03T08:02:22.4487058Z remote: Counting objects:  19% (804/4231)        
2021-12-03T08:02:22.4487575Z remote: Counting objects:  20% (847/4231)        
2021-12-03T08:02:22.4490651Z remote: Counting objects:  21% (889/4231)        
2021-12-03T08:02:22.4491277Z remote: Counting objects:  22% (931/4231)        
2021-12-03T08:02:22.4491951Z remote: Counting objects:  23% (974/4231)        
2021-12-03T08:02:22.4492857Z remote: Counting objects:  24% (1016/4231)        
2021-12-03T08:02:22.4493353Z remote: Counting objects:  25% (1058/4231)        
2021-12-03T08:02:22.4493872Z remote: Counting objects:  26% (1101/4231)        
2021-12-03T08:02:22.4494400Z remote: Counting objects:  27% (1143/4231)        
2021-12-03T08:02:22.4494985Z remote: Counting objects:  28% (1185/4231)        
2021-12-03T08:02:22.4495485Z remote: Counting objects:  29% (1227/4231)        
2021-12-03T08:02:22.4495967Z remote: Counting objects:  30% (1270/4231)        
2021-12-03T08:02:22.4496526Z remote: Counting objects:  31% (1312/4231)        
2021-12-03T08:02:22.4496977Z remote: Counting objects:  32% (1354/4231)        
2021-12-03T08:02:22.4497444Z remote: Counting objects:  33% (1397/4231)        
2021-12-03T08:02:22.4497892Z remote: Counting objects:  34% (1439/4231)        
2021-12-03T08:02:22.4498329Z remote: Counting objects:  35% (1481/4231)        
2021-12-03T08:02:22.4498774Z remote: Counting objects:  36% (1524/4231)        
2021-12-03T08:02:22.4499224Z remote: Counting objects:  37% (1566/4231)        
2021-12-03T08:02:22.4499660Z remote: Counting objects:  38% (1608/4231)        
2021-12-03T08:02:22.4500098Z remote: Counting objects:  39% (1651/4231)        
2021-12-03T08:02:22.4500680Z remote: Counting objects:  40% (1693/4231)        
2021-12-03T08:02:22.4501122Z remote: Counting objects:  41% (1735/4231)        
2021-12-03T08:02:22.4501693Z remote: Counting objects:  42% (1778/4231)        
2021-12-03T08:02:22.4502155Z remote: Counting objects:  43% (1820/4231)        
2021-12-03T08:02:22.4502594Z remote: Counting objects:  44% (1862/4231)        
2021-12-03T08:02:22.4503034Z remote: Counting objects:  45% (1904/4231)        
2021-12-03T08:02:22.4503469Z remote: Counting objects:  46% (1947/4231)        
2021-12-03T08:02:22.4503898Z remote: Counting objects:  47% (1989/4231)        
2021-12-03T08:02:22.4504331Z remote: Counting objects:  48% (2031/4231)        
2021-12-03T08:02:22.4504774Z remote: Counting objects:  49% (2074/4231)        
2021-12-03T08:02:22.4505204Z remote: Counting objects:  50% (2116/4231)        
2021-12-03T08:02:22.4505757Z remote: Counting objects:  51% (2158/4231)        
2021-12-03T08:02:22.4506193Z remote: Counting objects:  52% (2201/4231)        
2021-12-03T08:02:22.4506667Z remote: Counting objects:  53% (2243/4231)        
2021-12-03T08:02:22.4507246Z remote: Counting objects:  54% (2285/4231)        
2021-12-03T08:02:22.4507875Z remote: Counting objects:  55% (2328/4231)        
2021-12-03T08:02:22.4508335Z remote: Counting objects:  56% (2370/4231)        
2021-12-03T08:02:22.4508772Z remote: Counting objects:  57% (2412/4231)        
2021-12-03T08:02:22.4509250Z remote: Counting objects:  58% (2454/4231)        
2021-12-03T08:02:22.4509693Z remote: Counting objects:  59% (2497/4231)        
2021-12-03T08:02:22.4510243Z remote: Counting objects:  60% (2539/4231)        
2021-12-03T08:02:22.4510697Z remote: Counting objects:  61% (2581/4231)        
2021-12-03T08:02:22.4511165Z remote: Counting objects:  62% (2624/4231)        
2021-12-03T08:02:22.4511607Z remote: Counting objects:  63% (2666/4231)        
2021-12-03T08:02:22.4512341Z remote: Counting objects:  64% (2708/4231)        
2021-12-03T08:02:22.4512782Z remote: Counting objects:  65% (2751/4231)        
2021-12-03T08:02:22.4513222Z remote: Counting objects:  66% (2793/4231)        
2021-12-03T08:02:22.4513666Z remote: Counting objects:  67% (2835/4231)        
2021-12-03T08:02:22.4514107Z remote: Counting objects:  68% (2878/4231)        
2021-12-03T08:02:22.4514545Z remote: Counting objects:  69% (2920/4231)        
2021-12-03T08:02:22.4514972Z remote: Counting objects:  70% (2962/4231)        
2021-12-03T08:02:22.4515404Z remote: Counting objects:  71% (3005/4231)        
2021-12-03T08:02:22.4515962Z remote: Counting objects:  72% (3047/4231)        
2021-12-03T08:02:22.4516397Z remote: Counting objects:  73% (3089/4231)        
2021-12-03T08:02:22.4516833Z remote: Counting objects:  74% (3131/4231)        
2021-12-03T08:02:22.4517288Z remote: Counting objects:  75% (3174/4231)        
2021-12-03T08:02:22.4517724Z remote: Counting objects:  76% (3216/4231)        
2021-12-03T08:02:22.4518159Z remote: Counting objects:  77% (3258/4231)        
2021-12-03T08:02:22.4518596Z remote: Counting objects:  78% (3301/4231)        
2021-12-03T08:02:22.4519029Z remote: Counting objects:  79% (3343/4231)        
2021-12-03T08:02:22.4519559Z remote: Counting objects:  80% (3385/4231)        
2021-12-03T08:02:22.4519999Z remote: Counting objects:  81% (3428/4231)        
2021-12-03T08:02:22.4520459Z remote: Counting objects:  82% (3470/4231)        
2021-12-03T08:02:22.4520993Z remote: Counting objects:  83% (3512/4231)        
2021-12-03T08:02:22.4521431Z remote: Counting objects:  84% (3555/4231)        
2021-12-03T08:02:22.4521871Z remote: Counting objects:  85% (3597/4231)        
2021-12-03T08:02:22.4522312Z remote: Counting objects:  86% (3639/4231)        
2021-12-03T08:02:22.4522841Z remote: Counting objects:  87% (3681/4231)        
2021-12-03T08:02:22.4523274Z remote: Counting objects:  88% (3724/4231)        
2021-12-03T08:02:22.4523706Z remote: Counting objects:  89% (3766/4231)        
2021-12-03T08:02:22.4524153Z remote: Counting objects:  90% (3808/4231)        
2021-12-03T08:02:22.4524587Z remote: Counting objects:  91% (3851/4231)        
2021-12-03T08:02:22.4525059Z remote: Counting objects:  92% (3893/4231)        
2021-12-03T08:02:22.4525503Z remote: Counting objects:  93% (3935/4231)        
2021-12-03T08:02:22.4525965Z remote: Counting objects:  94% (3978/4231)        
2021-12-03T08:02:22.4526405Z remote: Counting objects:  95% (4020/4231)        
2021-12-03T08:02:22.4526837Z remote: Counting objects:  96% (4062/4231)        
2021-12-03T08:02:22.4527271Z remote: Counting objects:  97% (4105/4231)        
2021-12-03T08:02:22.4527710Z remote: Counting objects:  98% (4147/4231)        
2021-12-03T08:02:22.4528144Z remote: Counting objects:  99% (4189/4231)        
2021-12-03T08:02:22.4528582Z remote: Counting objects: 100% (4231/4231)        
2021-12-03T08:02:22.4529043Z remote: Counting objects: 100% (4231/4231), done.        
2021-12-03T08:02:22.4529555Z remote: Compressing objects:   0% (1/509)        
2021-12-03T08:02:22.4530056Z remote: Compressing objects:   1% (6/509)        
2021-12-03T08:02:22.4530582Z remote: Compressing objects:   2% (11/509)        
2021-12-03T08:02:22.4531062Z remote: Compressing objects:   3% (16/509)        
2021-12-03T08:02:22.4531613Z remote: Compressing objects:   4% (21/509)        
2021-12-03T08:02:22.4532109Z remote: Compressing objects:   5% (26/509)        
2021-12-03T08:02:22.4532595Z remote: Compressing objects:   6% (31/509)        
2021-12-03T08:02:22.4533072Z remote: Compressing objects:   7% (36/509)        
2021-12-03T08:02:22.4533551Z remote: Compressing objects:   8% (41/509)        
2021-12-03T08:02:22.4534023Z remote: Compressing objects:   9% (46/509)        
2021-12-03T08:02:22.4534505Z remote: Compressing objects:  10% (51/509)        
2021-12-03T08:02:22.4540394Z remote: Compressing objects:  11% (56/509)        
2021-12-03T08:02:22.4546731Z remote: Compressing objects:  12% (62/509)        
2021-12-03T08:02:22.4553707Z remote: Compressing objects:  13% (67/509)        
2021-12-03T08:02:22.4556500Z remote: Compressing objects:  14% (72/509)        
2021-12-03T08:02:22.4568788Z remote: Compressing objects:  15% (77/509)        
2021-12-03T08:02:22.4634352Z remote: Compressing objects:  16% (82/509)        
2021-12-03T08:02:22.4666507Z remote: Compressing objects:  17% (87/509)        
2021-12-03T08:02:22.4728874Z remote: Compressing objects:  18% (92/509)        
2021-12-03T08:02:22.4752719Z remote: Compressing objects:  19% (97/509)        
2021-12-03T08:02:22.4779522Z remote: Compressing objects:  20% (102/509)        
2021-12-03T08:02:22.4791671Z remote: Compressing objects:  21% (107/509)        
2021-12-03T08:02:22.4833204Z remote: Compressing objects:  22% (112/509)        
2021-12-03T08:02:22.4856855Z remote: Compressing objects:  23% (118/509)        
2021-12-03T08:02:22.4891793Z remote: Compressing objects:  24% (123/509)        
2021-12-03T08:02:22.4901790Z remote: Compressing objects:  25% (128/509)        
2021-12-03T08:02:22.4925002Z remote: Compressing objects:  26% (133/509)        
2021-12-03T08:02:22.4939954Z remote: Compressing objects:  27% (138/509)        
2021-12-03T08:02:22.4967611Z remote: Compressing objects:  28% (143/509)        
2021-12-03T08:02:22.4978897Z remote: Compressing objects:  29% (148/509)        
2021-12-03T08:02:22.4985418Z remote: Compressing objects:  30% (153/509)        
2021-12-03T08:02:22.4997097Z remote: Compressing objects:  31% (158/509)        
2021-12-03T08:02:22.5007498Z remote: Compressing objects:  32% (163/509)        
2021-12-03T08:02:22.5022577Z remote: Compressing objects:  33% (168/509)        
2021-12-03T08:02:22.5029944Z remote: Compressing objects:  34% (174/509)        
2021-12-03T08:02:22.5036740Z remote: Compressing objects:  35% (179/509)        
2021-12-03T08:02:22.5042910Z remote: Compressing objects:  36% (184/509)        
2021-12-03T08:02:22.5050032Z remote: Compressing objects:  37% (189/509)        
2021-12-03T08:02:22.5053065Z remote: Compressing objects:  38% (194/509)        
2021-12-03T08:02:22.5057381Z remote: Compressing objects:  39% (199/509)        
2021-12-03T08:02:22.5061660Z remote: Compressing objects:  40% (204/509)        
2021-12-03T08:02:22.5062845Z remote: Compressing objects:  41% (209/509)        
2021-12-03T08:02:22.5063415Z remote: Compressing objects:  42% (214/509)        
2021-12-03T08:02:22.5065299Z remote: Compressing objects:  43% (219/509)        
2021-12-03T08:02:22.5069815Z remote: Compressing objects:  44% (224/509)        
2021-12-03T08:02:22.5070311Z remote: Compressing objects:  45% (230/509)        
2021-12-03T08:02:22.5070807Z remote: Compressing objects:  46% (235/509)        
2021-12-03T08:02:22.5071285Z remote: Compressing objects:  47% (240/509)        
2021-12-03T08:02:22.5079978Z remote: Compressing objects:  48% (245/509)        
2021-12-03T08:02:22.5080484Z remote: Compressing objects:  49% (250/509)        
2021-12-03T08:02:22.5085182Z remote: Compressing objects:  50% (255/509)        
2021-12-03T08:02:22.5087372Z remote: Compressing objects:  51% (260/509)        
2021-12-03T08:02:22.5092186Z remote: Compressing objects:  52% (265/509)        
2021-12-03T08:02:22.5092710Z remote: Compressing objects:  53% (270/509)        
2021-12-03T08:02:22.5094969Z remote: Compressing objects:  54% (275/509)        
2021-12-03T08:02:22.5095695Z remote: Compressing objects:  55% (280/509)        
2021-12-03T08:02:22.5096569Z remote: Compressing objects:  56% (286/509)        
2021-12-03T08:02:22.5098471Z remote: Compressing objects:  57% (291/509)        
2021-12-03T08:02:22.5099896Z remote: Compressing objects:  58% (296/509)        
2021-12-03T08:02:22.5100405Z remote: Compressing objects:  59% (301/509)        
2021-12-03T08:02:22.5100903Z remote: Compressing objects:  60% (306/509)        
2021-12-03T08:02:22.5111821Z remote: Compressing objects:  61% (311/509)        
2021-12-03T08:02:22.5112385Z remote: Compressing objects:  62% (316/509)        
2021-12-03T08:02:22.5112866Z remote: Compressing objects:  63% (321/509)        
2021-12-03T08:02:22.5113617Z remote: Compressing objects:  64% (326/509)        
2021-12-03T08:02:22.5114187Z remote: Compressing objects:  65% (331/509)        
2021-12-03T08:02:22.5114667Z remote: Compressing objects:  66% (336/509)        
2021-12-03T08:02:22.5115193Z remote: Compressing objects:  67% (342/509)        
2021-12-03T08:02:22.5115665Z remote: Compressing objects:  68% (347/509)        
2021-12-03T08:02:22.5116144Z remote: Compressing objects:  69% (352/509)        
2021-12-03T08:02:22.5116611Z remote: Compressing objects:  70% (357/509)        
2021-12-03T08:02:22.5119972Z remote: Compressing objects:  71% (362/509)        
2021-12-03T08:02:22.5121131Z remote: Compressing objects:  72% (367/509)        
2021-12-03T08:02:22.5121827Z remote: Compressing objects:  73% (372/509)        
2021-12-03T08:02:22.5122322Z remote: Compressing objects:  74% (377/509)        
2021-12-03T08:02:22.5122808Z remote: Compressing objects:  75% (382/509)        
2021-12-03T08:02:22.5123334Z remote: Compressing objects:  76% (387/509)        
2021-12-03T08:02:22.5123809Z remote: Compressing objects:  77% (392/509)        
2021-12-03T08:02:22.5124828Z remote: Compressing objects:  78% (398/509)        
2021-12-03T08:02:22.5125308Z remote: Compressing objects:  79% (403/509)        
2021-12-03T08:02:22.5125787Z remote: Compressing objects:  80% (408/509)        
2021-12-03T08:02:22.5126364Z remote: Compressing objects:  81% (413/509)        
2021-12-03T08:02:22.5126841Z remote: Compressing objects:  82% (418/509)        
2021-12-03T08:02:22.5127854Z remote: Compressing objects:  83% (423/509)        
2021-12-03T08:02:22.5128365Z remote: Compressing objects:  84% (428/509)        
2021-12-03T08:02:22.5128850Z remote: Compressing objects:  85% (433/509)        
2021-12-03T08:02:22.5129325Z remote: Compressing objects:  86% (438/509)        
2021-12-03T08:02:22.5130102Z remote: Compressing objects:  87% (443/509)        
2021-12-03T08:02:22.5130855Z remote: Compressing objects:  88% (448/509)        
2021-12-03T08:02:22.5131378Z remote: Compressing objects:  89% (454/509)        
2021-12-03T08:02:22.5132175Z remote: Compressing objects:  90% (459/509)        
2021-12-03T08:02:22.5132655Z remote: Compressing objects:  91% (464/509)        
2021-12-03T08:02:22.5133169Z remote: Compressing objects:  92% (469/509)        
2021-12-03T08:02:22.5133643Z remote: Compressing objects:  93% (474/509)        
2021-12-03T08:02:22.5134122Z remote: Compressing objects:  94% (479/509)        
2021-12-03T08:02:22.5134623Z remote: Compressing objects:  95% (484/509)        
2021-12-03T08:02:22.5135096Z remote: Compressing objects:  96% (489/509)        
2021-12-03T08:02:22.5135568Z remote: Compressing objects:  97% (494/509)        
2021-12-03T08:02:22.5136040Z remote: Compressing objects:  98% (499/509)        
2021-12-03T08:02:22.5136518Z remote: Compressing objects:  99% (504/509)        
2021-12-03T08:02:22.5137130Z remote: Compressing objects: 100% (509/509)        
2021-12-03T08:02:22.5137633Z remote: Compressing objects: 100% (509/509), done.        
2021-12-03T08:02:22.5471129Z Receiving objects:   0% (1/27359)
2021-12-03T08:02:22.5523943Z Receiving objects:   1% (274/27359)
2021-12-03T08:02:22.5759045Z Receiving objects:   2% (548/27359)
2021-12-03T08:02:22.5871860Z Receiving objects:   3% (821/27359)
2021-12-03T08:02:22.5914878Z Receiving objects:   4% (1095/27359)
2021-12-03T08:02:22.5975679Z Receiving objects:   5% (1368/27359)
2021-12-03T08:02:22.6090093Z Receiving objects:   6% (1642/27359)
2021-12-03T08:02:22.6155659Z Receiving objects:   7% (1916/27359)
2021-12-03T08:02:22.6207589Z Receiving objects:   8% (2189/27359)
2021-12-03T08:02:22.6250601Z Receiving objects:   9% (2463/27359)
2021-12-03T08:02:22.6289911Z Receiving objects:  10% (2736/27359)
2021-12-03T08:02:22.6320967Z Receiving objects:  11% (3010/27359)
2021-12-03T08:02:22.6352510Z Receiving objects:  12% (3284/27359)
2021-12-03T08:02:22.6383905Z Receiving objects:  13% (3557/27359)
2021-12-03T08:02:22.6540337Z Receiving objects:  14% (3831/27359)
2021-12-03T08:02:22.6616391Z Receiving objects:  15% (4104/27359)
2021-12-03T08:02:22.6635751Z Receiving objects:  16% (4378/27359)
2021-12-03T08:02:22.6660945Z Receiving objects:  17% (4652/27359)
2021-12-03T08:02:22.6671548Z Receiving objects:  18% (4925/27359)
2021-12-03T08:02:22.6680243Z Receiving objects:  19% (5199/27359)
2021-12-03T08:02:22.6692397Z Receiving objects:  20% (5472/27359)
2021-12-03T08:02:22.6702707Z Receiving objects:  21% (5746/27359)
2021-12-03T08:02:22.6717653Z Receiving objects:  22% (6019/27359)
2021-12-03T08:02:22.6730879Z Receiving objects:  23% (6293/27359)
2021-12-03T08:02:22.6744982Z Receiving objects:  24% (6567/27359)
2021-12-03T08:02:22.6759564Z Receiving objects:  25% (6840/27359)
2021-12-03T08:02:22.6768348Z Receiving objects:  26% (7114/27359)
2021-12-03T08:02:22.6776042Z Receiving objects:  27% (7387/27359)
2021-12-03T08:02:22.6791529Z Receiving objects:  28% (7661/27359)
2021-12-03T08:02:22.6804572Z Receiving objects:  29% (7935/27359)
2021-12-03T08:02:22.6820890Z Receiving objects:  30% (8208/27359)
2021-12-03T08:02:22.6837166Z Receiving objects:  31% (8482/27359)
2021-12-03T08:02:22.6851319Z Receiving objects:  32% (8755/27359)
2021-12-03T08:02:22.6884231Z Receiving objects:  33% (9029/27359)
2021-12-03T08:02:22.6932025Z Receiving objects:  34% (9303/27359)
2021-12-03T08:02:22.6932680Z Receiving objects:  35% (9576/27359)
2021-12-03T08:02:22.6933118Z Receiving objects:  36% (9850/27359)
2021-12-03T08:02:22.6947449Z Receiving objects:  37% (10123/27359)
2021-12-03T08:02:22.6952285Z Receiving objects:  38% (10397/27359)
2021-12-03T08:02:22.6958087Z Receiving objects:  39% (10671/27359)
2021-12-03T08:02:22.6970904Z Receiving objects:  40% (10944/27359)
2021-12-03T08:02:22.6988651Z Receiving objects:  41% (11218/27359)
2021-12-03T08:02:22.6999974Z Receiving objects:  42% (11491/27359)
2021-12-03T08:02:22.7010952Z Receiving objects:  43% (11765/27359)
2021-12-03T08:02:22.7021355Z Receiving objects:  44% (12038/27359)
2021-12-03T08:02:22.7027543Z Receiving objects:  45% (12312/27359)
2021-12-03T08:02:22.7033199Z Receiving objects:  46% (12586/27359)
2021-12-03T08:02:22.7039629Z Receiving objects:  47% (12859/27359)
2021-12-03T08:02:22.7045056Z Receiving objects:  48% (13133/27359)
2021-12-03T08:02:22.7051972Z Receiving objects:  49% (13406/27359)
2021-12-03T08:02:22.7065371Z Receiving objects:  50% (13680/27359)
2021-12-03T08:02:22.7070855Z Receiving objects:  51% (13954/27359)
2021-12-03T08:02:22.7076560Z Receiving objects:  52% (14227/27359)
2021-12-03T08:02:22.7083238Z Receiving objects:  53% (14501/27359)
2021-12-03T08:02:22.7089050Z Receiving objects:  54% (14774/27359)
2021-12-03T08:02:22.7094264Z Receiving objects:  55% (15048/27359)
2021-12-03T08:02:22.7100523Z Receiving objects:  56% (15322/27359)
2021-12-03T08:02:22.7106323Z Receiving objects:  57% (15595/27359)
2021-12-03T08:02:22.7111233Z Receiving objects:  58% (15869/27359)
2021-12-03T08:02:22.7118459Z Receiving objects:  59% (16142/27359)
2021-12-03T08:02:22.7124766Z Receiving objects:  60% (16416/27359)
2021-12-03T08:02:22.7130558Z Receiving objects:  61% (16689/27359)
2021-12-03T08:02:22.7138449Z Receiving objects:  62% (16963/27359)
2021-12-03T08:02:22.7143996Z Receiving objects:  63% (17237/27359)
2021-12-03T08:02:22.7148705Z Receiving objects:  64% (17510/27359)
2021-12-03T08:02:22.7155322Z Receiving objects:  65% (17784/27359)
2021-12-03T08:02:22.7163734Z Receiving objects:  66% (18057/27359)
2021-12-03T08:02:22.7169971Z Receiving objects:  67% (18331/27359)
2021-12-03T08:02:22.7177925Z Receiving objects:  68% (18605/27359)
2021-12-03T08:02:22.7183891Z Receiving objects:  69% (18878/27359)
2021-12-03T08:02:22.7190957Z Receiving objects:  70% (19152/27359)
2021-12-03T08:02:22.7195503Z Receiving objects:  71% (19425/27359)
2021-12-03T08:02:22.7201222Z Receiving objects:  72% (19699/27359)
2021-12-03T08:02:22.7208376Z Receiving objects:  73% (19973/27359)
2021-12-03T08:02:22.7214931Z Receiving objects:  74% (20246/27359)
2021-12-03T08:02:22.7220786Z Receiving objects:  75% (20520/27359)
2021-12-03T08:02:22.7226042Z Receiving objects:  76% (20793/27359)
2021-12-03T08:02:22.7231517Z Receiving objects:  77% (21067/27359)
2021-12-03T08:02:22.7236904Z Receiving objects:  78% (21341/27359)
2021-12-03T08:02:22.7245737Z Receiving objects:  79% (21614/27359)
2021-12-03T08:02:22.7256923Z Receiving objects:  80% (21888/27359)
2021-12-03T08:02:22.7259095Z Receiving objects:  81% (22161/27359)
2021-12-03T08:02:22.7264392Z Receiving objects:  82% (22435/27359)
2021-12-03T08:02:22.7282438Z Receiving objects:  83% (22708/27359)
2021-12-03T08:02:22.7307401Z Receiving objects:  84% (22982/27359)
2021-12-03T08:02:22.7313773Z Receiving objects:  85% (23256/27359)
2021-12-03T08:02:22.7316743Z Receiving objects:  86% (23529/27359)
2021-12-03T08:02:22.7320065Z Receiving objects:  87% (23803/27359)
2021-12-03T08:02:22.7324155Z Receiving objects:  88% (24076/27359)
2021-12-03T08:02:22.7327221Z Receiving objects:  89% (24350/27359)
2021-12-03T08:02:22.7330103Z Receiving objects:  90% (24624/27359)
2021-12-03T08:02:22.7333179Z Receiving objects:  91% (24897/27359)
2021-12-03T08:02:22.7337099Z Receiving objects:  92% (25171/27359)
2021-12-03T08:02:22.7355296Z Receiving objects:  93% (25444/27359)
2021-12-03T08:02:22.7440438Z Receiving objects:  94% (25718/27359)
2021-12-03T08:02:22.7492173Z Receiving objects:  95% (25992/27359)
2021-12-03T08:02:22.7513026Z Receiving objects:  96% (26265/27359)
2021-12-03T08:02:22.7529847Z Receiving objects:  97% (26539/27359)
2021-12-03T08:02:22.7556664Z Receiving objects:  98% (26812/27359)
2021-12-03T08:02:22.7570398Z Receiving objects:  99% (27086/27359)
2021-12-03T08:02:22.7571554Z remote: Total 27359 (delta 3931), reused 3853 (delta 3722), pack-reused 23128        
2021-12-03T08:02:22.7596634Z Receiving objects: 100% (27359/27359)
2021-12-03T08:02:22.7597186Z Receiving objects: 100% (27359/27359), 5.77 MiB | 23.63 MiB/s, done.
2021-12-03T08:02:22.7661060Z Resolving deltas:   0% (0/19296)
2021-12-03T08:02:22.7680730Z Resolving deltas:   1% (193/19296)
2021-12-03T08:02:22.7696882Z Resolving deltas:   2% (386/19296)
2021-12-03T08:02:22.7763593Z Resolving deltas:   3% (579/19296)
2021-12-03T08:02:22.7849684Z Resolving deltas:   4% (772/19296)
2021-12-03T08:02:22.7911127Z Resolving deltas:   5% (965/19296)
2021-12-03T08:02:22.7923615Z Resolving deltas:   6% (1158/19296)
2021-12-03T08:02:22.7941701Z Resolving deltas:   7% (1351/19296)
2021-12-03T08:02:22.8001318Z Resolving deltas:   8% (1544/19296)
2021-12-03T08:02:22.8036802Z Resolving deltas:   9% (1737/19296)
2021-12-03T08:02:22.8050277Z Resolving deltas:  10% (1930/19296)
2021-12-03T08:02:22.8064336Z Resolving deltas:  11% (2123/19296)
2021-12-03T08:02:22.8080399Z Resolving deltas:  12% (2316/19296)
2021-12-03T08:02:22.8140895Z Resolving deltas:  13% (2509/19296)
2021-12-03T08:02:22.8179935Z Resolving deltas:  14% (2702/19296)
2021-12-03T08:02:22.8197890Z Resolving deltas:  15% (2895/19296)
2021-12-03T08:02:22.8218038Z Resolving deltas:  16% (3088/19296)
2021-12-03T08:02:22.8233339Z Resolving deltas:  17% (3281/19296)
2021-12-03T08:02:22.8253328Z Resolving deltas:  18% (3474/19296)
2021-12-03T08:02:22.8273941Z Resolving deltas:  19% (3667/19296)
2021-12-03T08:02:22.8281073Z Resolving deltas:  20% (3860/19296)
2021-12-03T08:02:22.8288620Z Resolving deltas:  21% (4053/19296)
2021-12-03T08:02:22.8295325Z Resolving deltas:  22% (4246/19296)
2021-12-03T08:02:22.8301272Z Resolving deltas:  23% (4439/19296)
2021-12-03T08:02:22.8309317Z Resolving deltas:  24% (4632/19296)
2021-12-03T08:02:22.8316801Z Resolving deltas:  25% (4824/19296)
2021-12-03T08:02:22.8327754Z Resolving deltas:  26% (5017/19296)
2021-12-03T08:02:22.8334840Z Resolving deltas:  27% (5210/19296)
2021-12-03T08:02:22.8343293Z Resolving deltas:  28% (5403/19296)
2021-12-03T08:02:22.8352158Z Resolving deltas:  29% (5596/19296)
2021-12-03T08:02:22.8359913Z Resolving deltas:  30% (5789/19296)
2021-12-03T08:02:22.8375031Z Resolving deltas:  31% (5982/19296)
2021-12-03T08:02:22.8392123Z Resolving deltas:  32% (6175/19296)
2021-12-03T08:02:22.8404286Z Resolving deltas:  33% (6368/19296)
2021-12-03T08:02:22.8416526Z Resolving deltas:  34% (6561/19296)
2021-12-03T08:02:22.8426954Z Resolving deltas:  35% (6754/19296)
2021-12-03T08:02:22.8439895Z Resolving deltas:  36% (6947/19296)
2021-12-03T08:02:22.8445207Z Resolving deltas:  37% (7140/19296)
2021-12-03T08:02:22.8455200Z Resolving deltas:  38% (7333/19296)
2021-12-03T08:02:22.8466570Z Resolving deltas:  39% (7526/19296)
2021-12-03T08:02:22.8499300Z Resolving deltas:  40% (7719/19296)
2021-12-03T08:02:22.8512465Z Resolving deltas:  41% (7912/19296)
2021-12-03T08:02:22.8552462Z Resolving deltas:  42% (8105/19296)
2021-12-03T08:02:22.8576721Z Resolving deltas:  43% (8298/19296)
2021-12-03T08:02:22.8595253Z Resolving deltas:  44% (8491/19296)
2021-12-03T08:02:22.8602102Z Resolving deltas:  45% (8684/19296)
2021-12-03T08:02:22.8607884Z Resolving deltas:  46% (8877/19296)
2021-12-03T08:02:22.8613398Z Resolving deltas:  47% (9071/19296)
2021-12-03T08:02:22.8618974Z Resolving deltas:  48% (9263/19296)
2021-12-03T08:02:22.8625443Z Resolving deltas:  49% (9456/19296)
2021-12-03T08:02:22.8631252Z Resolving deltas:  50% (9648/19296)
2021-12-03T08:02:22.8636986Z Resolving deltas:  51% (9841/19296)
2021-12-03T08:02:22.8643278Z Resolving deltas:  52% (10034/19296)
2021-12-03T08:02:22.8649102Z Resolving deltas:  53% (10228/19296)
2021-12-03T08:02:22.8654400Z Resolving deltas:  54% (10420/19296)
2021-12-03T08:02:22.8673179Z Resolving deltas:  55% (10613/19296)
2021-12-03T08:02:22.8691091Z Resolving deltas:  56% (10806/19296)
2021-12-03T08:02:22.8697451Z Resolving deltas:  57% (10999/19296)
2021-12-03T08:02:22.8708001Z Resolving deltas:  58% (11192/19296)
2021-12-03T08:02:22.8714336Z Resolving deltas:  59% (11385/19296)
2021-12-03T08:02:22.8721453Z Resolving deltas:  60% (11578/19296)
2021-12-03T08:02:22.8727329Z Resolving deltas:  61% (11771/19296)
2021-12-03T08:02:22.8734452Z Resolving deltas:  62% (11964/19296)
2021-12-03T08:02:22.8742079Z Resolving deltas:  63% (12158/19296)
2021-12-03T08:02:22.8754757Z Resolving deltas:  64% (12350/19296)
2021-12-03T08:02:22.8761106Z Resolving deltas:  65% (12543/19296)
2021-12-03T08:02:22.8772393Z Resolving deltas:  66% (12736/19296)
2021-12-03T08:02:22.8777824Z Resolving deltas:  67% (12929/19296)
2021-12-03T08:02:22.8784095Z Resolving deltas:  68% (13122/19296)
2021-12-03T08:02:22.8790203Z Resolving deltas:  69% (13315/19296)
2021-12-03T08:02:22.8796202Z Resolving deltas:  70% (13508/19296)
2021-12-03T08:02:22.8803528Z Resolving deltas:  71% (13701/19296)
2021-12-03T08:02:22.8810658Z Resolving deltas:  72% (13894/19296)
2021-12-03T08:02:22.8816714Z Resolving deltas:  73% (14087/19296)
2021-12-03T08:02:22.8821534Z Resolving deltas:  74% (14280/19296)
2021-12-03T08:02:22.8827717Z Resolving deltas:  75% (14472/19296)
2021-12-03T08:02:22.8833519Z Resolving deltas:  76% (14665/19296)
2021-12-03T08:02:22.8838687Z Resolving deltas:  77% (14858/19296)
2021-12-03T08:02:22.8846965Z Resolving deltas:  78% (15051/19296)
2021-12-03T08:02:22.8853290Z Resolving deltas:  79% (15244/19296)
2021-12-03T08:02:22.8858176Z Resolving deltas:  80% (15437/19296)
2021-12-03T08:02:22.8863504Z Resolving deltas:  81% (15630/19296)
2021-12-03T08:02:22.8873554Z Resolving deltas:  82% (15823/19296)
2021-12-03T08:02:22.8887276Z Resolving deltas:  83% (16016/19296)
2021-12-03T08:02:22.8897322Z Resolving deltas:  84% (16209/19296)
2021-12-03T08:02:22.8903051Z Resolving deltas:  85% (16402/19296)
2021-12-03T08:02:22.8909220Z Resolving deltas:  86% (16595/19296)
2021-12-03T08:02:22.8914609Z Resolving deltas:  87% (16788/19296)
2021-12-03T08:02:22.8920535Z Resolving deltas:  88% (16981/19296)
2021-12-03T08:02:22.8926067Z Resolving deltas:  89% (17174/19296)
2021-12-03T08:02:22.8942456Z Resolving deltas:  90% (17367/19296)
2021-12-03T08:02:22.8975218Z Resolving deltas:  91% (17561/19296)
2021-12-03T08:02:22.9046893Z Resolving deltas:  92% (17753/19296)
2021-12-03T08:02:22.9189437Z Resolving deltas:  93% (17946/19296)
2021-12-03T08:02:22.9277590Z Resolving deltas:  94% (18139/19296)
2021-12-03T08:02:22.9307549Z Resolving deltas:  95% (18332/19296)
2021-12-03T08:02:22.9341115Z Resolving deltas:  96% (18525/19296)
2021-12-03T08:02:22.9375797Z Resolving deltas:  97% (18718/19296)
2021-12-03T08:02:22.9418073Z Resolving deltas:  98% (18911/19296)
2021-12-03T08:02:22.9452902Z Resolving deltas:  99% (19104/19296)
2021-12-03T08:02:22.9507498Z Resolving deltas: 100% (19296/19296)
2021-12-03T08:02:22.9508272Z Resolving deltas: 100% (19296/19296), done.
2021-12-03T08:02:23.0495008Z From https://github.com/actions/virtual-environments
2021-12-03T08:02:23.0495972Z  * [new branch]        ale/removeStale         -> origin/ale/removeStale
2021-12-03T08:02:23.0497916Z  * [new branch]        main                    -> origin/main
2021-12-03T08:02:23.0498673Z  * [new branch]        malob/test-branch       -> origin/malob/test-branch
2021-12-03T08:02:23.0500387Z  * [new branch]        malob/ws2022-temp10     -> origin/malob/ws2022-temp10
2021-12-03T08:02:23.0501987Z  * [new branch]        malob/ws2022-test4      -> origin/malob/ws2022-test4
2021-12-03T08:02:23.0503611Z  * [new branch]        malob/ws2022-test8      -> origin/malob/ws2022-test8
2021-12-03T08:02:23.0505409Z  * [new branch]        maxim-lobanov-patch-1   -> origin/maxim-lobanov-patch-1
2021-12-03T08:02:23.0507730Z  * [new branch]        maxim-lobanov/set-ubuntu-permissions -> origin/maxim-lobanov/set-ubuntu-permissions
2021-12-03T08:02:23.0509713Z  * [new branch]        releases/Ubuntu18/20201102 -> origin/releases/Ubuntu18/20201102
2021-12-03T08:02:23.0511391Z  * [new branch]        releases/macOS-10.13/20201101 -> origin/releases/macOS-10.13/20201101
2021-12-03T08:02:23.0513529Z  * [new branch]        releases/macOS-10.13/20201101-docs -> origin/releases/macOS-10.13/20201101-docs
2021-12-03T08:02:23.0514477Z  * [new branch]        releases/macOS-10.13/20201107 -> origin/releases/macOS-10.13/20201107
2021-12-03T08:02:23.0516266Z  * [new branch]        releases/macOS-10.13/20201214 -> origin/releases/macOS-10.13/20201214
2021-12-03T08:02:23.0517919Z  * [new branch]        releases/macOS-10.13/20210115 -> origin/releases/macOS-10.13/20210115
2021-12-03T08:02:23.0519971Z  * [new branch]        releases/macOS-10.13/20210123 -> origin/releases/macOS-10.13/20210123
2021-12-03T08:02:23.0520836Z  * [new branch]        releases/macOS-10.13/20210207 -> origin/releases/macOS-10.13/20210207
2021-12-03T08:02:23.0522471Z  * [new branch]        releases/macOS-10.13/20210412 -> origin/releases/macOS-10.13/20210412
2021-12-03T08:02:23.0524173Z  * [new branch]        releases/macOS-10.13/20210412-docs -> origin/releases/macOS-10.13/20210412-docs
2021-12-03T08:02:23.0525884Z  * [new branch]        releases/macOS-10.13/20210413 -> origin/releases/macOS-10.13/20210413
2021-12-03T08:02:23.0527495Z  * [new branch]        releases/macOS-10.14/20201106 -> origin/releases/macOS-10.14/20201106
2021-12-03T08:02:23.0529121Z  * [new branch]        releases/macOS-10.14/20201214 -> origin/releases/macOS-10.14/20201214
2021-12-03T08:02:23.0531099Z  * [new branch]        releases/macOS-10.14/20210109 -> origin/releases/macOS-10.14/20210109
2021-12-03T08:02:23.0531973Z  * [new branch]        releases/macOS-10.14/20210130 -> origin/releases/macOS-10.14/20210130
2021-12-03T08:02:23.0533616Z  * [new branch]        releases/macOS-10.14/20210207 -> origin/releases/macOS-10.14/20210207
2021-12-03T08:02:23.0535215Z  * [new branch]        releases/macOS-10.14/20210308 -> origin/releases/macOS-10.14/20210308
2021-12-03T08:02:23.0537037Z  * [new branch]        releases/macOS-10.14/20210405 -> origin/releases/macOS-10.14/20210405
2021-12-03T08:02:23.0539144Z  * [new branch]        releases/macOS-10.14/20210413 -> origin/releases/macOS-10.14/20210413
2021-12-03T08:02:23.0540002Z  * [new branch]        releases/macOS-10.14/20210501 -> origin/releases/macOS-10.14/20210501
2021-12-03T08:02:23.0541599Z  * [new branch]        releases/macOS-10.14/20210531 -> origin/releases/macOS-10.14/20210531
2021-12-03T08:02:23.0543255Z  * [new branch]        releases/macOS-10.14/20210626 -> origin/releases/macOS-10.14/20210626
2021-12-03T08:02:23.0544874Z  * [new branch]        releases/macOS-10.14/20210724 -> origin/releases/macOS-10.14/20210724
2021-12-03T08:02:23.0546943Z  * [new branch]        releases/macOS-10.14/20210731 -> origin/releases/macOS-10.14/20210731
2021-12-03T08:02:23.0547841Z  * [new branch]        releases/macOS-10.14/20210814 -> origin/releases/macOS-10.14/20210814
2021-12-03T08:02:23.0549515Z  * [new branch]        releases/macOS-10.14/20210918 -> origin/releases/macOS-10.14/20210918
2021-12-03T08:02:23.0551142Z  * [new branch]        releases/macOS-10.14/20211016 -> origin/releases/macOS-10.14/20211016
2021-12-03T08:02:23.0552760Z  * [new branch]        releases/macOS-10.15/20201017 -> origin/releases/macOS-10.15/20201017
2021-12-03T08:02:23.0554406Z  * [new branch]        releases/macOS-10.15/20201026 -> origin/releases/macOS-10.15/20201026
2021-12-03T08:02:23.0556009Z  * [new branch]        releases/macOS-10.15/20201103 -> origin/releases/macOS-10.15/20201103
2021-12-03T08:02:23.0558080Z  * [new branch]        releases/macOS-10.15/20201103-docs -> origin/releases/macOS-10.15/20201103-docs
2021-12-03T08:02:23.0558995Z  * [new branch]        releases/macOS-10.15/20201107 -> origin/releases/macOS-10.15/20201107
2021-12-03T08:02:23.0560656Z  * [new branch]        releases/macOS-10.15/20201115 -> origin/releases/macOS-10.15/20201115
2021-12-03T08:02:23.0562282Z  * [new branch]        releases/macOS-10.15/20201130 -> origin/releases/macOS-10.15/20201130
2021-12-03T08:02:23.0564307Z  * [new branch]        releases/macOS-10.15/20201212 -> origin/releases/macOS-10.15/20201212
2021-12-03T08:02:23.0565179Z  * [new branch]        releases/macOS-10.15/20210110 -> origin/releases/macOS-10.15/20210110
2021-12-03T08:02:23.0566868Z  * [new branch]        releases/macOS-10.15/20210110-docs -> origin/releases/macOS-10.15/20210110-docs
2021-12-03T08:02:23.0568503Z  * [new branch]        releases/macOS-10.15/20210123 -> origin/releases/macOS-10.15/20210123
2021-12-03T08:02:23.0570493Z  * [new branch]        releases/macOS-10.15/20210130 -> origin/releases/macOS-10.15/20210130
2021-12-03T08:02:23.0571376Z  * [new branch]        releases/macOS-10.15/20210207 -> origin/releases/macOS-10.15/20210207
2021-12-03T08:02:23.0573017Z  * [new branch]        releases/macOS-10.15/20210213 -> origin/releases/macOS-10.15/20210213
2021-12-03T08:02:23.0574606Z  * [new branch]        releases/macOS-10.15/20210220 -> origin/releases/macOS-10.15/20210220
2021-12-03T08:02:23.0576309Z  * [new branch]        releases/macOS-10.15/20210302 -> origin/releases/macOS-10.15/20210302
2021-12-03T08:02:23.0577932Z  * [new branch]        releases/macOS-10.15/20210307 -> origin/releases/macOS-10.15/20210307
2021-12-03T08:02:23.0579907Z  * [new branch]        releases/macOS-10.15/20210314 -> origin/releases/macOS-10.15/20210314
2021-12-03T08:02:23.0580787Z  * [new branch]        releases/macOS-10.15/20210321 -> origin/releases/macOS-10.15/20210321
2021-12-03T08:02:23.0582474Z  * [new branch]        releases/macOS-10.15/20210321-docs -> origin/releases/macOS-10.15/20210321-docs
2021-12-03T08:02:23.0584510Z  * [new branch]        releases/macOS-10.15/20210327 -> origin/releases/macOS-10.15/20210327
2021-12-03T08:02:23.0585377Z  * [new branch]        releases/macOS-10.15/20210404 -> origin/releases/macOS-10.15/20210404
2021-12-03T08:02:23.0587780Z  * [new branch]        releases/macOS-10.15/20210409 -> origin/releases/macOS-10.15/20210409
2021-12-03T08:02:23.0588910Z  * [new branch]        releases/macOS-10.15/20210409-docs -> origin/releases/macOS-10.15/20210409-docs
2021-12-03T08:02:23.0590697Z  * [new branch]        releases/macOS-10.15/20210412 -> origin/releases/macOS-10.15/20210412
2021-12-03T08:02:23.0592709Z  * [new branch]        releases/macOS-10.15/20210419 -> origin/releases/macOS-10.15/20210419
2021-12-03T08:02:23.0593567Z  * [new branch]        releases/macOS-10.15/20210423 -> origin/releases/macOS-10.15/20210423
2021-12-03T08:02:23.0595196Z  * [new branch]        releases/macOS-10.15/20210503 -> origin/releases/macOS-10.15/20210503
2021-12-03T08:02:23.0596820Z  * [new branch]        releases/macOS-10.15/20210510 -> origin/releases/macOS-10.15/20210510
2021-12-03T08:02:23.0598624Z  * [new branch]        releases/macOS-10.15/20210516 -> origin/releases/macOS-10.15/20210516
2021-12-03T08:02:23.0600609Z  * [new branch]        releases/macOS-10.15/20210525 -> origin/releases/macOS-10.15/20210525
2021-12-03T08:02:23.0601479Z  * [new branch]        releases/macOS-10.15/20210531 -> origin/releases/macOS-10.15/20210531
2021-12-03T08:02:23.0603114Z  * [new branch]        releases/macOS-10.15/20210607 -> origin/releases/macOS-10.15/20210607
2021-12-03T08:02:23.0604695Z  * [new branch]        releases/macOS-10.15/20210612 -> origin/releases/macOS-10.15/20210612
2021-12-03T08:02:23.0606299Z  * [new branch]        releases/macOS-10.15/20210620 -> origin/releases/macOS-10.15/20210620
2021-12-03T08:02:23.0608338Z  * [new branch]        releases/macOS-10.15/20210626 -> origin/releases/macOS-10.15/20210626
2021-12-03T08:02:23.0609214Z  * [new branch]        releases/macOS-10.15/20210712 -> origin/releases/macOS-10.15/20210712
2021-12-03T08:02:23.0610827Z  * [new branch]        releases/macOS-10.15/20210718 -> origin/releases/macOS-10.15/20210718
2021-12-03T08:02:23.0612479Z  * [new branch]        releases/macOS-10.15/20210725 -> origin/releases/macOS-10.15/20210725
2021-12-03T08:02:23.0614071Z  * [new branch]        releases/macOS-10.15/20210801 -> origin/releases/macOS-10.15/20210801
2021-12-03T08:02:23.0615705Z  * [new branch]        releases/macOS-10.15/20210808 -> origin/releases/macOS-10.15/20210808
2021-12-03T08:02:23.0617729Z  * [new branch]        releases/macOS-10.15/20210814 -> origin/releases/macOS-10.15/20210814
2021-12-03T08:02:23.0618595Z  * [new branch]        releases/macOS-10.15/20210831 -> origin/releases/macOS-10.15/20210831
2021-12-03T08:02:23.0620198Z  * [new branch]        releases/macOS-10.15/20210905 -> origin/releases/macOS-10.15/20210905
2021-12-03T08:02:23.0621804Z  * [new branch]        releases/macOS-10.15/20210914 -> origin/releases/macOS-10.15/20210914
2021-12-03T08:02:23.0623408Z  * [new branch]        releases/macOS-10.15/20210919 -> origin/releases/macOS-10.15/20210919
2021-12-03T08:02:23.0625431Z  * [new branch]        releases/macOS-10.15/20210927 -> origin/releases/macOS-10.15/20210927
2021-12-03T08:02:23.0626304Z  * [new branch]        releases/macOS-10.15/20211002 -> origin/releases/macOS-10.15/20211002
2021-12-03T08:02:23.0628092Z  * [new branch]        releases/macOS-10.15/20211011 -> origin/releases/macOS-10.15/20211011
2021-12-03T08:02:23.0629712Z  * [new branch]        releases/macOS-10.15/20211016 -> origin/releases/macOS-10.15/20211016
2021-12-03T08:02:23.0631323Z  * [new branch]        releases/macOS-10.15/20211029 -> origin/releases/macOS-10.15/20211029
2021-12-03T08:02:23.0632919Z  * [new branch]        releases/macOS-10.15/20211106 -> origin/releases/macOS-10.15/20211106
2021-12-03T08:02:23.0634529Z  * [new branch]        releases/macOS-10.15/20211114 -> origin/releases/macOS-10.15/20211114
2021-12-03T08:02:23.0636153Z  * [new branch]        releases/macOS-10.15/20211120 -> origin/releases/macOS-10.15/20211120
2021-12-03T08:02:23.0637028Z  * [new branch]        releases/macOS-10.15/20211126 -> origin/releases/macOS-10.15/20211126
2021-12-03T08:02:23.0638916Z  * [new branch]        releases/macOS-11.0/20201024 -> origin/releases/macOS-11.0/20201024
2021-12-03T08:02:23.0640539Z  * [new branch]        releases/macOS-11.0/20201102 -> origin/releases/macOS-11.0/20201102
2021-12-03T08:02:23.0642314Z  * [new branch]        releases/macOS-11.0/20201107 -> origin/releases/macOS-11.0/20201107
2021-12-03T08:02:23.0643992Z  * [new branch]        releases/macOS-11.0/20201116 -> origin/releases/macOS-11.0/20201116
2021-12-03T08:02:23.0645982Z  * [new branch]        releases/macOS-11.0/20201130 -> origin/releases/macOS-11.0/20201130
2021-12-03T08:02:23.0646860Z  * [new branch]        releases/macOS-11.0/20201213 -> origin/releases/macOS-11.0/20201213
2021-12-03T08:02:23.0648490Z  * [new branch]        releases/macOS-11.0/20210110 -> origin/releases/macOS-11.0/20210110
2021-12-03T08:02:23.0650104Z  * [new branch]        releases/macOS-11.0/20210118 -> origin/releases/macOS-11.0/20210118
2021-12-03T08:02:23.0652316Z  * [new branch]        releases/macOS-11.0/20210123 -> origin/releases/macOS-11.0/20210123
2021-12-03T08:02:23.0653177Z  * [new branch]        releases/macOS-11.0/20210131 -> origin/releases/macOS-11.0/20210131
2021-12-03T08:02:23.0654804Z  * [new branch]        releases/macOS-11.0/20210208 -> origin/releases/macOS-11.0/20210208
2021-12-03T08:02:23.0656425Z  * [new branch]        releases/macOS-11.0/20210216 -> origin/releases/macOS-11.0/20210216
2021-12-03T08:02:23.0658048Z  * [new branch]        releases/macOS-11.0/20210219 -> origin/releases/macOS-11.0/20210219
2021-12-03T08:02:23.0660027Z  * [new branch]        releases/macOS-11.0/20210302 -> origin/releases/macOS-11.0/20210302
2021-12-03T08:02:23.0660862Z  * [new branch]        releases/macOS-11.0/20210308 -> origin/releases/macOS-11.0/20210308
2021-12-03T08:02:23.0662441Z  * [new branch]        releases/macOS-11.0/20210314 -> origin/releases/macOS-11.0/20210314
2021-12-03T08:02:23.0664056Z  * [new branch]        releases/macOS-11.0/20210321 -> origin/releases/macOS-11.0/20210321
2021-12-03T08:02:23.0665666Z  * [new branch]        releases/macOS-11.0/20210328 -> origin/releases/macOS-11.0/20210328
2021-12-03T08:02:23.0667601Z  * [new branch]        releases/macOS-11.0/20210404 -> origin/releases/macOS-11.0/20210404
2021-12-03T08:02:23.0669640Z  * [new branch]        releases/macOS-11.0/20210409 -> origin/releases/macOS-11.0/20210409
2021-12-03T08:02:23.0670530Z  * [new branch]        releases/macOS-11.0/20210409-docs -> origin/releases/macOS-11.0/20210409-docs
2021-12-03T08:02:23.0672168Z  * [new branch]        releases/macOS-11.0/20210412 -> origin/releases/macOS-11.0/20210412
2021-12-03T08:02:23.0673812Z  * [new branch]        releases/macOS-11.0/20210418 -> origin/releases/macOS-11.0/20210418
2021-12-03T08:02:23.0675455Z  * [new branch]        releases/macOS-11.0/20210420 -> origin/releases/macOS-11.0/20210420
2021-12-03T08:02:23.0677431Z  * [new branch]        releases/macOS-11.0/20210424 -> origin/releases/macOS-11.0/20210424
2021-12-03T08:02:23.0678289Z  * [new branch]        releases/macOS-11.0/20210503 -> origin/releases/macOS-11.0/20210503
2021-12-03T08:02:23.0679933Z  * [new branch]        releases/macOS-11.0/20210510 -> origin/releases/macOS-11.0/20210510
2021-12-03T08:02:23.0681510Z  * [new branch]        releases/macOS-11.0/20210516 -> origin/releases/macOS-11.0/20210516
2021-12-03T08:02:23.0683125Z  * [new branch]        releases/macOS-11/20210523 -> origin/releases/macOS-11/20210523
2021-12-03T08:02:23.0684729Z  * [new branch]        releases/macOS-11/20210530 -> origin/releases/macOS-11/20210530
2021-12-03T08:02:23.0686383Z  * [new branch]        releases/macOS-11/20210530-docs -> origin/releases/macOS-11/20210530-docs
2021-12-03T08:02:23.0688393Z  * [new branch]        releases/macOS-11/20210531 -> origin/releases/macOS-11/20210531
2021-12-03T08:02:23.0689245Z  * [new branch]        releases/macOS-11/20210608 -> origin/releases/macOS-11/20210608
2021-12-03T08:02:23.0690828Z  * [new branch]        releases/macOS-11/20210614 -> origin/releases/macOS-11/20210614
2021-12-03T08:02:23.0692459Z  * [new branch]        releases/macOS-11/20210620 -> origin/releases/macOS-11/20210620
2021-12-03T08:02:23.0694447Z  * [new branch]        releases/macOS-11/20210621 -> origin/releases/macOS-11/20210621
2021-12-03T08:02:23.0695475Z  * [new branch]        releases/macOS-11/20210621-docs -> origin/releases/macOS-11/20210621-docs
2021-12-03T08:02:23.0697179Z  * [new branch]        releases/macOS-11/20210626 -> origin/releases/macOS-11/20210626
2021-12-03T08:02:23.0698798Z  * [new branch]        releases/macOS-11/20210712 -> origin/releases/macOS-11/20210712
2021-12-03T08:02:23.0700850Z  * [new branch]        releases/macOS-11/20210718 -> origin/releases/macOS-11/20210718
2021-12-03T08:02:23.0701703Z  * [new branch]        releases/macOS-11/20210724 -> origin/releases/macOS-11/20210724
2021-12-03T08:02:23.0703313Z  * [new branch]        releases/macOS-11/20210801 -> origin/releases/macOS-11/20210801
2021-12-03T08:02:23.0705114Z  * [new branch]        releases/macOS-11/20210808 -> origin/releases/macOS-11/20210808
2021-12-03T08:02:23.0707777Z  * [new branch]        releases/macOS-11/20210814 -> origin/releases/macOS-11/20210814
2021-12-03T08:02:23.0708674Z  * [new branch]        releases/macOS-11/20210831 -> origin/releases/macOS-11/20210831
2021-12-03T08:02:23.0710832Z  * [new branch]        releases/macOS-11/20210905 -> origin/releases/macOS-11/20210905
2021-12-03T08:02:23.0711677Z  * [new branch]        releases/macOS-11/20210914 -> origin/releases/macOS-11/20210914
2021-12-03T08:02:23.0713290Z  * [new branch]        releases/macOS-11/20210917 -> origin/releases/macOS-11/20210917
2021-12-03T08:02:23.0714894Z  * [new branch]        releases/macOS-11/20210927 -> origin/releases/macOS-11/20210927
2021-12-03T08:02:23.0716862Z  * [new branch]        releases/macOS-11/20211001 -> origin/releases/macOS-11/20211001
2021-12-03T08:02:23.0717692Z  * [new branch]        releases/macOS-11/20211011 -> origin/releases/macOS-11/20211011
2021-12-03T08:02:23.0719288Z  * [new branch]        releases/macOS-11/20211018 -> origin/releases/macOS-11/20211018
2021-12-03T08:02:23.0720891Z  * [new branch]        releases/macOS-11/20211029 -> origin/releases/macOS-11/20211029
2021-12-03T08:02:23.0722491Z  * [new branch]        releases/macOS-11/20211106 -> origin/releases/macOS-11/20211106
2021-12-03T08:02:23.0724085Z  * [new branch]        releases/macOS-11/20211114 -> origin/releases/macOS-11/20211114
2021-12-03T08:02:23.0725660Z  * [new branch]        releases/macOS-11/20211120 -> origin/releases/macOS-11/20211120
2021-12-03T08:02:23.0727228Z  * [new branch]        releases/macOS-11/20211127 -> origin/releases/macOS-11/20211127
2021-12-03T08:02:23.0728845Z  * [new branch]        releases/macos-10.15/20200530 -> origin/releases/macos-10.15/20200530
2021-12-03T08:02:23.0730493Z  * [new branch]        releases/macos-10.15/20200604 -> origin/releases/macos-10.15/20200604
2021-12-03T08:02:23.0732135Z  * [new branch]        releases/macos-10.15/20200610 -> origin/releases/macos-10.15/20200610
2021-12-03T08:02:23.0734157Z  * [new branch]        releases/macos-10.15/20200618 -> origin/releases/macos-10.15/20200618
2021-12-03T08:02:23.0735031Z  * [new branch]        releases/macos-10.15/20200625 -> origin/releases/macos-10.15/20200625
2021-12-03T08:02:23.0736721Z  * [new branch]        releases/macos-10.15/20200701 -> origin/releases/macos-10.15/20200701
2021-12-03T08:02:23.0738368Z  * [new branch]        releases/macos-10.15/20200702 -> origin/releases/macos-10.15/20200702
2021-12-03T08:02:23.0740376Z  * [new branch]        releases/macos-10.15/20200707 -> origin/releases/macos-10.15/20200707
2021-12-03T08:02:23.0741247Z  * [new branch]        releases/macos-10.15/20200716 -> origin/releases/macos-10.15/20200716
2021-12-03T08:02:23.0742885Z  * [new branch]        releases/macos-10.15/20200728 -> origin/releases/macos-10.15/20200728
2021-12-03T08:02:23.0744501Z  * [new branch]        releases/macos-10.15/20200802 -> origin/releases/macos-10.15/20200802
2021-12-03T08:02:23.0746157Z  * [new branch]        releases/macos-10.15/20200806 -> origin/releases/macos-10.15/20200806
2021-12-03T08:02:23.0749854Z  * [new branch]        releases/macos-10.15/20200811 -> origin/releases/macos-10.15/20200811
2021-12-03T08:02:23.0754519Z  * [new branch]        releases/macos-10.15/20200819 -> origin/releases/macos-10.15/20200819
2021-12-03T08:02:23.0756635Z  * [new branch]        releases/macos-10.15/20200825 -> origin/releases/macos-10.15/20200825
2021-12-03T08:02:23.0757518Z  * [new branch]        releases/macos-10.15/20200829 -> origin/releases/macos-10.15/20200829
2021-12-03T08:02:23.0758364Z  * [new branch]        releases/macos-10.15/20200903 -> origin/releases/macos-10.15/20200903
2021-12-03T08:02:23.0759235Z  * [new branch]        releases/macos-10.15/20200913 -> origin/releases/macos-10.15/20200913
2021-12-03T08:02:23.0762791Z  * [new branch]        releases/macos-10.15/20200913-docs -> origin/releases/macos-10.15/20200913-docs
2021-12-03T08:02:23.0764432Z  * [new branch]        releases/macos-10.15/20200916 -> origin/releases/macos-10.15/20200916
2021-12-03T08:02:23.0766100Z  * [new branch]        releases/macos-10.15/20200918 -> origin/releases/macos-10.15/20200918
2021-12-03T08:02:23.0768157Z  * [new branch]        releases/macos-10.15/20201003 -> origin/releases/macos-10.15/20201003
2021-12-03T08:02:23.0769091Z  * [new branch]        releases/macos-10.15/20201011 -> origin/releases/macos-10.15/20201011
2021-12-03T08:02:23.0770625Z  * [new branch]        releases/ubuntu16/20200102 -> origin/releases/ubuntu16/20200102
2021-12-03T08:02:23.0772139Z  * [new branch]        releases/ubuntu16/20200113 -> origin/releases/ubuntu16/20200113
2021-12-03T08:02:23.0773003Z  * [new branch]        releases/ubuntu16/20200119 -> origin/releases/ubuntu16/20200119
2021-12-03T08:02:23.0774480Z  * [new branch]        releases/ubuntu16/20200130 -> origin/releases/ubuntu16/20200130
2021-12-03T08:02:23.0775985Z  * [new branch]        releases/ubuntu16/20200211 -> origin/releases/ubuntu16/20200211
2021-12-03T08:02:23.0776847Z  * [new branch]        releases/ubuntu16/20200217 -> origin/releases/ubuntu16/20200217
2021-12-03T08:02:23.0778327Z  * [new branch]        releases/ubuntu16/20200225 -> origin/releases/ubuntu16/20200225
2021-12-03T08:02:23.0779806Z  * [new branch]        releases/ubuntu16/20200301 -> origin/releases/ubuntu16/20200301
2021-12-03T08:02:23.0781243Z  * [new branch]        releases/ubuntu16/20200308 -> origin/releases/ubuntu16/20200308
2021-12-03T08:02:23.0782128Z  * [new branch]        releases/ubuntu16/20200315 -> origin/releases/ubuntu16/20200315
2021-12-03T08:02:23.0783611Z  * [new branch]        releases/ubuntu16/20200323 -> origin/releases/ubuntu16/20200323
2021-12-03T08:02:23.0785738Z  * [new branch]        releases/ubuntu16/20200330 -> origin/releases/ubuntu16/20200330
2021-12-03T08:02:23.0788001Z  * [new branch]        releases/ubuntu16/20200406 -> origin/releases/ubuntu16/20200406
2021-12-03T08:02:23.0790071Z  * [new branch]        releases/ubuntu16/20200415 -> origin/releases/ubuntu16/20200415
2021-12-03T08:02:23.0792225Z  * [new branch]        releases/ubuntu16/20200426 -> origin/releases/ubuntu16/20200426
2021-12-03T08:02:23.0794142Z  * [new branch]        releases/ubuntu16/20200428 -> origin/releases/ubuntu16/20200428
2021-12-03T08:02:23.0796129Z  * [new branch]        releases/ubuntu16/20200430 -> origin/releases/ubuntu16/20200430
2021-12-03T08:02:23.0798166Z  * [new branch]        releases/ubuntu16/20200512 -> origin/releases/ubuntu16/20200512
2021-12-03T08:02:23.0800236Z  * [new branch]        releases/ubuntu16/20200517 -> origin/releases/ubuntu16/20200517
2021-12-03T08:02:23.0802214Z  * [new branch]        releases/ubuntu16/20200525 -> origin/releases/ubuntu16/20200525
2021-12-03T08:02:23.0804309Z  * [new branch]        releases/ubuntu16/20200531 -> origin/releases/ubuntu16/20200531
2021-12-03T08:02:23.0806272Z  * [new branch]        releases/ubuntu16/20200604 -> origin/releases/ubuntu16/20200604
2021-12-03T08:02:23.0808700Z  * [new branch]        releases/ubuntu16/20200614 -> origin/releases/ubuntu16/20200614
2021-12-03T08:02:23.0810486Z  * [new branch]        releases/ubuntu16/20200621 -> origin/releases/ubuntu16/20200621
2021-12-03T08:02:23.0812548Z  * [new branch]        releases/ubuntu16/20200625 -> origin/releases/ubuntu16/20200625
2021-12-03T08:02:23.0814693Z  * [new branch]        releases/ubuntu16/20200705 -> origin/releases/ubuntu16/20200705
2021-12-03T08:02:23.0816610Z  * [new branch]        releases/ubuntu16/20200709 -> origin/releases/ubuntu16/20200709
2021-12-03T08:02:23.0818515Z  * [new branch]        releases/ubuntu16/20200717 -> origin/releases/ubuntu16/20200717
2021-12-03T08:02:23.0820857Z  * [new branch]        releases/ubuntu16/20200723 -> origin/releases/ubuntu16/20200723
2021-12-03T08:02:23.0822970Z  * [new branch]        releases/ubuntu16/20200802 -> origin/releases/ubuntu16/20200802
2021-12-03T08:02:23.0825068Z  * [new branch]        releases/ubuntu16/20200806 -> origin/releases/ubuntu16/20200806
2021-12-03T08:02:23.0827273Z  * [new branch]        releases/ubuntu16/20200817 -> origin/releases/ubuntu16/20200817
2021-12-03T08:02:23.0830569Z  * [new branch]        releases/ubuntu16/20200820 -> origin/releases/ubuntu16/20200820
2021-12-03T08:02:23.0832408Z  * [new branch]        releases/ubuntu16/20200823 -> origin/releases/ubuntu16/20200823
2021-12-03T08:02:23.0834454Z  * [new branch]        releases/ubuntu16/20200825 -> origin/releases/ubuntu16/20200825
2021-12-03T08:02:23.0836415Z  * [new branch]        releases/ubuntu16/20200901 -> origin/releases/ubuntu16/20200901
2021-12-03T08:02:23.0838480Z  * [new branch]        releases/ubuntu16/20200908 -> origin/releases/ubuntu16/20200908
2021-12-03T08:02:23.0840561Z  * [new branch]        releases/ubuntu16/20200914 -> origin/releases/ubuntu16/20200914
2021-12-03T08:02:23.0842853Z  * [new branch]        releases/ubuntu16/20200914-docs -> origin/releases/ubuntu16/20200914-docs
2021-12-03T08:02:23.0844740Z  * [new branch]        releases/ubuntu16/20200917 -> origin/releases/ubuntu16/20200917
2021-12-03T08:02:23.0846763Z  * [new branch]        releases/ubuntu16/20200917-docs -> origin/releases/ubuntu16/20200917-docs
2021-12-03T08:02:23.0848789Z  * [new branch]        releases/ubuntu16/20200920 -> origin/releases/ubuntu16/20200920
2021-12-03T08:02:23.0850942Z  * [new branch]        releases/ubuntu16/20201004 -> origin/releases/ubuntu16/20201004
2021-12-03T08:02:23.0852980Z  * [new branch]        releases/ubuntu16/20201011 -> origin/releases/ubuntu16/20201011
2021-12-03T08:02:23.0855022Z  * [new branch]        releases/ubuntu16/20201011-docs -> origin/releases/ubuntu16/20201011-docs
2021-12-03T08:02:23.0857001Z  * [new branch]        releases/ubuntu16/20201012 -> origin/releases/ubuntu16/20201012
2021-12-03T08:02:23.0859081Z  * [new branch]        releases/ubuntu16/20201015 -> origin/releases/ubuntu16/20201015
2021-12-03T08:02:23.0861131Z  * [new branch]        releases/ubuntu16/20201026 -> origin/releases/ubuntu16/20201026
2021-12-03T08:02:23.0863234Z  * [new branch]        releases/ubuntu16/20201101 -> origin/releases/ubuntu16/20201101
2021-12-03T08:02:23.0865501Z  * [new branch]        releases/ubuntu16/20201101-docs -> origin/releases/ubuntu16/20201101-docs
2021-12-03T08:02:23.0867614Z  * [new branch]        releases/ubuntu16/20201102 -> origin/releases/ubuntu16/20201102
2021-12-03T08:02:23.0869665Z  * [new branch]        releases/ubuntu16/20201108 -> origin/releases/ubuntu16/20201108
2021-12-03T08:02:23.0871780Z  * [new branch]        releases/ubuntu16/20201116 -> origin/releases/ubuntu16/20201116
2021-12-03T08:02:23.0873685Z  * [new branch]        releases/ubuntu16/20201129 -> origin/releases/ubuntu16/20201129
2021-12-03T08:02:23.0876157Z  * [new branch]        releases/ubuntu16/20201210 -> origin/releases/ubuntu16/20201210
2021-12-03T08:02:23.0877846Z  * [new branch]        releases/ubuntu16/20210111 -> origin/releases/ubuntu16/20210111
2021-12-03T08:02:23.0879899Z  * [new branch]        releases/ubuntu16/20210117 -> origin/releases/ubuntu16/20210117
2021-12-03T08:02:23.0881862Z  * [new branch]        releases/ubuntu16/20210117-docs -> origin/releases/ubuntu16/20210117-docs
2021-12-03T08:02:23.0883866Z  * [new branch]        releases/ubuntu16/20210123 -> origin/releases/ubuntu16/20210123
2021-12-03T08:02:23.0885816Z  * [new branch]        releases/ubuntu16/20210131 -> origin/releases/ubuntu16/20210131
2021-12-03T08:02:23.0888217Z  * [new branch]        releases/ubuntu16/20210208 -> origin/releases/ubuntu16/20210208
2021-12-03T08:02:23.0890031Z  * [new branch]        releases/ubuntu16/20210214 -> origin/releases/ubuntu16/20210214
2021-12-03T08:02:23.0892120Z  * [new branch]        releases/ubuntu16/20210214-docs -> origin/releases/ubuntu16/20210214-docs
2021-12-03T08:02:23.0894141Z  * [new branch]        releases/ubuntu16/20210216 -> origin/releases/ubuntu16/20210216
2021-12-03T08:02:23.0896359Z  * [new branch]        releases/ubuntu16/20210219 -> origin/releases/ubuntu16/20210219
2021-12-03T08:02:23.0898289Z  * [new branch]        releases/ubuntu16/20210302 -> origin/releases/ubuntu16/20210302
2021-12-03T08:02:23.0900353Z  * [new branch]        releases/ubuntu16/20210309 -> origin/releases/ubuntu16/20210309
2021-12-03T08:02:23.0902423Z  * [new branch]        releases/ubuntu16/20210317 -> origin/releases/ubuntu16/20210317
2021-12-03T08:02:23.0904448Z  * [new branch]        releases/ubuntu16/20210318 -> origin/releases/ubuntu16/20210318
2021-12-03T08:02:23.0906409Z  * [new branch]        releases/ubuntu16/20210327 -> origin/releases/ubuntu16/20210327
2021-12-03T08:02:23.0909647Z  * [new branch]        releases/ubuntu16/20210405 -> origin/releases/ubuntu16/20210405
2021-12-03T08:02:23.0911493Z  * [new branch]        releases/ubuntu16/20210412 -> origin/releases/ubuntu16/20210412
2021-12-03T08:02:23.0913704Z  * [new branch]        releases/ubuntu16/20210419 -> origin/releases/ubuntu16/20210419
2021-12-03T08:02:23.0915683Z  * [new branch]        releases/ubuntu16/20210425 -> origin/releases/ubuntu16/20210425
2021-12-03T08:02:23.0917779Z  * [new branch]        releases/ubuntu16/20210504 -> origin/releases/ubuntu16/20210504
2021-12-03T08:02:23.0919903Z  * [new branch]        releases/ubuntu16/20210510 -> origin/releases/ubuntu16/20210510
2021-12-03T08:02:23.0922243Z  * [new branch]        releases/ubuntu16/20210517 -> origin/releases/ubuntu16/20210517
2021-12-03T08:02:23.0924131Z  * [new branch]        releases/ubuntu16/20210524 -> origin/releases/ubuntu16/20210524
2021-12-03T08:02:23.0926179Z  * [new branch]        releases/ubuntu16/20210531 -> origin/releases/ubuntu16/20210531
2021-12-03T08:02:23.0928908Z  * [new branch]        releases/ubuntu18/20200102 -> origin/releases/ubuntu18/20200102
2021-12-03T08:02:23.0930756Z  * [new branch]        releases/ubuntu18/20200113 -> origin/releases/ubuntu18/20200113
2021-12-03T08:02:23.0932785Z  * [new branch]        releases/ubuntu18/20200119 -> origin/releases/ubuntu18/20200119
2021-12-03T08:02:23.0934734Z  * [new branch]        releases/ubuntu18/20200130 -> origin/releases/ubuntu18/20200130
2021-12-03T08:02:23.0936716Z  * [new branch]        releases/ubuntu18/20200211 -> origin/releases/ubuntu18/20200211
2021-12-03T08:02:23.0938760Z  * [new branch]        releases/ubuntu18/20200217 -> origin/releases/ubuntu18/20200217
2021-12-03T08:02:23.0940692Z  * [new branch]        releases/ubuntu18/20200301 -> origin/releases/ubuntu18/20200301
2021-12-03T08:02:23.0942854Z  * [new branch]        releases/ubuntu18/20200308 -> origin/releases/ubuntu18/20200308
2021-12-03T08:02:23.0944757Z  * [new branch]        releases/ubuntu18/20200316 -> origin/releases/ubuntu18/20200316
2021-12-03T08:02:23.0946781Z  * [new branch]        releases/ubuntu18/20200323 -> origin/releases/ubuntu18/20200323
2021-12-03T08:02:23.0949150Z  * [new branch]        releases/ubuntu18/20200330 -> origin/releases/ubuntu18/20200330
2021-12-03T08:02:23.0951089Z  * [new branch]        releases/ubuntu18/20200406 -> origin/releases/ubuntu18/20200406
2021-12-03T08:02:23.0952967Z  * [new branch]        releases/ubuntu18/20200415 -> origin/releases/ubuntu18/20200415
2021-12-03T08:02:23.0954979Z  * [new branch]        releases/ubuntu18/20200426 -> origin/releases/ubuntu18/20200426
2021-12-03T08:02:23.0956891Z  * [new branch]        releases/ubuntu18/20200428 -> origin/releases/ubuntu18/20200428
2021-12-03T08:02:23.0958981Z  * [new branch]        releases/ubuntu18/20200430 -> origin/releases/ubuntu18/20200430
2021-12-03T08:02:23.0961140Z  * [new branch]        releases/ubuntu18/20200512 -> origin/releases/ubuntu18/20200512
2021-12-03T08:02:23.0963074Z  * [new branch]        releases/ubuntu18/20200518 -> origin/releases/ubuntu18/20200518
2021-12-03T08:02:23.0964965Z  * [new branch]        releases/ubuntu18/20200525 -> origin/releases/ubuntu18/20200525
2021-12-03T08:02:23.0967023Z  * [new branch]        releases/ubuntu18/20200531 -> origin/releases/ubuntu18/20200531
2021-12-03T08:02:23.0968995Z  * [new branch]        releases/ubuntu18/20200604 -> origin/releases/ubuntu18/20200604
2021-12-03T08:02:23.0970928Z  * [new branch]        releases/ubuntu18/20200614 -> origin/releases/ubuntu18/20200614
2021-12-03T08:02:23.0972894Z  * [new branch]        releases/ubuntu18/20200621 -> origin/releases/ubuntu18/20200621
2021-12-03T08:02:23.0975018Z  * [new branch]        releases/ubuntu18/20200625 -> origin/releases/ubuntu18/20200625
2021-12-03T08:02:23.0976888Z  * [new branch]        releases/ubuntu18/20200705 -> origin/releases/ubuntu18/20200705
2021-12-03T08:02:23.0978886Z  * [new branch]        releases/ubuntu18/20200709 -> origin/releases/ubuntu18/20200709
2021-12-03T08:02:23.0980843Z  * [new branch]        releases/ubuntu18/20200717 -> origin/releases/ubuntu18/20200717
2021-12-03T08:02:23.0982882Z  * [new branch]        releases/ubuntu18/20200726 -> origin/releases/ubuntu18/20200726
2021-12-03T08:02:23.0984779Z  * [new branch]        releases/ubuntu18/20200802 -> origin/releases/ubuntu18/20200802
2021-12-03T08:02:23.0987014Z  * [new branch]        releases/ubuntu18/20200806 -> origin/releases/ubuntu18/20200806
2021-12-03T08:02:23.0989887Z  * [new branch]        releases/ubuntu18/20200817 -> origin/releases/ubuntu18/20200817
2021-12-03T08:02:23.0991790Z  * [new branch]        releases/ubuntu18/20200820 -> origin/releases/ubuntu18/20200820
2021-12-03T08:02:23.0993698Z  * [new branch]        releases/ubuntu18/20200823 -> origin/releases/ubuntu18/20200823
2021-12-03T08:02:23.0995704Z  * [new branch]        releases/ubuntu18/20200825 -> origin/releases/ubuntu18/20200825
2021-12-03T08:02:23.0997697Z  * [new branch]        releases/ubuntu18/20200901 -> origin/releases/ubuntu18/20200901
2021-12-03T08:02:23.0999679Z  * [new branch]        releases/ubuntu18/20200908 -> origin/releases/ubuntu18/20200908
2021-12-03T08:02:23.1001625Z  * [new branch]        releases/ubuntu18/20200914 -> origin/releases/ubuntu18/20200914
2021-12-03T08:02:23.1003713Z  * [new branch]        releases/ubuntu18/20200914-docs -> origin/releases/ubuntu18/20200914-docs
2021-12-03T08:02:23.1005673Z  * [new branch]        releases/ubuntu18/20200917 -> origin/releases/ubuntu18/20200917
2021-12-03T08:02:23.1007741Z  * [new branch]        releases/ubuntu18/20200920 -> origin/releases/ubuntu18/20200920
2021-12-03T08:02:23.1009633Z  * [new branch]        releases/ubuntu18/20201004 -> origin/releases/ubuntu18/20201004
2021-12-03T08:02:23.1011599Z  * [new branch]        releases/ubuntu18/20201007 -> origin/releases/ubuntu18/20201007
2021-12-03T08:02:23.1013601Z  * [new branch]        releases/ubuntu18/20201007-docs -> origin/releases/ubuntu18/20201007-docs
2021-12-03T08:02:23.1015537Z  * [new branch]        releases/ubuntu18/20201011 -> origin/releases/ubuntu18/20201011
2021-12-03T08:02:23.1017465Z  * [new branch]        releases/ubuntu18/20201011-docs -> origin/releases/ubuntu18/20201011-docs
2021-12-03T08:02:23.1019497Z  * [new branch]        releases/ubuntu18/20201012 -> origin/releases/ubuntu18/20201012
2021-12-03T08:02:23.1021510Z  * [new branch]        releases/ubuntu18/20201015 -> origin/releases/ubuntu18/20201015
2021-12-03T08:02:23.1023512Z  * [new branch]        releases/ubuntu18/20201026 -> origin/releases/ubuntu18/20201026
2021-12-03T08:02:23.1025559Z  * [new branch]        releases/ubuntu18/20201101 -> origin/releases/ubuntu18/20201101
2021-12-03T08:02:23.1027891Z  * [new branch]        releases/ubuntu18/20201101-docs -> origin/releases/ubuntu18/20201101-docs
2021-12-03T08:02:23.1030078Z  * [new branch]        releases/ubuntu18/20201108 -> origin/releases/ubuntu18/20201108
2021-12-03T08:02:23.1032272Z  * [new branch]        releases/ubuntu18/20201115 -> origin/releases/ubuntu18/20201115
2021-12-03T08:02:23.1034211Z  * [new branch]        releases/ubuntu18/20201129 -> origin/releases/ubuntu18/20201129
2021-12-03T08:02:23.1036213Z  * [new branch]        releases/ubuntu18/20201210 -> origin/releases/ubuntu18/20201210
2021-12-03T08:02:23.1038128Z  * [new branch]        releases/ubuntu18/20210111 -> origin/releases/ubuntu18/20210111
2021-12-03T08:02:23.1040466Z  * [new branch]        releases/ubuntu18/20210117 -> origin/releases/ubuntu18/20210117
2021-12-03T08:02:23.1042249Z  * [new branch]        releases/ubuntu18/20210117-docs -> origin/releases/ubuntu18/20210117-docs
2021-12-03T08:02:23.1044265Z  * [new branch]        releases/ubuntu18/20210123 -> origin/releases/ubuntu18/20210123
2021-12-03T08:02:23.1046355Z  * [new branch]        releases/ubuntu18/20210131 -> origin/releases/ubuntu18/20210131
2021-12-03T08:02:23.1048347Z  * [new branch]        releases/ubuntu18/20210208 -> origin/releases/ubuntu18/20210208
2021-12-03T08:02:23.1050376Z  * [new branch]        releases/ubuntu18/20210211 -> origin/releases/ubuntu18/20210211
2021-12-03T08:02:23.1052401Z  * [new branch]        releases/ubuntu18/20210219 -> origin/releases/ubuntu18/20210219
2021-12-03T08:02:23.1054307Z  * [new branch]        releases/ubuntu18/20210302 -> origin/releases/ubuntu18/20210302
2021-12-03T08:02:23.1056306Z  * [new branch]        releases/ubuntu18/20210309 -> origin/releases/ubuntu18/20210309
2021-12-03T08:02:23.1058481Z  * [new branch]        releases/ubuntu18/20210315 -> origin/releases/ubuntu18/20210315
2021-12-03T08:02:23.1060580Z  * [new branch]        releases/ubuntu18/20210318 -> origin/releases/ubuntu18/20210318
2021-12-03T08:02:23.1062525Z  * [new branch]        releases/ubuntu18/20210330 -> origin/releases/ubuntu18/20210330
2021-12-03T08:02:23.1064549Z  * [new branch]        releases/ubuntu18/20210405 -> origin/releases/ubuntu18/20210405
2021-12-03T08:02:23.1066583Z  * [new branch]        releases/ubuntu18/20210412 -> origin/releases/ubuntu18/20210412
2021-12-03T08:02:23.1069604Z  * [new branch]        releases/ubuntu18/20210419 -> origin/releases/ubuntu18/20210419
2021-12-03T08:02:23.1071425Z  * [new branch]        releases/ubuntu18/20210425 -> origin/releases/ubuntu18/20210425
2021-12-03T08:02:23.1073520Z  * [new branch]        releases/ubuntu18/20210504 -> origin/releases/ubuntu18/20210504
2021-12-03T08:02:23.1075444Z  * [new branch]        releases/ubuntu18/20210510 -> origin/releases/ubuntu18/20210510
2021-12-03T08:02:23.1077472Z  * [new branch]        releases/ubuntu18/20210517 -> origin/releases/ubuntu18/20210517
2021-12-03T08:02:23.1079477Z  * [new branch]        releases/ubuntu18/20210524 -> origin/releases/ubuntu18/20210524
2021-12-03T08:02:23.1081436Z  * [new branch]        releases/ubuntu18/20210531 -> origin/releases/ubuntu18/20210531
2021-12-03T08:02:23.1083596Z  * [new branch]        releases/ubuntu18/20210606 -> origin/releases/ubuntu18/20210606
2021-12-03T08:02:23.1085690Z  * [new branch]        releases/ubuntu18/20210614 -> origin/releases/ubuntu18/20210614
2021-12-03T08:02:23.1087647Z  * [new branch]        releases/ubuntu18/20210621 -> origin/releases/ubuntu18/20210621
2021-12-03T08:02:23.1089789Z  * [new branch]        releases/ubuntu18/20210628 -> origin/releases/ubuntu18/20210628
2021-12-03T08:02:23.1091816Z  * [new branch]        releases/ubuntu18/20210712 -> origin/releases/ubuntu18/20210712
2021-12-03T08:02:23.1094133Z  * [new branch]        releases/ubuntu18/20210718 -> origin/releases/ubuntu18/20210718
2021-12-03T08:02:23.1095953Z  * [new branch]        releases/ubuntu18/20210726 -> origin/releases/ubuntu18/20210726
2021-12-03T08:02:23.1098029Z  * [new branch]        releases/ubuntu18/20210803 -> origin/releases/ubuntu18/20210803
2021-12-03T08:02:23.1100041Z  * [new branch]        releases/ubuntu18/20210810 -> origin/releases/ubuntu18/20210810
2021-12-03T08:02:23.1102413Z  * [new branch]        releases/ubuntu18/20210816 -> origin/releases/ubuntu18/20210816
2021-12-03T08:02:23.1104405Z  * [new branch]        releases/ubuntu18/20210831 -> origin/releases/ubuntu18/20210831
2021-12-03T08:02:23.1106463Z  * [new branch]        releases/ubuntu18/20210906 -> origin/releases/ubuntu18/20210906
2021-12-03T08:02:23.1108626Z  * [new branch]        releases/ubuntu18/20210913 -> origin/releases/ubuntu18/20210913
2021-12-03T08:02:23.1110672Z  * [new branch]        releases/ubuntu18/20210919 -> origin/releases/ubuntu18/20210919
2021-12-03T08:02:23.1112668Z  * [new branch]        releases/ubuntu18/20210929 -> origin/releases/ubuntu18/20210929
2021-12-03T08:02:23.1114797Z  * [new branch]        releases/ubuntu18/20211004 -> origin/releases/ubuntu18/20211004
2021-12-03T08:02:23.1116859Z  * [new branch]        releases/ubuntu18/20211011 -> origin/releases/ubuntu18/20211011
2021-12-03T08:02:23.1119040Z  * [new branch]        releases/ubuntu18/20211017 -> origin/releases/ubuntu18/20211017
2021-12-03T08:02:23.1121041Z  * [new branch]        releases/ubuntu18/20211101 -> origin/releases/ubuntu18/20211101
2021-12-03T08:02:23.1123229Z  * [new branch]        releases/ubuntu18/20211108 -> origin/releases/ubuntu18/20211108
2021-12-03T08:02:23.1125216Z  * [new branch]        releases/ubuntu18/20211114 -> origin/releases/ubuntu18/20211114
2021-12-03T08:02:23.1127521Z  * [new branch]        releases/ubuntu18/20211122 -> origin/releases/ubuntu18/20211122
2021-12-03T08:02:23.1129947Z  * [new branch]        releases/ubuntu18/20211129 -> origin/releases/ubuntu18/20211129
2021-12-03T08:02:23.1132689Z  * [new branch]        releases/ubuntu20/20200531 -> origin/releases/ubuntu20/20200531
2021-12-03T08:02:23.1134714Z  * [new branch]        releases/ubuntu20/20200604 -> origin/releases/ubuntu20/20200604
2021-12-03T08:02:23.1136764Z  * [new branch]        releases/ubuntu20/20200607 -> origin/releases/ubuntu20/20200607
2021-12-03T08:02:23.1138665Z  * [new branch]        releases/ubuntu20/20200614 -> origin/releases/ubuntu20/20200614
2021-12-03T08:02:23.1140710Z  * [new branch]        releases/ubuntu20/20200621 -> origin/releases/ubuntu20/20200621
2021-12-03T08:02:23.1142661Z  * [new branch]        releases/ubuntu20/20200625 -> origin/releases/ubuntu20/20200625
2021-12-03T08:02:23.1144656Z  * [new branch]        releases/ubuntu20/20200705 -> origin/releases/ubuntu20/20200705
2021-12-03T08:02:23.1146680Z  * [new branch]        releases/ubuntu20/20200709 -> origin/releases/ubuntu20/20200709
2021-12-03T08:02:23.1148925Z  * [new branch]        releases/ubuntu20/20200717 -> origin/releases/ubuntu20/20200717
2021-12-03T08:02:23.1150893Z  * [new branch]        releases/ubuntu20/20200723 -> origin/releases/ubuntu20/20200723
2021-12-03T08:02:23.1152886Z  * [new branch]        releases/ubuntu20/20200802 -> origin/releases/ubuntu20/20200802
2021-12-03T08:02:23.1154889Z  * [new branch]        releases/ubuntu20/20200806 -> origin/releases/ubuntu20/20200806
2021-12-03T08:02:23.1156866Z  * [new branch]        releases/ubuntu20/20200817 -> origin/releases/ubuntu20/20200817
2021-12-03T08:02:23.1158820Z  * [new branch]        releases/ubuntu20/20200820 -> origin/releases/ubuntu20/20200820
2021-12-03T08:02:23.1160777Z  * [new branch]        releases/ubuntu20/20200825 -> origin/releases/ubuntu20/20200825
2021-12-03T08:02:23.1162777Z  * [new branch]        releases/ubuntu20/20200901 -> origin/releases/ubuntu20/20200901
2021-12-03T08:02:23.1164797Z  * [new branch]        releases/ubuntu20/20200908 -> origin/releases/ubuntu20/20200908
2021-12-03T08:02:23.1166750Z  * [new branch]        releases/ubuntu20/20200914 -> origin/releases/ubuntu20/20200914
2021-12-03T08:02:23.1168742Z  * [new branch]        releases/ubuntu20/20200914-docs -> origin/releases/ubuntu20/20200914-docs
2021-12-03T08:02:23.1170591Z  * [new branch]        releases/ubuntu20/20200920 -> origin/releases/ubuntu20/20200920
2021-12-03T08:02:23.1172573Z  * [new branch]        releases/ubuntu20/20201004 -> origin/releases/ubuntu20/20201004
2021-12-03T08:02:23.1174546Z  * [new branch]        releases/ubuntu20/20201011 -> origin/releases/ubuntu20/20201011
2021-12-03T08:02:23.1176604Z  * [new branch]        releases/ubuntu20/20201011-docs -> origin/releases/ubuntu20/20201011-docs
2021-12-03T08:02:23.1178378Z  * [new branch]        releases/ubuntu20/20201012 -> origin/releases/ubuntu20/20201012
2021-12-03T08:02:23.1180385Z  * [new branch]        releases/ubuntu20/20201015 -> origin/releases/ubuntu20/20201015
2021-12-03T08:02:23.1182330Z  * [new branch]        releases/ubuntu20/20201026 -> origin/releases/ubuntu20/20201026
2021-12-03T08:02:23.1184377Z  * [new branch]        releases/ubuntu20/20201101 -> origin/releases/ubuntu20/20201101
2021-12-03T08:02:23.1187003Z  * [new branch]        releases/ubuntu20/20201101-docs -> origin/releases/ubuntu20/20201101-docs
2021-12-03T08:02:23.1189349Z  * [new branch]        releases/ubuntu20/20201108 -> origin/releases/ubuntu20/20201108
2021-12-03T08:02:23.1191372Z  * [new branch]        releases/ubuntu20/20201116 -> origin/releases/ubuntu20/20201116
2021-12-03T08:02:23.1193380Z  * [new branch]        releases/ubuntu20/20201130 -> origin/releases/ubuntu20/20201130
2021-12-03T08:02:23.1195412Z  * [new branch]        releases/ubuntu20/20201210 -> origin/releases/ubuntu20/20201210
2021-12-03T08:02:23.1197396Z  * [new branch]        releases/ubuntu20/20210111 -> origin/releases/ubuntu20/20210111
2021-12-03T08:02:23.1199410Z  * [new branch]        releases/ubuntu20/20210117 -> origin/releases/ubuntu20/20210117
2021-12-03T08:02:23.1201392Z  * [new branch]        releases/ubuntu20/20210117-docs -> origin/releases/ubuntu20/20210117-docs
2021-12-03T08:02:23.1203249Z  * [new branch]        releases/ubuntu20/20210123 -> origin/releases/ubuntu20/20210123
2021-12-03T08:02:23.1205226Z  * [new branch]        releases/ubuntu20/20210131 -> origin/releases/ubuntu20/20210131
2021-12-03T08:02:23.1207173Z  * [new branch]        releases/ubuntu20/20210208 -> origin/releases/ubuntu20/20210208
2021-12-03T08:02:23.1209191Z  * [new branch]        releases/ubuntu20/20210215 -> origin/releases/ubuntu20/20210215
2021-12-03T08:02:23.1211405Z  * [new branch]        releases/ubuntu20/20210215-docs -> origin/releases/ubuntu20/20210215-docs
2021-12-03T08:02:23.1213461Z  * [new branch]        releases/ubuntu20/20210216 -> origin/releases/ubuntu20/20210216
2021-12-03T08:02:23.1215371Z  * [new branch]        releases/ubuntu20/20210219 -> origin/releases/ubuntu20/20210219
2021-12-03T08:02:23.1220842Z  * [new branch]        releases/ubuntu20/20210302 -> origin/releases/ubuntu20/20210302
2021-12-03T08:02:23.1224468Z  * [new branch]        releases/ubuntu20/20210309 -> origin/releases/ubuntu20/20210309
2021-12-03T08:02:23.1225470Z  * [new branch]        releases/ubuntu20/20210315 -> origin/releases/ubuntu20/20210315
2021-12-03T08:02:23.1228067Z  * [new branch]        releases/ubuntu20/20210318 -> origin/releases/ubuntu20/20210318
2021-12-03T08:02:23.1230875Z  * [new branch]        releases/ubuntu20/20210327 -> origin/releases/ubuntu20/20210327
2021-12-03T08:02:23.1232608Z  * [new branch]        releases/ubuntu20/20210327-docs -> origin/releases/ubuntu20/20210327-docs
2021-12-03T08:02:23.1234259Z  * [new branch]        releases/ubuntu20/20210330 -> origin/releases/ubuntu20/20210330
2021-12-03T08:02:23.1235832Z  * [new branch]        releases/ubuntu20/20210405 -> origin/releases/ubuntu20/20210405
2021-12-03T08:02:23.1237949Z  * [new branch]        releases/ubuntu20/20210412 -> origin/releases/ubuntu20/20210412
2021-12-03T08:02:23.1239601Z  * [new branch]        releases/ubuntu20/20210419 -> origin/releases/ubuntu20/20210419
2021-12-03T08:02:23.1241700Z  * [new branch]        releases/ubuntu20/20210425 -> origin/releases/ubuntu20/20210425
2021-12-03T08:02:23.1243328Z  * [new branch]        releases/ubuntu20/20210504 -> origin/releases/ubuntu20/20210504
2021-12-03T08:02:23.1245334Z  * [new branch]        releases/ubuntu20/20210510 -> origin/releases/ubuntu20/20210510
2021-12-03T08:02:23.1246921Z  * [new branch]        releases/ubuntu20/20210517 -> origin/releases/ubuntu20/20210517
2021-12-03T08:02:23.1248525Z  * [new branch]        releases/ubuntu20/20210524 -> origin/releases/ubuntu20/20210524
2021-12-03T08:02:23.1250603Z  * [new branch]        releases/ubuntu20/20210531 -> origin/releases/ubuntu20/20210531
2021-12-03T08:02:23.1252212Z  * [new branch]        releases/ubuntu20/20210606 -> origin/releases/ubuntu20/20210606
2021-12-03T08:02:23.1253896Z  * [new branch]        releases/ubuntu20/20210614 -> origin/releases/ubuntu20/20210614
2021-12-03T08:02:23.1255512Z  * [new branch]        releases/ubuntu20/20210621 -> origin/releases/ubuntu20/20210621
2021-12-03T08:02:23.1257620Z  * [new branch]        releases/ubuntu20/20210628 -> origin/releases/ubuntu20/20210628
2021-12-03T08:02:23.1259233Z  * [new branch]        releases/ubuntu20/20210712 -> origin/releases/ubuntu20/20210712
2021-12-03T08:02:23.1261162Z  * [new branch]        releases/ubuntu20/20210718 -> origin/releases/ubuntu20/20210718
2021-12-03T08:02:23.1262909Z  * [new branch]        releases/ubuntu20/20210726 -> origin/releases/ubuntu20/20210726
2021-12-03T08:02:23.1264519Z  * [new branch]        releases/ubuntu20/20210803 -> origin/releases/ubuntu20/20210803
2021-12-03T08:02:23.1266472Z  * [new branch]        releases/ubuntu20/20210810 -> origin/releases/ubuntu20/20210810
2021-12-03T08:02:23.1268262Z  * [new branch]        releases/ubuntu20/20210816 -> origin/releases/ubuntu20/20210816
2021-12-03T08:02:23.1269916Z  * [new branch]        releases/ubuntu20/20210831 -> origin/releases/ubuntu20/20210831
2021-12-03T08:02:23.1271532Z  * [new branch]        releases/ubuntu20/20210906 -> origin/releases/ubuntu20/20210906
2021-12-03T08:02:23.1272546Z  * [new branch]        releases/ubuntu20/20210913 -> origin/releases/ubuntu20/20210913
2021-12-03T08:02:23.1275136Z  * [new branch]        releases/ubuntu20/20210919 -> origin/releases/ubuntu20/20210919
2021-12-03T08:02:23.1276751Z  * [new branch]        releases/ubuntu20/20210929 -> origin/releases/ubuntu20/20210929
2021-12-03T08:02:23.1279716Z  * [new branch]        releases/ubuntu20/20211004 -> origin/releases/ubuntu20/20211004
2021-12-03T08:02:23.1281292Z  * [new branch]        releases/ubuntu20/20211011 -> origin/releases/ubuntu20/20211011
2021-12-03T08:02:23.1282206Z  * [new branch]        releases/ubuntu20/20211017 -> origin/releases/ubuntu20/20211017
2021-12-03T08:02:23.1283810Z  * [new branch]        releases/ubuntu20/20211101 -> origin/releases/ubuntu20/20211101
2021-12-03T08:02:23.1285436Z  * [new branch]        releases/ubuntu20/20211108 -> origin/releases/ubuntu20/20211108
2021-12-03T08:02:23.1290369Z  * [new branch]        releases/ubuntu20/20211114 -> origin/releases/ubuntu20/20211114
2021-12-03T08:02:23.1291225Z  * [new branch]        releases/ubuntu20/20211122 -> origin/releases/ubuntu20/20211122
2021-12-03T08:02:23.1292733Z  * [new branch]        releases/ubuntu20/20211129 -> origin/releases/ubuntu20/20211129
2021-12-03T08:02:23.1293639Z  * [new branch]        releases/win16/20200113 -> origin/releases/win16/20200113
2021-12-03T08:02:23.1295103Z  * [new branch]        releases/win16/20200120 -> origin/releases/win16/20200120
2021-12-03T08:02:23.1296954Z  * [new branch]        releases/win16/20200211 -> origin/releases/win16/20200211
2021-12-03T08:02:23.1299329Z  * [new branch]        releases/win16/20200217 -> origin/releases/win16/20200217
2021-12-03T08:02:23.1301549Z  * [new branch]        releases/win16/20200301 -> origin/releases/win16/20200301
2021-12-03T08:02:23.1303838Z  * [new branch]        releases/win16/20200308 -> origin/releases/win16/20200308
2021-12-03T08:02:23.1306092Z  * [new branch]        releases/win16/20200316 -> origin/releases/win16/20200316
2021-12-03T08:02:23.1309421Z  * [new branch]        releases/win16/20200323 -> origin/releases/win16/20200323
2021-12-03T08:02:23.1312005Z  * [new branch]        releases/win16/20200330 -> origin/releases/win16/20200330
2021-12-03T08:02:23.1313583Z  * [new branch]        releases/win16/20200331 -> origin/releases/win16/20200331
2021-12-03T08:02:23.1315442Z  * [new branch]        releases/win16/20200406 -> origin/releases/win16/20200406
2021-12-03T08:02:23.1317009Z  * [new branch]        releases/win16/20200416 -> origin/releases/win16/20200416
2021-12-03T08:02:23.1319078Z  * [new branch]        releases/win16/20200426 -> origin/releases/win16/20200426
2021-12-03T08:02:23.1320623Z  * [new branch]        releases/win16/20200505 -> origin/releases/win16/20200505
2021-12-03T08:02:23.1322707Z  * [new branch]        releases/win16/20200512 -> origin/releases/win16/20200512
2021-12-03T08:02:23.1325035Z  * [new branch]        releases/win16/20200517 -> origin/releases/win16/20200517
2021-12-03T08:02:23.1327280Z  * [new branch]        releases/win16/20200524 -> origin/releases/win16/20200524
2021-12-03T08:02:23.1329335Z  * [new branch]        releases/win16/20200531 -> origin/releases/win16/20200531
2021-12-03T08:02:23.1331259Z  * [new branch]        releases/win16/20200604 -> origin/releases/win16/20200604
2021-12-03T08:02:23.1333416Z  * [new branch]        releases/win16/20200614 -> origin/releases/win16/20200614
2021-12-03T08:02:23.1335745Z  * [new branch]        releases/win16/20200621 -> origin/releases/win16/20200621
2021-12-03T08:02:23.1338036Z  * [new branch]        releases/win16/20200625 -> origin/releases/win16/20200625
2021-12-03T08:02:23.1340337Z  * [new branch]        releases/win16/20200628 -> origin/releases/win16/20200628
2021-12-03T08:02:23.1342510Z  * [new branch]        releases/win16/20200630 -> origin/releases/win16/20200630
2021-12-03T08:02:23.1344604Z  * [new branch]        releases/win16/20200706 -> origin/releases/win16/20200706
2021-12-03T08:02:23.1347067Z  * [new branch]        releases/win16/20200713 -> origin/releases/win16/20200713
2021-12-03T08:02:23.1349300Z  * [new branch]        releases/win16/20200720 -> origin/releases/win16/20200720
2021-12-03T08:02:23.1351442Z  * [new branch]        releases/win16/20200726 -> origin/releases/win16/20200726
2021-12-03T08:02:23.1353657Z  * [new branch]        releases/win16/20200802 -> origin/releases/win16/20200802
2021-12-03T08:02:23.1355926Z  * [new branch]        releases/win16/20200811 -> origin/releases/win16/20200811
2021-12-03T08:02:23.1358076Z  * [new branch]        releases/win16/20200820 -> origin/releases/win16/20200820
2021-12-03T08:02:23.1360314Z  * [new branch]        releases/win16/20200827 -> origin/releases/win16/20200827
2021-12-03T08:02:23.1362454Z  * [new branch]        releases/win16/20200913 -> origin/releases/win16/20200913
2021-12-03T08:02:23.1364691Z  * [new branch]        releases/win16/20200913-docs -> origin/releases/win16/20200913-docs
2021-12-03T08:02:23.1366795Z  * [new branch]        releases/win16/20200917 -> origin/releases/win16/20200917
2021-12-03T08:02:23.1368787Z  * [new branch]        releases/win16/20200917-docs -> origin/releases/win16/20200917-docs
2021-12-03T08:02:23.1370839Z  * [new branch]        releases/win16/20200920 -> origin/releases/win16/20200920
2021-12-03T08:02:23.1373135Z  * [new branch]        releases/win16/20201012 -> origin/releases/win16/20201012
2021-12-03T08:02:23.1375475Z  * [new branch]        releases/win16/20201020 -> origin/releases/win16/20201020
2021-12-03T08:02:23.1377654Z  * [new branch]        releases/win16/20201101 -> origin/releases/win16/20201101
2021-12-03T08:02:23.1379954Z  * [new branch]        releases/win16/20201101-docs -> origin/releases/win16/20201101-docs
2021-12-03T08:02:23.1382143Z  * [new branch]        releases/win16/20201102 -> origin/releases/win16/20201102
2021-12-03T08:02:23.1384115Z  * [new branch]        releases/win16/20201102-docs -> origin/releases/win16/20201102-docs
2021-12-03T08:02:23.1386309Z  * [new branch]        releases/win16/20201108 -> origin/releases/win16/20201108
2021-12-03T08:02:23.1389693Z  * [new branch]        releases/win16/20201116 -> origin/releases/win16/20201116
2021-12-03T08:02:23.1391538Z  * [new branch]        releases/win16/20201202 -> origin/releases/win16/20201202
2021-12-03T08:02:23.1393103Z  * [new branch]        releases/win16/20201210 -> origin/releases/win16/20201210
2021-12-03T08:02:23.1395112Z  * [new branch]        releases/win16/20210110 -> origin/releases/win16/20210110
2021-12-03T08:02:23.1396972Z  * [new branch]        releases/win16/20210118 -> origin/releases/win16/20210118
2021-12-03T08:02:23.1399551Z  * [new branch]        releases/win16/20210118-docs -> origin/releases/win16/20210118-docs
2021-12-03T08:02:23.1401423Z  * [new branch]        releases/win16/20210202 -> origin/releases/win16/20210202
2021-12-03T08:02:23.1403622Z  * [new branch]        releases/win16/20210202-docs -> origin/releases/win16/20210202-docs
2021-12-03T08:02:23.1405580Z  * [new branch]        releases/win16/20210209 -> origin/releases/win16/20210209
2021-12-03T08:02:23.1407823Z  * [new branch]        releases/win16/20210219 -> origin/releases/win16/20210219
2021-12-03T08:02:23.1410166Z  * [new branch]        releases/win16/20210309 -> origin/releases/win16/20210309
2021-12-03T08:02:23.1412374Z  * [new branch]        releases/win16/20210404 -> origin/releases/win16/20210404
2021-12-03T08:02:23.1414618Z  * [new branch]        releases/win16/20210411 -> origin/releases/win16/20210411
2021-12-03T08:02:23.1416857Z  * [new branch]        releases/win16/20210419 -> origin/releases/win16/20210419
2021-12-03T08:02:23.1418943Z  * [new branch]        releases/win16/20210425 -> origin/releases/win16/20210425
2021-12-03T08:02:23.1421196Z  * [new branch]        releases/win16/20210509 -> origin/releases/win16/20210509
2021-12-03T08:02:23.1423441Z  * [new branch]        releases/win16/20210516 -> origin/releases/win16/20210516
2021-12-03T08:02:23.1425846Z  * [new branch]        releases/win16/20210525 -> origin/releases/win16/20210525
2021-12-03T08:02:23.1428036Z  * [new branch]        releases/win16/20210531 -> origin/releases/win16/20210531
2021-12-03T08:02:23.1430371Z  * [new branch]        releases/win16/20210609 -> origin/releases/win16/20210609
2021-12-03T08:02:23.1432572Z  * [new branch]        releases/win16/20210614 -> origin/releases/win16/20210614
2021-12-03T08:02:23.1434732Z  * [new branch]        releases/win16/20210620 -> origin/releases/win16/20210620
2021-12-03T08:02:23.1436999Z  * [new branch]        releases/win16/20210628 -> origin/releases/win16/20210628
2021-12-03T08:02:23.1439186Z  * [new branch]        releases/win16/20210711 -> origin/releases/win16/20210711
2021-12-03T08:02:23.1441533Z  * [new branch]        releases/win16/20210719 -> origin/releases/win16/20210719
2021-12-03T08:02:23.1443778Z  * [new branch]        releases/win16/20210725 -> origin/releases/win16/20210725
2021-12-03T08:02:23.1446242Z  * [new branch]        releases/win16/20210802 -> origin/releases/win16/20210802
2021-12-03T08:02:23.1448411Z  * [new branch]        releases/win16/20210810 -> origin/releases/win16/20210810
2021-12-03T08:02:23.1450613Z  * [new branch]        releases/win16/20210815 -> origin/releases/win16/20210815
2021-12-03T08:02:23.1452792Z  * [new branch]        releases/win16/20210901 -> origin/releases/win16/20210901
2021-12-03T08:02:23.1455054Z  * [new branch]        releases/win16/20210907 -> origin/releases/win16/20210907
2021-12-03T08:02:23.1457416Z  * [new branch]        releases/win16/20210914 -> origin/releases/win16/20210914
2021-12-03T08:02:23.1459660Z  * [new branch]        releases/win16/20210919 -> origin/releases/win16/20210919
2021-12-03T08:02:23.1461977Z  * [new branch]        releases/win16/20210927 -> origin/releases/win16/20210927
2021-12-03T08:02:23.1464187Z  * [new branch]        releases/win16/20211003 -> origin/releases/win16/20211003
2021-12-03T08:02:23.1466286Z  * [new branch]        releases/win16/20211011 -> origin/releases/win16/20211011
2021-12-03T08:02:23.1468738Z  * [new branch]        releases/win16/20211018 -> origin/releases/win16/20211018
2021-12-03T08:02:23.1471106Z  * [new branch]        releases/win16/20211102 -> origin/releases/win16/20211102
2021-12-03T08:02:23.1473335Z  * [new branch]        releases/win16/20211109 -> origin/releases/win16/20211109
2021-12-03T08:02:23.1475622Z  * [new branch]        releases/win16/20211115 -> origin/releases/win16/20211115
2021-12-03T08:02:23.1477882Z  * [new branch]        releases/win16/20211122 -> origin/releases/win16/20211122
2021-12-03T08:02:23.1480030Z  * [new branch]        releases/win16/20211229 -> origin/releases/win16/20211229
2021-12-03T08:02:23.1508147Z  * [new branch]        releases/win19/20200102 -> origin/releases/win19/20200102
2021-12-03T08:02:23.1509143Z  * [new branch]        releases/win19/20200113 -> origin/releases/win19/20200113
2021-12-03T08:02:23.1509928Z  * [new branch]        releases/win19/20200116 -> origin/releases/win19/20200116
2021-12-03T08:02:23.1510771Z  * [new branch]        releases/win19/20200212 -> origin/releases/win19/20200212
2021-12-03T08:02:23.1511621Z  * [new branch]        releases/win19/20200301 -> origin/releases/win19/20200301
2021-12-03T08:02:23.1512402Z  * [new branch]        releases/win19/20200308 -> origin/releases/win19/20200308
2021-12-03T08:02:23.1513261Z  * [new branch]        releases/win19/20200319 -> origin/releases/win19/20200319
2021-12-03T08:02:23.1514143Z  * [new branch]        releases/win19/20200330 -> origin/releases/win19/20200330
2021-12-03T08:02:23.1514955Z  * [new branch]        releases/win19/20200331 -> origin/releases/win19/20200331
2021-12-03T08:02:23.1515781Z  * [new branch]        releases/win19/20200407 -> origin/releases/win19/20200407
2021-12-03T08:02:23.1516569Z  * [new branch]        releases/win19/20200416 -> origin/releases/win19/20200416
2021-12-03T08:02:23.1517375Z  * [new branch]        releases/win19/20200426 -> origin/releases/win19/20200426
2021-12-03T08:02:23.1518163Z  * [new branch]        releases/win19/20200430 -> origin/releases/win19/20200430
2021-12-03T08:02:23.1518965Z  * [new branch]        releases/win19/20200511 -> origin/releases/win19/20200511
2021-12-03T08:02:23.1519778Z  * [new branch]        releases/win19/20200517 -> origin/releases/win19/20200517
2021-12-03T08:02:23.1520554Z  * [new branch]        releases/win19/20200524 -> origin/releases/win19/20200524
2021-12-03T08:02:23.1521374Z  * [new branch]        releases/win19/20200531 -> origin/releases/win19/20200531
2021-12-03T08:02:23.1522187Z  * [new branch]        releases/win19/20200608 -> origin/releases/win19/20200608
2021-12-03T08:02:23.1522974Z  * [new branch]        releases/win19/20200610 -> origin/releases/win19/20200610
2021-12-03T08:02:23.1523801Z  * [new branch]        releases/win19/20200621 -> origin/releases/win19/20200621
2021-12-03T08:02:23.1524574Z  * [new branch]        releases/win19/20200628 -> origin/releases/win19/20200628
2021-12-03T08:02:23.1525392Z  * [new branch]        releases/win19/20200630 -> origin/releases/win19/20200630
2021-12-03T08:02:23.1526191Z  * [new branch]        releases/win19/20200706 -> origin/releases/win19/20200706
2021-12-03T08:02:23.1526978Z  * [new branch]        releases/win19/20200714 -> origin/releases/win19/20200714
2021-12-03T08:02:23.1527797Z  * [new branch]        releases/win19/20200720 -> origin/releases/win19/20200720
2021-12-03T08:02:23.1528569Z  * [new branch]        releases/win19/20200726 -> origin/releases/win19/20200726
2021-12-03T08:02:23.1529398Z  * [new branch]        releases/win19/20200802 -> origin/releases/win19/20200802
2021-12-03T08:02:23.1530227Z  * [new branch]        releases/win19/20200811 -> origin/releases/win19/20200811
2021-12-03T08:02:23.1531018Z  * [new branch]        releases/win19/20200820 -> origin/releases/win19/20200820
2021-12-03T08:02:23.1531845Z  * [new branch]        releases/win19/20200827 -> origin/releases/win19/20200827
2021-12-03T08:02:23.1532606Z  * [new branch]        releases/win19/20200917 -> origin/releases/win19/20200917
2021-12-03T08:02:23.1533479Z  * [new branch]        releases/win19/20200917-docs -> origin/releases/win19/20200917-docs
2021-12-03T08:02:23.1534340Z  * [new branch]        releases/win19/20200920 -> origin/releases/win19/20200920
2021-12-03T08:02:23.1535114Z  * [new branch]        releases/win19/20200927 -> origin/releases/win19/20200927
2021-12-03T08:02:23.1535996Z  * [new branch]        releases/win19/20200927-docs -> origin/releases/win19/20200927-docs
2021-12-03T08:02:23.1536860Z  * [new branch]        releases/win19/20201004 -> origin/releases/win19/20201004
2021-12-03T08:02:23.1537661Z  * [new branch]        releases/win19/20201011 -> origin/releases/win19/20201011
2021-12-03T08:02:23.1541560Z  * [new branch]        releases/win19/20201021 -> origin/releases/win19/20201021
2021-12-03T08:02:23.1542381Z  * [new branch]        releases/win19/20201102 -> origin/releases/win19/20201102
2021-12-03T08:02:23.1543334Z  * [new branch]        releases/win19/20201102-docs -> origin/releases/win19/20201102-docs
2021-12-03T08:02:23.1547193Z  * [new branch]        releases/win19/20201108 -> origin/releases/win19/20201108
2021-12-03T08:02:23.1548003Z  * [new branch]        releases/win19/20201116 -> origin/releases/win19/20201116
2021-12-03T08:02:23.1549400Z  * [new branch]        releases/win19/20201202 -> origin/releases/win19/20201202
2021-12-03T08:02:23.1552641Z  * [new branch]        releases/win19/20201210 -> origin/releases/win19/20201210
2021-12-03T08:02:23.1553699Z  * [new branch]        releases/win19/20210110 -> origin/releases/win19/20210110
2021-12-03T08:02:23.1557060Z  * [new branch]        releases/win19/20210118 -> origin/releases/win19/20210118
2021-12-03T08:02:23.1558269Z  * [new branch]        releases/win19/20210118-docs -> origin/releases/win19/20210118-docs
2021-12-03T08:02:23.1561329Z  * [new branch]        releases/win19/20210121 -> origin/releases/win19/20210121
2021-12-03T08:02:23.1562461Z  * [new branch]        releases/win19/20210202 -> origin/releases/win19/20210202
2021-12-03T08:02:23.1566177Z  * [new branch]        releases/win19/20210202-docs -> origin/releases/win19/20210202-docs
2021-12-03T08:02:23.1567030Z  * [new branch]        releases/win19/20210211 -> origin/releases/win19/20210211
2021-12-03T08:02:23.1568354Z  * [new branch]        releases/win19/20210219 -> origin/releases/win19/20210219
2021-12-03T08:02:23.1571564Z  * [new branch]        releases/win19/20210309 -> origin/releases/win19/20210309
2021-12-03T08:02:23.1572724Z  * [new branch]        releases/win19/20210316 -> origin/releases/win19/20210316
2021-12-03T08:02:23.1575787Z  * [new branch]        releases/win19/20210329 -> origin/releases/win19/20210329
2021-12-03T08:02:23.1577028Z  * [new branch]        releases/win19/20210330 -> origin/releases/win19/20210330
2021-12-03T08:02:23.1580074Z  * [new branch]        releases/win19/20210404 -> origin/releases/win19/20210404
2021-12-03T08:02:23.1581133Z  * [new branch]        releases/win19/20210411 -> origin/releases/win19/20210411
2021-12-03T08:02:23.1584256Z  * [new branch]        releases/win19/20210419 -> origin/releases/win19/20210419
2021-12-03T08:02:23.1585363Z  * [new branch]        releases/win19/20210425 -> origin/releases/win19/20210425
2021-12-03T08:02:23.1588567Z  * [new branch]        releases/win19/20210509 -> origin/releases/win19/20210509
2021-12-03T08:02:23.1589688Z  * [new branch]        releases/win19/20210516 -> origin/releases/win19/20210516
2021-12-03T08:02:23.1592921Z  * [new branch]        releases/win19/20210525 -> origin/releases/win19/20210525
2021-12-03T08:02:23.1594005Z  * [new branch]        releases/win19/20210531 -> origin/releases/win19/20210531
2021-12-03T08:02:23.1597090Z  * [new branch]        releases/win19/20210608 -> origin/releases/win19/20210608
2021-12-03T08:02:23.1598325Z  * [new branch]        releases/win19/20210616 -> origin/releases/win19/20210616
2021-12-03T08:02:23.1601356Z  * [new branch]        releases/win19/20210620 -> origin/releases/win19/20210620
2021-12-03T08:02:23.1602881Z  * [new branch]        releases/win19/20210628 -> origin/releases/win19/20210628
2021-12-03T08:02:23.1607295Z  * [new branch]        releases/win19/20210711 -> origin/releases/win19/20210711
2021-12-03T08:02:23.1610274Z  * [new branch]        releases/win19/20210719 -> origin/releases/win19/20210719
2021-12-03T08:02:23.1613094Z  * [new branch]        releases/win19/20210725 -> origin/releases/win19/20210725
2021-12-03T08:02:23.1616044Z  * [new branch]        releases/win19/20210803 -> origin/releases/win19/20210803
2021-12-03T08:02:23.1619013Z  * [new branch]        releases/win19/20210810 -> origin/releases/win19/20210810
2021-12-03T08:02:23.1621960Z  * [new branch]        releases/win19/20210815 -> origin/releases/win19/20210815
2021-12-03T08:02:23.1625014Z  * [new branch]        releases/win19/20210903 -> origin/releases/win19/20210903
2021-12-03T08:02:23.1629200Z  * [new branch]        releases/win19/20210907 -> origin/releases/win19/20210907
2021-12-03T08:02:23.1632153Z  * [new branch]        releases/win19/20210914 -> origin/releases/win19/20210914
2021-12-03T08:02:23.1635253Z  * [new branch]        releases/win19/20210920 -> origin/releases/win19/20210920
2021-12-03T08:02:23.1638270Z  * [new branch]        releases/win19/20210928 -> origin/releases/win19/20210928
2021-12-03T08:02:23.1641264Z  * [new branch]        releases/win19/20211003 -> origin/releases/win19/20211003
2021-12-03T08:02:23.1644180Z  * [new branch]        releases/win19/20211011 -> origin/releases/win19/20211011
2021-12-03T08:02:23.1647097Z  * [new branch]        releases/win19/20211018 -> origin/releases/win19/20211018
2021-12-03T08:02:23.1650028Z  * [new branch]        releases/win19/20211102 -> origin/releases/win19/20211102
2021-12-03T08:02:23.1652932Z  * [new branch]        releases/win19/20211110 -> origin/releases/win19/20211110
2021-12-03T08:02:23.1655872Z  * [new branch]        releases/win19/20211122 -> origin/releases/win19/20211122
2021-12-03T08:02:23.1658850Z  * [new branch]        releases/win19/20211229 -> origin/releases/win19/20211229
2021-12-03T08:02:23.1662334Z  * [new branch]        releases/win22/20210819 -> origin/releases/win22/20210819
2021-12-03T08:02:23.1665102Z  * [new branch]        releases/win22/20210819-docs -> origin/releases/win22/20210819-docs
2021-12-03T08:02:23.1668322Z  * [new branch]        releases/win22/20210901 -> origin/releases/win22/20210901
2021-12-03T08:02:23.1780806Z  * [new branch]        releases/win22/20210907 -> origin/releases/win22/20210907
2021-12-03T08:02:23.1845693Z  * [new branch]        releases/win22/20210914 -> origin/releases/win22/20210914
2021-12-03T08:02:23.1846705Z  * [new branch]        releases/win22/20210920 -> origin/releases/win22/20210920
2021-12-03T08:02:23.1847488Z  * [new branch]        releases/win22/20210927 -> origin/releases/win22/20210927
2021-12-03T08:02:23.1848263Z  * [new branch]        releases/win22/20211003 -> origin/releases/win22/20211003
2021-12-03T08:02:23.1849041Z  * [new branch]        releases/win22/20211011 -> origin/releases/win22/20211011
2021-12-03T08:02:23.1849786Z  * [new branch]        releases/win22/20211018 -> origin/releases/win22/20211018
2021-12-03T08:02:23.1850536Z  * [new branch]        releases/win22/20211102 -> origin/releases/win22/20211102
2021-12-03T08:02:23.1851290Z  * [new branch]        releases/win22/20211109 -> origin/releases/win22/20211109
2021-12-03T08:02:23.1852041Z  * [new branch]        releases/win22/20211115 -> origin/releases/win22/20211115
2021-12-03T08:02:23.1852780Z  * [new branch]        releases/win22/20211122 -> origin/releases/win22/20211122
2021-12-03T08:02:23.1853536Z  * [new branch]        releases/win22/20211130 -> origin/releases/win22/20211130
2021-12-03T08:02:23.1854793Z  * [new branch]        revert-3747-windows-stick-to-mongodb-4 -> origin/revert-3747-windows-stick-to-mongodb-4
2021-12-03T08:02:23.1856301Z  * [new branch]        revert-4050-macos-install-mono -> origin/revert-4050-macos-install-mono
2021-12-03T08:02:23.1857705Z  * [new branch]        revert-4135-v-dimago/macos-update-software -> origin/revert-4135-v-dimago/macos-update-software
2021-12-03T08:02:23.1858914Z  * [new branch]        revert-4389-fix_macos_vcpkg -> origin/revert-4389-fix_macos_vcpkg
2021-12-03T08:02:23.1859945Z  * [new branch]        windows-server-2022-move -> origin/windows-server-2022-move
2021-12-03T08:02:23.1860837Z  * [new tag]           Ubuntu18/20201102.0     -> Ubuntu18/20201102.0
2021-12-03T08:02:23.1861516Z  * [new tag]           macOS-10.15/20201017.1  -> macOS-10.15/20201017.1
2021-12-03T08:02:23.1862182Z  * [new tag]           macOS-10.15/20201026.2  -> macOS-10.15/20201026.2
2021-12-03T08:02:23.1862860Z  * [new tag]           macOS-10.15/20201107.1  -> macOS-10.15/20201107.1
2021-12-03T08:02:23.1863521Z  * [new tag]           macOS-10.15/20201115.1  -> macOS-10.15/20201115.1
2021-12-03T08:02:23.1864349Z  * [new tag]           macOS-10.15/20201130.3  -> macOS-10.15/20201130.3
2021-12-03T08:02:23.1865029Z  * [new tag]           macOS-10.15/20201212.1  -> macOS-10.15/20201212.1
2021-12-03T08:02:23.1865683Z  * [new tag]           macOS-10.15/20210110.1  -> macOS-10.15/20210110.1
2021-12-03T08:02:23.1866330Z  * [new tag]           macOS-10.15/20210123.2  -> macOS-10.15/20210123.2
2021-12-03T08:02:23.1873824Z  * [new tag]           macOS-10.15/20210130.1  -> macOS-10.15/20210130.1
2021-12-03T08:02:23.1896573Z  * [new tag]           macOS-10.15/20210207.2  -> macOS-10.15/20210207.2
2021-12-03T08:02:23.1897967Z  * [new tag]           macOS-10.15/20210213.1  -> macOS-10.15/20210213.1
2021-12-03T08:02:23.1899321Z  * [new tag]           macOS-10.15/20210220.1  -> macOS-10.15/20210220.1
2021-12-03T08:02:23.1901443Z  * [new tag]           macOS-10.15/20210302.1  -> macOS-10.15/20210302.1
2021-12-03T08:02:23.1902829Z  * [new tag]           macOS-10.15/20210307.1  -> macOS-10.15/20210307.1
2021-12-03T08:02:23.1920786Z  * [new tag]           macOS-10.15/20210314.1  -> macOS-10.15/20210314.1
2021-12-03T08:02:23.1921533Z  * [new tag]           macOS-10.15/20210321.1  -> macOS-10.15/20210321.1
2021-12-03T08:02:23.1922203Z  * [new tag]           macOS-10.15/20210327.1  -> macOS-10.15/20210327.1
2021-12-03T08:02:23.1922869Z  * [new tag]           macOS-10.15/20210404.1  -> macOS-10.15/20210404.1
2021-12-03T08:02:23.1923514Z  * [new tag]           macOS-10.15/20210409.1  -> macOS-10.15/20210409.1
2021-12-03T08:02:23.1924176Z  * [new tag]           macOS-10.15/20210412.2  -> macOS-10.15/20210412.2
2021-12-03T08:02:23.1924826Z  * [new tag]           macOS-10.15/20210419.2  -> macOS-10.15/20210419.2
2021-12-03T08:02:23.1925471Z  * [new tag]           macOS-10.15/20210423.1  -> macOS-10.15/20210423.1
2021-12-03T08:02:23.1926135Z  * [new tag]           macOS-10.15/20210503.2  -> macOS-10.15/20210503.2
2021-12-03T08:02:23.1926769Z  * [new tag]           macOS-10.15/20210510.1  -> macOS-10.15/20210510.1
2021-12-03T08:02:23.1927418Z  * [new tag]           macOS-10.15/20210516.1  -> macOS-10.15/20210516.1
2021-12-03T08:02:23.1928076Z  * [new tag]           macOS-10.15/20210525.2  -> macOS-10.15/20210525.2
2021-12-03T08:02:23.1928709Z  * [new tag]           macOS-10.15/20210531.1  -> macOS-10.15/20210531.1
2021-12-03T08:02:23.1929355Z  * [new tag]           macOS-10.15/20210607.1  -> macOS-10.15/20210607.1
2021-12-03T08:02:23.1929996Z  * [new tag]           macOS-10.15/20210612.1  -> macOS-10.15/20210612.1
2021-12-03T08:02:23.1930637Z  * [new tag]           macOS-10.15/20210620.1  -> macOS-10.15/20210620.1
2021-12-03T08:02:23.1931281Z  * [new tag]           macOS-10.15/20210626.1  -> macOS-10.15/20210626.1
2021-12-03T08:02:23.1931919Z  * [new tag]           macOS-10.15/20210712.4  -> macOS-10.15/20210712.4
2021-12-03T08:02:23.1932570Z  * [new tag]           macOS-10.15/20210718.2  -> macOS-10.15/20210718.2
2021-12-03T08:02:23.1933198Z  * [new tag]           macOS-10.15/20210725.1  -> macOS-10.15/20210725.1
2021-12-03T08:02:23.1933847Z  * [new tag]           macOS-10.15/20210801.1  -> macOS-10.15/20210801.1
2021-12-03T08:02:23.1934497Z  * [new tag]           macOS-10.15/20210808.1  -> macOS-10.15/20210808.1
2021-12-03T08:02:23.1935136Z  * [new tag]           macOS-10.15/20210814.1  -> macOS-10.15/20210814.1
2021-12-03T08:02:23.1935780Z  * [new tag]           macOS-10.15/20210831.3  -> macOS-10.15/20210831.3
2021-12-03T08:02:23.1936411Z  * [new tag]           macOS-10.15/20210905.2  -> macOS-10.15/20210905.2
2021-12-03T08:02:23.1937056Z  * [new tag]           macOS-10.15/20210914.1  -> macOS-10.15/20210914.1
2021-12-03T08:02:23.1937703Z  * [new tag]           macOS-10.15/20210919.1  -> macOS-10.15/20210919.1
2021-12-03T08:02:23.1938333Z  * [new tag]           macOS-10.15/20210927.1  -> macOS-10.15/20210927.1
2021-12-03T08:02:23.1938990Z  * [new tag]           macOS-10.15/20211002.1  -> macOS-10.15/20211002.1
2021-12-03T08:02:23.1939628Z  * [new tag]           macOS-10.15/20211011.2  -> macOS-10.15/20211011.2
2021-12-03T08:02:23.1940415Z  * [new tag]           macOS-10.15/20211016.1  -> macOS-10.15/20211016.1
2021-12-03T08:02:23.1941088Z  * [new tag]           macOS-10.15/20211029.1  -> macOS-10.15/20211029.1
2021-12-03T08:02:23.1941728Z  * [new tag]           macOS-10.15/20211106.1  -> macOS-10.15/20211106.1
2021-12-03T08:02:23.1942391Z  * [new tag]           macOS-10.15/20211114.1  -> macOS-10.15/20211114.1
2021-12-03T08:02:23.1943039Z  * [new tag]           macOS-10.15/20211120.1  -> macOS-10.15/20211120.1
2021-12-03T08:02:23.1943697Z  * [new tag]           macOS-10.15/20211126.1  -> macOS-10.15/20211126.1
2021-12-03T08:02:23.1944361Z  * [new tag]           macOS-11.0/20201024.1   -> macOS-11.0/20201024.1
2021-12-03T08:02:23.1945010Z  * [new tag]           macOS-11.0/20201102.1   -> macOS-11.0/20201102.1
2021-12-03T08:02:23.1945764Z  * [new tag]           macOS-11.0/20201107.1   -> macOS-11.0/20201107.1
2021-12-03T08:02:23.1946469Z  * [new tag]           macOS-11.0/20201116.13  -> macOS-11.0/20201116.13
2021-12-03T08:02:23.1947338Z  * [new tag]           macOS-11.0/20201130.3   -> macOS-11.0/20201130.3
2021-12-03T08:02:23.1947995Z  * [new tag]           macOS-11.0/20201213.1   -> macOS-11.0/20201213.1
2021-12-03T08:02:23.1948626Z  * [new tag]           macOS-11.0/20210110.1   -> macOS-11.0/20210110.1
2021-12-03T08:02:23.1949276Z  * [new tag]           macOS-11.0/20210118.2   -> macOS-11.0/20210118.2
2021-12-03T08:02:23.1949906Z  * [new tag]           macOS-11.0/20210123.1   -> macOS-11.0/20210123.1
2021-12-03T08:02:23.1950552Z  * [new tag]           macOS-11.0/20210131.1   -> macOS-11.0/20210131.1
2021-12-03T08:02:23.1951180Z  * [new tag]           macOS-11.0/20210208.1   -> macOS-11.0/20210208.1
2021-12-03T08:02:23.1951802Z  * [new tag]           macOS-11.0/20210216.3   -> macOS-11.0/20210216.3
2021-12-03T08:02:23.1952440Z  * [new tag]           macOS-11.0/20210219.1   -> macOS-11.0/20210219.1
2021-12-03T08:02:23.1953062Z  * [new tag]           macOS-11.0/20210302.1   -> macOS-11.0/20210302.1
2021-12-03T08:02:23.1953692Z  * [new tag]           macOS-11.0/20210308.1   -> macOS-11.0/20210308.1
2021-12-03T08:02:23.1954333Z  * [new tag]           macOS-11.0/20210314.1   -> macOS-11.0/20210314.1
2021-12-03T08:02:23.1954955Z  * [new tag]           macOS-11.0/20210321.1   -> macOS-11.0/20210321.1
2021-12-03T08:02:23.1955598Z  * [new tag]           macOS-11.0/20210328.1   -> macOS-11.0/20210328.1
2021-12-03T08:02:23.1956218Z  * [new tag]           macOS-11.0/20210404.2   -> macOS-11.0/20210404.2
2021-12-03T08:02:23.1990279Z  * [new tag]           macOS-11.0/20210409.1   -> macOS-11.0/20210409.1
2021-12-03T08:02:23.2028017Z  * [new tag]           macOS-11.0/20210412.3   -> macOS-11.0/20210412.3
2021-12-03T08:02:23.2029802Z  * [new tag]           macOS-11.0/20210418.1   -> macOS-11.0/20210418.1
2021-12-03T08:02:23.2030545Z  * [new tag]           macOS-11.0/20210420.1   -> macOS-11.0/20210420.1
2021-12-03T08:02:23.2031737Z  * [new tag]           macOS-11.0/20210424.1   -> macOS-11.0/20210424.1
2021-12-03T08:02:23.2032934Z  * [new tag]           macOS-11.0/20210503.1   -> macOS-11.0/20210503.1
2021-12-03T08:02:23.2034119Z  * [new tag]           macOS-11.0/20210510.1   -> macOS-11.0/20210510.1
2021-12-03T08:02:23.2035283Z  * [new tag]           macOS-11.0/20210516.1   -> macOS-11.0/20210516.1
2021-12-03T08:02:23.2036460Z  * [new tag]           macOS-11/20210523.1     -> macOS-11/20210523.1
2021-12-03T08:02:23.2037660Z  * [new tag]           macOS-11/20210531.1     -> macOS-11/20210531.1
2021-12-03T08:02:23.2038808Z  * [new tag]           macOS-11/20210608.6     -> macOS-11/20210608.6
2021-12-03T08:02:23.2039960Z  * [new tag]           macOS-11/20210614.1     -> macOS-11/20210614.1
2021-12-03T08:02:23.2041095Z  * [new tag]           macOS-11/20210620.1     -> macOS-11/20210620.1
2021-12-03T08:02:23.2042267Z  * [new tag]           macOS-11/20210626.1     -> macOS-11/20210626.1
2021-12-03T08:02:23.2043416Z  * [new tag]           macOS-11/20210712.4     -> macOS-11/20210712.4
2021-12-03T08:02:23.2044548Z  * [new tag]           macOS-11/20210718.3     -> macOS-11/20210718.3
2021-12-03T08:02:23.2045868Z  * [new tag]           macOS-11/20210724.1     -> macOS-11/20210724.1
2021-12-03T08:02:23.2047122Z  * [new tag]           macOS-11/20210801.1     -> macOS-11/20210801.1
2021-12-03T08:02:23.2048277Z  * [new tag]           macOS-11/20210808.1     -> macOS-11/20210808.1
2021-12-03T08:02:23.2049415Z  * [new tag]           macOS-11/20210814.1     -> macOS-11/20210814.1
2021-12-03T08:02:23.2050078Z  * [new tag]           macOS-11/20210831.3     -> macOS-11/20210831.3
2021-12-03T08:02:23.2051269Z  * [new tag]           macOS-11/20210905.2     -> macOS-11/20210905.2
2021-12-03T08:02:23.2052395Z  * [new tag]           macOS-11/20210914.4     -> macOS-11/20210914.4
2021-12-03T08:02:23.2053530Z  * [new tag]           macOS-11/20210917.1     -> macOS-11/20210917.1
2021-12-03T08:02:23.2054829Z  * [new tag]           macOS-11/20210927.2     -> macOS-11/20210927.2
2021-12-03T08:02:23.2055997Z  * [new tag]           macOS-11/20211001.1     -> macOS-11/20211001.1
2021-12-03T08:02:23.2057292Z  * [new tag]           macOS-11/20211011.3     -> macOS-11/20211011.3
2021-12-03T08:02:23.2058518Z  * [new tag]           macOS-11/20211018.1     -> macOS-11/20211018.1
2021-12-03T08:02:23.2062041Z  * [new tag]           macOS-11/20211029.3     -> macOS-11/20211029.3
2021-12-03T08:02:23.2121777Z  * [new tag]           macOS-11/20211106.1     -> macOS-11/20211106.1
2021-12-03T08:02:23.2122445Z  * [new tag]           macOS-11/20211114.1     -> macOS-11/20211114.1
2021-12-03T08:02:23.2123067Z  * [new tag]           macOS-11/20211120.1     -> macOS-11/20211120.1
2021-12-03T08:02:23.2123689Z  * [new tag]           macOS-11/20211127.1     -> macOS-11/20211127.1
2021-12-03T08:02:23.2124328Z  * [new tag]           macos-10.15/20200530.1  -> macos-10.15/20200530.1
2021-12-03T08:02:23.2125013Z  * [new tag]           macos-10.15/20200604.1  -> macos-10.15/20200604.1
2021-12-03T08:02:23.2125681Z  * [new tag]           macos-10.15/20200610.3  -> macos-10.15/20200610.3
2021-12-03T08:02:23.2126341Z  * [new tag]           macos-10.15/20200618.1  -> macos-10.15/20200618.1
2021-12-03T08:02:23.2127007Z  * [new tag]           macos-10.15/20200625.2  -> macos-10.15/20200625.2
2021-12-03T08:02:23.2127663Z  * [new tag]           macos-10.15/20200702.1  -> macos-10.15/20200702.1
2021-12-03T08:02:23.2128308Z  * [new tag]           macos-10.15/20200707.3  -> macos-10.15/20200707.3
2021-12-03T08:02:23.2128964Z  * [new tag]           macos-10.15/20200716.2  -> macos-10.15/20200716.2
2021-12-03T08:02:23.2129608Z  * [new tag]           macos-10.15/20200728.1  -> macos-10.15/20200728.1
2021-12-03T08:02:23.2130274Z  * [new tag]           macos-10.15/20200802.1  -> macos-10.15/20200802.1
2021-12-03T08:02:23.2130922Z  * [new tag]           macos-10.15/20200806.4  -> macos-10.15/20200806.4
2021-12-03T08:02:23.2131566Z  * [new tag]           macos-10.15/20200819.1  -> macos-10.15/20200819.1
2021-12-03T08:02:23.2132219Z  * [new tag]           macos-10.15/20200825.1  -> macos-10.15/20200825.1
2021-12-03T08:02:23.2132866Z  * [new tag]           macos-10.15/20200829.1  -> macos-10.15/20200829.1
2021-12-03T08:02:23.2133520Z  * [new tag]           macos-10.15/20200903.1  -> macos-10.15/20200903.1
2021-12-03T08:02:23.2134158Z  * [new tag]           macos-10.15/20200913.1  -> macos-10.15/20200913.1
2021-12-03T08:02:23.2134801Z  * [new tag]           macos-10.15/20200916.1  -> macos-10.15/20200916.1
2021-12-03T08:02:23.2135448Z  * [new tag]           macos-10.15/20200918.1  -> macos-10.15/20200918.1
2021-12-03T08:02:23.2136089Z  * [new tag]           macos-10.15/20201003.1  -> macos-10.15/20201003.1
2021-12-03T08:02:23.2136749Z  * [new tag]           ubuntu16/20200102.1     -> ubuntu16/20200102.1
2021-12-03T08:02:23.2137388Z  * [new tag]           ubuntu16/20200113.1     -> ubuntu16/20200113.1
2021-12-03T08:02:23.2138007Z  * [new tag]           ubuntu16/20200119.1     -> ubuntu16/20200119.1
2021-12-03T08:02:23.2138647Z  * [new tag]           ubuntu16/20200130.1     -> ubuntu16/20200130.1
2021-12-03T08:02:23.2139261Z  * [new tag]           ubuntu16/20200211.1     -> ubuntu16/20200211.1
2021-12-03T08:02:23.2140028Z  * [new tag]           ubuntu16/20200217.1     -> ubuntu16/20200217.1
2021-12-03T08:02:23.2140672Z  * [new tag]           ubuntu16/20200225.0     -> ubuntu16/20200225.0
2021-12-03T08:02:23.2141281Z  * [new tag]           ubuntu16/20200301.1     -> ubuntu16/20200301.1
2021-12-03T08:02:23.2141910Z  * [new tag]           ubuntu16/20200308.0     -> ubuntu16/20200308.0
2021-12-03T08:02:23.2142520Z  * [new tag]           ubuntu16/20200315.1     -> ubuntu16/20200315.1
2021-12-03T08:02:23.2143144Z  * [new tag]           ubuntu16/20200323.1     -> ubuntu16/20200323.1
2021-12-03T08:02:23.2143766Z  * [new tag]           ubuntu16/20200330.1     -> ubuntu16/20200330.1
2021-12-03T08:02:23.2144454Z  * [new tag]           ubuntu16/20200406.2     -> ubuntu16/20200406.2
2021-12-03T08:02:23.2145080Z  * [new tag]           ubuntu16/20200415.3     -> ubuntu16/20200415.3
2021-12-03T08:02:23.2145694Z  * [new tag]           ubuntu16/20200426.1     -> ubuntu16/20200426.1
2021-12-03T08:02:23.2146362Z  * [new tag]           ubuntu16/20200428.2     -> ubuntu16/20200428.2
2021-12-03T08:02:23.2147093Z  * [new tag]           ubuntu16/20200430.2     -> ubuntu16/20200430.2
2021-12-03T08:02:23.2147710Z  * [new tag]           ubuntu16/20200512.2     -> ubuntu16/20200512.2
2021-12-03T08:02:23.2148328Z  * [new tag]           ubuntu16/20200517.1     -> ubuntu16/20200517.1
2021-12-03T08:02:23.2148931Z  * [new tag]           ubuntu16/20200525.2     -> ubuntu16/20200525.2
2021-12-03T08:02:23.2149546Z  * [new tag]           ubuntu16/20200531.1     -> ubuntu16/20200531.1
2021-12-03T08:02:23.2150178Z  * [new tag]           ubuntu16/20200604.1     -> ubuntu16/20200604.1
2021-12-03T08:02:23.2150784Z  * [new tag]           ubuntu16/20200614.1     -> ubuntu16/20200614.1
2021-12-03T08:02:23.2151405Z  * [new tag]           ubuntu16/20200621.1     -> ubuntu16/20200621.1
2021-12-03T08:02:23.2152015Z  * [new tag]           ubuntu16/20200625.0     -> ubuntu16/20200625.0
2021-12-03T08:02:23.2152693Z  * [new tag]           ubuntu16/20200705.1     -> ubuntu16/20200705.1
2021-12-03T08:02:23.2153313Z  * [new tag]           ubuntu16/20200709.0     -> ubuntu16/20200709.0
2021-12-03T08:02:23.2153921Z  * [new tag]           ubuntu16/20200717.1     -> ubuntu16/20200717.1
2021-12-03T08:02:23.2154544Z  * [new tag]           ubuntu16/20200723.1     -> ubuntu16/20200723.1
2021-12-03T08:02:23.2155148Z  * [new tag]           ubuntu16/20200802.1     -> ubuntu16/20200802.1
2021-12-03T08:02:23.2155771Z  * [new tag]           ubuntu16/20200806.0     -> ubuntu16/20200806.0
2021-12-03T08:02:23.2156389Z  * [new tag]           ubuntu16/20200817.1     -> ubuntu16/20200817.1
2021-12-03T08:02:23.2157002Z  * [new tag]           ubuntu16/20200820.1     -> ubuntu16/20200820.1
2021-12-03T08:02:23.2157623Z  * [new tag]           ubuntu16/20200825.1     -> ubuntu16/20200825.1
2021-12-03T08:02:23.2158231Z  * [new tag]           ubuntu16/20200901.1     -> ubuntu16/20200901.1
2021-12-03T08:02:23.2158847Z  * [new tag]           ubuntu16/20200908.1     -> ubuntu16/20200908.1
2021-12-03T08:02:23.2159469Z  * [new tag]           ubuntu16/20200914.1     -> ubuntu16/20200914.1
2021-12-03T08:02:23.2160074Z  * [new tag]           ubuntu16/20200920.1     -> ubuntu16/20200920.1
2021-12-03T08:02:23.2160692Z  * [new tag]           ubuntu16/20201004.1     -> ubuntu16/20201004.1
2021-12-03T08:02:23.2161295Z  * [new tag]           ubuntu16/20201012.1     -> ubuntu16/20201012.1
2021-12-03T08:02:23.2161910Z  * [new tag]           ubuntu16/20201015.1     -> ubuntu16/20201015.1
2021-12-03T08:02:23.2162526Z  * [new tag]           ubuntu16/20201026.1     -> ubuntu16/20201026.1
2021-12-03T08:02:23.2163132Z  * [new tag]           ubuntu16/20201101.1     -> ubuntu16/20201101.1
2021-12-03T08:02:23.2163758Z  * [new tag]           ubuntu16/20201102.0     -> ubuntu16/20201102.0
2021-12-03T08:02:23.2164365Z  * [new tag]           ubuntu16/20201108.1     -> ubuntu16/20201108.1
2021-12-03T08:02:23.2164984Z  * [new tag]           ubuntu16/20201116.1     -> ubuntu16/20201116.1
2021-12-03T08:02:23.2165680Z  * [new tag]           ubuntu16/20201129.1     -> ubuntu16/20201129.1
2021-12-03T08:02:23.2166297Z  * [new tag]           ubuntu16/20201210.0     -> ubuntu16/20201210.0
2021-12-03T08:02:23.2166910Z  * [new tag]           ubuntu16/20210111.1     -> ubuntu16/20210111.1
2021-12-03T08:02:23.2167516Z  * [new tag]           ubuntu16/20210117.1     -> ubuntu16/20210117.1
2021-12-03T08:02:23.2168136Z  * [new tag]           ubuntu16/20210123.1     -> ubuntu16/20210123.1
2021-12-03T08:02:23.2168750Z  * [new tag]           ubuntu16/20210131.1     -> ubuntu16/20210131.1
2021-12-03T08:02:23.2169353Z  * [new tag]           ubuntu16/20210208.0     -> ubuntu16/20210208.0
2021-12-03T08:02:23.2169969Z  * [new tag]           ubuntu16/20210214.1     -> ubuntu16/20210214.1
2021-12-03T08:02:23.2170675Z  * [new tag]           ubuntu16/20210216.1     -> ubuntu16/20210216.1
2021-12-03T08:02:23.2171298Z  * [new tag]           ubuntu16/20210219.1     -> ubuntu16/20210219.1
2021-12-03T08:02:23.2171916Z  * [new tag]           ubuntu16/20210302.0     -> ubuntu16/20210302.0
2021-12-03T08:02:23.2172517Z  * [new tag]           ubuntu16/20210309.1     -> ubuntu16/20210309.1
2021-12-03T08:02:23.2173136Z  * [new tag]           ubuntu16/20210317.1     -> ubuntu16/20210317.1
2021-12-03T08:02:23.2173746Z  * [new tag]           ubuntu16/20210318.0     -> ubuntu16/20210318.0
2021-12-03T08:02:23.2174362Z  * [new tag]           ubuntu16/20210327.1     -> ubuntu16/20210327.1
2021-12-03T08:02:23.2174976Z  * [new tag]           ubuntu16/20210405.1     -> ubuntu16/20210405.1
2021-12-03T08:02:23.2175582Z  * [new tag]           ubuntu16/20210412.1     -> ubuntu16/20210412.1
2021-12-03T08:02:23.2176202Z  * [new tag]           ubuntu16/20210419.1     -> ubuntu16/20210419.1
2021-12-03T08:02:23.2176814Z  * [new tag]           ubuntu16/20210425.1     -> ubuntu16/20210425.1
2021-12-03T08:02:23.2177432Z  * [new tag]           ubuntu16/20210504.1     -> ubuntu16/20210504.1
2021-12-03T08:02:23.2178046Z  * [new tag]           ubuntu16/20210510.0     -> ubuntu16/20210510.0
2021-12-03T08:02:23.2178650Z  * [new tag]           ubuntu16/20210517.1     -> ubuntu16/20210517.1
2021-12-03T08:02:23.2179268Z  * [new tag]           ubuntu16/20210524.1     -> ubuntu16/20210524.1
2021-12-03T08:02:23.2179872Z  * [new tag]           ubuntu16/20210531.0     -> ubuntu16/20210531.0
2021-12-03T08:02:23.2180483Z  * [new tag]           ubuntu18/20200102.1     -> ubuntu18/20200102.1
2021-12-03T08:02:23.2181098Z  * [new tag]           ubuntu18/20200113.1     -> ubuntu18/20200113.1
2021-12-03T08:02:23.2181698Z  * [new tag]           ubuntu18/20200119.1     -> ubuntu18/20200119.1
2021-12-03T08:02:23.2182321Z  * [new tag]           ubuntu18/20200130.1     -> ubuntu18/20200130.1
2021-12-03T08:02:23.2182929Z  * [new tag]           ubuntu18/20200211.1     -> ubuntu18/20200211.1
2021-12-03T08:02:23.2183557Z  * [new tag]           ubuntu18/20200217.1     -> ubuntu18/20200217.1
2021-12-03T08:02:23.2184166Z  * [new tag]           ubuntu18/20200225.0     -> ubuntu18/20200225.0
2021-12-03T08:02:23.2184774Z  * [new tag]           ubuntu18/20200301.1     -> ubuntu18/20200301.1
2021-12-03T08:02:23.2185396Z  * [new tag]           ubuntu18/20200308.0     -> ubuntu18/20200308.0
2021-12-03T08:02:23.2186005Z  * [new tag]           ubuntu18/20200316.1     -> ubuntu18/20200316.1
2021-12-03T08:02:23.2186616Z  * [new tag]           ubuntu18/20200323.1     -> ubuntu18/20200323.1
2021-12-03T08:02:23.2190257Z  * [new tag]           ubuntu18/20200330.1     -> ubuntu18/20200330.1
2021-12-03T08:02:23.2190881Z  * [new tag]           ubuntu18/20200406.2     -> ubuntu18/20200406.2
2021-12-03T08:02:23.2191501Z  * [new tag]           ubuntu18/20200415.3     -> ubuntu18/20200415.3
2021-12-03T08:02:23.2192116Z  * [new tag]           ubuntu18/20200426.1     -> ubuntu18/20200426.1
2021-12-03T08:02:23.2192739Z  * [new tag]           ubuntu18/20200428.2     -> ubuntu18/20200428.2
2021-12-03T08:02:23.2193371Z  * [new tag]           ubuntu18/20200430.1     -> ubuntu18/20200430.1
2021-12-03T08:02:23.2194093Z  * [new tag]           ubuntu18/20200512.2     -> ubuntu18/20200512.2
2021-12-03T08:02:23.2194723Z  * [new tag]           ubuntu18/20200518.1     -> ubuntu18/20200518.1
2021-12-03T08:02:23.2195334Z  * [new tag]           ubuntu18/20200525.2     -> ubuntu18/20200525.2
2021-12-03T08:02:23.2195964Z  * [new tag]           ubuntu18/20200531.1     -> ubuntu18/20200531.1
2021-12-03T08:02:23.2196581Z  * [new tag]           ubuntu18/20200604.1     -> ubuntu18/20200604.1
2021-12-03T08:02:23.2197187Z  * [new tag]           ubuntu18/20200614.1     -> ubuntu18/20200614.1
2021-12-03T08:02:23.2197817Z  * [new tag]           ubuntu18/20200621.1     -> ubuntu18/20200621.1
2021-12-03T08:02:23.2198426Z  * [new tag]           ubuntu18/20200625.0     -> ubuntu18/20200625.0
2021-12-03T08:02:23.2199140Z  * [new tag]           ubuntu18/20200705.1     -> ubuntu18/20200705.1
2021-12-03T08:02:23.2199754Z  * [new tag]           ubuntu18/20200709.0     -> ubuntu18/20200709.0
2021-12-03T08:02:23.2200357Z  * [new tag]           ubuntu18/20200717.1     -> ubuntu18/20200717.1
2021-12-03T08:02:23.2200982Z  * [new tag]           ubuntu18/20200726.1     -> ubuntu18/20200726.1
2021-12-03T08:02:23.2201595Z  * [new tag]           ubuntu18/20200802.1     -> ubuntu18/20200802.1
2021-12-03T08:02:23.2202212Z  * [new tag]           ubuntu18/20200806.0     -> ubuntu18/20200806.0
2021-12-03T08:02:23.2202825Z  * [new tag]           ubuntu18/20200817.1     -> ubuntu18/20200817.1
2021-12-03T08:02:23.2203427Z  * [new tag]           ubuntu18/20200825.1     -> ubuntu18/20200825.1
2021-12-03T08:02:23.2204049Z  * [new tag]           ubuntu18/20200901.1     -> ubuntu18/20200901.1
2021-12-03T08:02:23.2204662Z  * [new tag]           ubuntu18/20200908.1     -> ubuntu18/20200908.1
2021-12-03T08:02:23.2205268Z  * [new tag]           ubuntu18/20200914.1     -> ubuntu18/20200914.1
2021-12-03T08:02:23.2205884Z  * [new tag]           ubuntu18/20200920.1     -> ubuntu18/20200920.1
2021-12-03T08:02:23.2206487Z  * [new tag]           ubuntu18/20201004.1     -> ubuntu18/20201004.1
2021-12-03T08:02:23.2207111Z  * [new tag]           ubuntu18/20201012.1     -> ubuntu18/20201012.1
2021-12-03T08:02:23.2207717Z  * [new tag]           ubuntu18/20201015.1     -> ubuntu18/20201015.1
2021-12-03T08:02:23.2208341Z  * [new tag]           ubuntu18/20201026.1     -> ubuntu18/20201026.1
2021-12-03T08:02:23.2208958Z  * [new tag]           ubuntu18/20201108.1     -> ubuntu18/20201108.1
2021-12-03T08:02:23.2209561Z  * [new tag]           ubuntu18/20201115.1     -> ubuntu18/20201115.1
2021-12-03T08:02:23.2210177Z  * [new tag]           ubuntu18/20201129.1     -> ubuntu18/20201129.1
2021-12-03T08:02:23.2210788Z  * [new tag]           ubuntu18/20201210.0     -> ubuntu18/20201210.0
2021-12-03T08:02:23.2211399Z  * [new tag]           ubuntu18/20210111.1     -> ubuntu18/20210111.1
2021-12-03T08:02:23.2212014Z  * [new tag]           ubuntu18/20210117.1     -> ubuntu18/20210117.1
2021-12-03T08:02:23.2212621Z  * [new tag]           ubuntu18/20210123.1     -> ubuntu18/20210123.1
2021-12-03T08:02:23.2213243Z  * [new tag]           ubuntu18/20210131.1     -> ubuntu18/20210131.1
2021-12-03T08:02:23.2213845Z  * [new tag]           ubuntu18/20210208.0     -> ubuntu18/20210208.0
2021-12-03T08:02:23.2214472Z  * [new tag]           ubuntu18/20210211.1     -> ubuntu18/20210211.1
2021-12-03T08:02:23.2215086Z  * [new tag]           ubuntu18/20210219.1     -> ubuntu18/20210219.1
2021-12-03T08:02:23.2215685Z  * [new tag]           ubuntu18/20210302.0     -> ubuntu18/20210302.0
2021-12-03T08:02:23.2216303Z  * [new tag]           ubuntu18/20210309.1     -> ubuntu18/20210309.1
2021-12-03T08:02:23.2216908Z  * [new tag]           ubuntu18/20210315.1     -> ubuntu18/20210315.1
2021-12-03T08:02:23.2217527Z  * [new tag]           ubuntu18/20210318.0     -> ubuntu18/20210318.0
2021-12-03T08:02:23.2218149Z  * [new tag]           ubuntu18/20210330.1     -> ubuntu18/20210330.1
2021-12-03T08:02:23.2218760Z  * [new tag]           ubuntu18/20210405.1     -> ubuntu18/20210405.1
2021-12-03T08:02:23.2219373Z  * [new tag]           ubuntu18/20210412.1     -> ubuntu18/20210412.1
2021-12-03T08:02:23.2220023Z  * [new tag]           ubuntu18/20210419.1     -> ubuntu18/20210419.1
2021-12-03T08:02:23.2220654Z  * [new tag]           ubuntu18/20210425.1     -> ubuntu18/20210425.1
2021-12-03T08:02:23.2221268Z  * [new tag]           ubuntu18/20210504.1     -> ubuntu18/20210504.1
2021-12-03T08:02:23.2221872Z  * [new tag]           ubuntu18/20210510.0     -> ubuntu18/20210510.0
2021-12-03T08:02:23.2222493Z  * [new tag]           ubuntu18/20210517.1     -> ubuntu18/20210517.1
2021-12-03T08:02:23.2223100Z  * [new tag]           ubuntu18/20210524.1     -> ubuntu18/20210524.1
2021-12-03T08:02:23.2223720Z  * [new tag]           ubuntu18/20210531.0     -> ubuntu18/20210531.0
2021-12-03T08:02:23.2224334Z  * [new tag]           ubuntu18/20210606.1     -> ubuntu18/20210606.1
2021-12-03T08:02:23.2225015Z  * [new tag]           ubuntu18/20210614.1     -> ubuntu18/20210614.1
2021-12-03T08:02:23.2225634Z  * [new tag]           ubuntu18/20210621.1     -> ubuntu18/20210621.1
2021-12-03T08:02:23.2226243Z  * [new tag]           ubuntu18/20210628.1     -> ubuntu18/20210628.1
2021-12-03T08:02:23.2227124Z  * [new tag]           ubuntu18/20210712.0     -> ubuntu18/20210712.0
2021-12-03T08:02:23.2227765Z  * [new tag]           ubuntu18/20210718.1     -> ubuntu18/20210718.1
2021-12-03T08:02:23.2228371Z  * [new tag]           ubuntu18/20210726.1     -> ubuntu18/20210726.1
2021-12-03T08:02:23.2228993Z  * [new tag]           ubuntu18/20210803.5     -> ubuntu18/20210803.5
2021-12-03T08:02:23.2229595Z  * [new tag]           ubuntu18/20210810.1     -> ubuntu18/20210810.1
2021-12-03T08:02:23.2230212Z  * [new tag]           ubuntu18/20210816.1     -> ubuntu18/20210816.1
2021-12-03T08:02:23.2230827Z  * [new tag]           ubuntu18/20210831.9     -> ubuntu18/20210831.9
2021-12-03T08:02:23.2231441Z  * [new tag]           ubuntu18/20210906.1     -> ubuntu18/20210906.1
2021-12-03T08:02:23.2232057Z  * [new tag]           ubuntu18/20210913.1     -> ubuntu18/20210913.1
2021-12-03T08:02:23.2232663Z  * [new tag]           ubuntu18/20210919.1     -> ubuntu18/20210919.1
2021-12-03T08:02:23.2233287Z  * [new tag]           ubuntu18/20210929.1     -> ubuntu18/20210929.1
2021-12-03T08:02:23.2233902Z  * [new tag]           ubuntu18/20211004.1     -> ubuntu18/20211004.1
2021-12-03T08:02:23.2234506Z  * [new tag]           ubuntu18/20211011.1     -> ubuntu18/20211011.1
2021-12-03T08:02:23.2235125Z  * [new tag]           ubuntu18/20211017.0     -> ubuntu18/20211017.0
2021-12-03T08:02:23.2235730Z  * [new tag]           ubuntu18/20211101.1     -> ubuntu18/20211101.1
2021-12-03T08:02:23.2236350Z  * [new tag]           ubuntu18/20211108.1     -> ubuntu18/20211108.1
2021-12-03T08:02:23.2236968Z  * [new tag]           ubuntu18/20211114.1     -> ubuntu18/20211114.1
2021-12-03T08:02:23.2237580Z  * [new tag]           ubuntu18/20211122.1     -> ubuntu18/20211122.1
2021-12-03T08:02:23.2238197Z  * [new tag]           ubuntu18/20211129.1     -> ubuntu18/20211129.1
2021-12-03T08:02:23.2238803Z  * [new tag]           ubuntu20/20200531.1     -> ubuntu20/20200531.1
2021-12-03T08:02:23.2239423Z  * [new tag]           ubuntu20/20200604.0     -> ubuntu20/20200604.0
2021-12-03T08:02:23.2240044Z  * [new tag]           ubuntu20/20200607.1     -> ubuntu20/20200607.1
2021-12-03T08:02:23.2240649Z  * [new tag]           ubuntu20/20200614.1     -> ubuntu20/20200614.1
2021-12-03T08:02:23.2241263Z  * [new tag]           ubuntu20/20200621.1     -> ubuntu20/20200621.1
2021-12-03T08:02:23.2241863Z  * [new tag]           ubuntu20/20200625.0     -> ubuntu20/20200625.0
2021-12-03T08:02:23.2242490Z  * [new tag]           ubuntu20/20200705.1     -> ubuntu20/20200705.1
2021-12-03T08:02:23.2243102Z  * [new tag]           ubuntu20/20200709.0     -> ubuntu20/20200709.0
2021-12-03T08:02:23.2243713Z  * [new tag]           ubuntu20/20200717.1     -> ubuntu20/20200717.1
2021-12-03T08:02:23.2244335Z  * [new tag]           ubuntu20/20200723.1     -> ubuntu20/20200723.1
2021-12-03T08:02:23.2244939Z  * [new tag]           ubuntu20/20200802.1     -> ubuntu20/20200802.1
2021-12-03T08:02:23.2245629Z  * [new tag]           ubuntu20/20200806.0     -> ubuntu20/20200806.0
2021-12-03T08:02:23.2246298Z  * [new tag]           ubuntu20/20200817.1     -> ubuntu20/20200817.1
2021-12-03T08:02:23.2246908Z  * [new tag]           ubuntu20/20200820.1     -> ubuntu20/20200820.1
2021-12-03T08:02:23.2247531Z  * [new tag]           ubuntu20/20200825.1     -> ubuntu20/20200825.1
2021-12-03T08:02:23.2248149Z  * [new tag]           ubuntu20/20200901.1     -> ubuntu20/20200901.1
2021-12-03T08:02:23.2248770Z  * [new tag]           ubuntu20/20200908.1     -> ubuntu20/20200908.1
2021-12-03T08:02:23.2249398Z  * [new tag]           ubuntu20/20200914.1     -> ubuntu20/20200914.1
2021-12-03T08:02:23.2250008Z  * [new tag]           ubuntu20/20200920.1     -> ubuntu20/20200920.1
2021-12-03T08:02:23.2250704Z  * [new tag]           ubuntu20/20201004.1     -> ubuntu20/20201004.1
2021-12-03T08:02:23.2251310Z  * [new tag]           ubuntu20/20201012.1     -> ubuntu20/20201012.1
2021-12-03T08:02:23.2251929Z  * [new tag]           ubuntu20/20201015.1     -> ubuntu20/20201015.1
2021-12-03T08:02:23.2252552Z  * [new tag]           ubuntu20/20201026.1     -> ubuntu20/20201026.1
2021-12-03T08:02:23.2253157Z  * [new tag]           ubuntu20/20201108.1     -> ubuntu20/20201108.1
2021-12-03T08:02:23.2253768Z  * [new tag]           ubuntu20/20201116.1     -> ubuntu20/20201116.1
2021-12-03T08:02:23.2254379Z  * [new tag]           ubuntu20/20201130.1     -> ubuntu20/20201130.1
2021-12-03T08:02:23.2254996Z  * [new tag]           ubuntu20/20201210.0     -> ubuntu20/20201210.0
2021-12-03T08:02:23.2255611Z  * [new tag]           ubuntu20/20210111.1     -> ubuntu20/20210111.1
2021-12-03T08:02:23.2256217Z  * [new tag]           ubuntu20/20210117.1     -> ubuntu20/20210117.1
2021-12-03T08:02:23.2256838Z  * [new tag]           ubuntu20/20210123.1     -> ubuntu20/20210123.1
2021-12-03T08:02:23.2257450Z  * [new tag]           ubuntu20/20210131.1     -> ubuntu20/20210131.1
2021-12-03T08:02:23.2258054Z  * [new tag]           ubuntu20/20210208.0     -> ubuntu20/20210208.0
2021-12-03T08:02:23.2258657Z  * [new tag]           ubuntu20/20210215.1     -> ubuntu20/20210215.1
2021-12-03T08:02:23.2259252Z  * [new tag]           ubuntu20/20210216.1     -> ubuntu20/20210216.1
2021-12-03T08:02:23.2259866Z  * [new tag]           ubuntu20/20210219.1     -> ubuntu20/20210219.1
2021-12-03T08:02:23.2260470Z  * [new tag]           ubuntu20/20210302.0     -> ubuntu20/20210302.0
2021-12-03T08:02:23.2261078Z  * [new tag]           ubuntu20/20210309.1     -> ubuntu20/20210309.1
2021-12-03T08:02:23.2261682Z  * [new tag]           ubuntu20/20210315.1     -> ubuntu20/20210315.1
2021-12-03T08:02:23.2262281Z  * [new tag]           ubuntu20/20210318.0     -> ubuntu20/20210318.0
2021-12-03T08:02:23.2262896Z  * [new tag]           ubuntu20/20210330.1     -> ubuntu20/20210330.1
2021-12-03T08:02:23.2263501Z  * [new tag]           ubuntu20/20210405.1     -> ubuntu20/20210405.1
2021-12-03T08:02:23.2264115Z  * [new tag]           ubuntu20/20210412.1     -> ubuntu20/20210412.1
2021-12-03T08:02:23.2264726Z  * [new tag]           ubuntu20/20210419.1     -> ubuntu20/20210419.1
2021-12-03T08:02:23.2265318Z  * [new tag]           ubuntu20/20210425.1     -> ubuntu20/20210425.1
2021-12-03T08:02:23.2265929Z  * [new tag]           ubuntu20/20210504.1     -> ubuntu20/20210504.1
2021-12-03T08:02:23.2266523Z  * [new tag]           ubuntu20/20210510.0     -> ubuntu20/20210510.0
2021-12-03T08:02:23.2267270Z  * [new tag]           ubuntu20/20210517.1     -> ubuntu20/20210517.1
2021-12-03T08:02:23.2267890Z  * [new tag]           ubuntu20/20210524.1     -> ubuntu20/20210524.1
2021-12-03T08:02:23.2268501Z  * [new tag]           ubuntu20/20210531.0     -> ubuntu20/20210531.0
2021-12-03T08:02:23.2269114Z  * [new tag]           ubuntu20/20210606.1     -> ubuntu20/20210606.1
2021-12-03T08:02:23.2269720Z  * [new tag]           ubuntu20/20210614.1     -> ubuntu20/20210614.1
2021-12-03T08:02:23.2270329Z  * [new tag]           ubuntu20/20210621.1     -> ubuntu20/20210621.1
2021-12-03T08:02:23.2270941Z  * [new tag]           ubuntu20/20210628.1     -> ubuntu20/20210628.1
2021-12-03T08:02:23.2271742Z  * [new tag]           ubuntu20/20210712.0     -> ubuntu20/20210712.0
2021-12-03T08:02:23.2272363Z  * [new tag]           ubuntu20/20210718.1     -> ubuntu20/20210718.1
2021-12-03T08:02:23.2272983Z  * [new tag]           ubuntu20/20210726.1     -> ubuntu20/20210726.1
2021-12-03T08:02:23.2273609Z  * [new tag]           ubuntu20/20210803.0     -> ubuntu20/20210803.0
2021-12-03T08:02:23.2274210Z  * [new tag]           ubuntu20/20210810.1     -> ubuntu20/20210810.1
2021-12-03T08:02:23.2274830Z  * [new tag]           ubuntu20/20210816.1     -> ubuntu20/20210816.1
2021-12-03T08:02:23.2275694Z  * [new tag]           ubuntu20/20210831.9     -> ubuntu20/20210831.9
2021-12-03T08:02:23.2276409Z  * [new tag]           ubuntu20/20210906.1     -> ubuntu20/20210906.1
2021-12-03T08:02:23.2277037Z  * [new tag]           ubuntu20/20210913.1     -> ubuntu20/20210913.1
2021-12-03T08:02:23.2277642Z  * [new tag]           ubuntu20/20210919.1     -> ubuntu20/20210919.1
2021-12-03T08:02:23.2278266Z  * [new tag]           ubuntu20/20210929.1     -> ubuntu20/20210929.1
2021-12-03T08:02:23.2278879Z  * [new tag]           ubuntu20/20211004.1     -> ubuntu20/20211004.1
2021-12-03T08:02:23.2279501Z  * [new tag]           ubuntu20/20211011.1     -> ubuntu20/20211011.1
2021-12-03T08:02:23.2280112Z  * [new tag]           ubuntu20/20211017.0     -> ubuntu20/20211017.0
2021-12-03T08:02:23.2280718Z  * [new tag]           ubuntu20/20211101.1     -> ubuntu20/20211101.1
2021-12-03T08:02:23.2281333Z  * [new tag]           ubuntu20/20211108.1     -> ubuntu20/20211108.1
2021-12-03T08:02:23.2281943Z  * [new tag]           ubuntu20/20211114.1     -> ubuntu20/20211114.1
2021-12-03T08:02:23.2282576Z  * [new tag]           ubuntu20/20211122.1     -> ubuntu20/20211122.1
2021-12-03T08:02:23.2283195Z  * [new tag]           ubuntu20/20211129.1     -> ubuntu20/20211129.1
2021-12-03T08:02:23.2283789Z  * [new tag]           win16/20200113.1        -> win16/20200113.1
2021-12-03T08:02:23.2284378Z  * [new tag]           win16/20200120.1        -> win16/20200120.1
2021-12-03T08:02:23.2284946Z  * [new tag]           win16/20200130.1        -> win16/20200130.1
2021-12-03T08:02:23.2285522Z  * [new tag]           win16/20200211.1        -> win16/20200211.1
2021-12-03T08:02:23.2286081Z  * [new tag]           win16/20200217.1        -> win16/20200217.1
2021-12-03T08:02:23.2286650Z  * [new tag]           win16/20200225.0        -> win16/20200225.0
2021-12-03T08:02:23.2287223Z  * [new tag]           win16/20200301.1        -> win16/20200301.1
2021-12-03T08:02:23.2287780Z  * [new tag]           win16/20200308.0        -> win16/20200308.0
2021-12-03T08:02:23.2288347Z  * [new tag]           win16/20200316.1        -> win16/20200316.1
2021-12-03T08:02:23.2288903Z  * [new tag]           win16/20200323.1        -> win16/20200323.1
2021-12-03T08:02:23.2289457Z  * [new tag]           win16/20200330.1        -> win16/20200330.1
2021-12-03T08:02:23.2290020Z  * [new tag]           win16/20200331.1        -> win16/20200331.1
2021-12-03T08:02:23.2290573Z  * [new tag]           win16/20200406.2        -> win16/20200406.2
2021-12-03T08:02:23.2291132Z  * [new tag]           win16/20200416.1        -> win16/20200416.1
2021-12-03T08:02:23.2291690Z  * [new tag]           win16/20200426.1        -> win16/20200426.1
2021-12-03T08:02:23.2292244Z  * [new tag]           win16/20200505.1        -> win16/20200505.1
2021-12-03T08:02:23.2292811Z  * [new tag]           win16/20200512.1        -> win16/20200512.1
2021-12-03T08:02:23.2293356Z  * [new tag]           win16/20200517.1        -> win16/20200517.1
2021-12-03T08:02:23.2315927Z  * [new tag]           win16/20200524.1        -> win16/20200524.1
2021-12-03T08:02:23.2316638Z  * [new tag]           win16/20200531.1        -> win16/20200531.1
2021-12-03T08:02:23.2317241Z  * [new tag]           win16/20200604.1        -> win16/20200604.1
2021-12-03T08:02:23.2317822Z  * [new tag]           win16/20200614.1        -> win16/20200614.1
2021-12-03T08:02:23.2318377Z  * [new tag]           win16/20200621.1        -> win16/20200621.1
2021-12-03T08:02:23.2319108Z  * [new tag]           win16/20200628.0        -> win16/20200628.0
2021-12-03T08:02:23.2320464Z  * [new tag]           win16/20200630.1        -> win16/20200630.1
2021-12-03T08:02:23.2321032Z  * [new tag]           win16/20200706.1        -> win16/20200706.1
2021-12-03T08:02:23.2321601Z  * [new tag]           win16/20200713.1        -> win16/20200713.1
2021-12-03T08:02:23.2336890Z  * [new tag]           win16/20200720.1        -> win16/20200720.1
2021-12-03T08:02:23.2337567Z  * [new tag]           win16/20200726.1        -> win16/20200726.1
2021-12-03T08:02:23.2338201Z  * [new tag]           win16/20200802.1        -> win16/20200802.1
2021-12-03T08:02:23.2338823Z  * [new tag]           win16/20200811.0        -> win16/20200811.0
2021-12-03T08:02:23.2339634Z  * [new tag]           win16/20200820.1        -> win16/20200820.1
2021-12-03T08:02:23.2340253Z  * [new tag]           win16/20200827.1        -> win16/20200827.1
2021-12-03T08:02:23.2340833Z  * [new tag]           win16/20200913.0        -> win16/20200913.0
2021-12-03T08:02:23.2341394Z  * [new tag]           win16/20200920.1        -> win16/20200920.1
2021-12-03T08:02:23.2341958Z  * [new tag]           win16/20201012.1        -> win16/20201012.1
2021-12-03T08:02:23.2342530Z  * [new tag]           win16/20201020.1        -> win16/20201020.1
2021-12-03T08:02:23.2343084Z  * [new tag]           win16/20201101.2        -> win16/20201101.2
2021-12-03T08:02:23.2343655Z  * [new tag]           win16/20201108.1        -> win16/20201108.1
2021-12-03T08:02:23.2344208Z  * [new tag]           win16/20201116.1        -> win16/20201116.1
2021-12-03T08:02:23.2348536Z  * [new tag]           win16/20201202.1        -> win16/20201202.1
2021-12-03T08:02:23.2349220Z  * [new tag]           win16/20201210.0        -> win16/20201210.0
2021-12-03T08:02:23.2349787Z  * [new tag]           win16/20210110.1        -> win16/20210110.1
2021-12-03T08:02:23.2350361Z  * [new tag]           win16/20210118.1        -> win16/20210118.1
2021-12-03T08:02:23.2350932Z  * [new tag]           win16/20210202.1        -> win16/20210202.1
2021-12-03T08:02:23.2351495Z  * [new tag]           win16/20210209.1        -> win16/20210209.1
2021-12-03T08:02:23.2352054Z  * [new tag]           win16/20210219.1        -> win16/20210219.1
2021-12-03T08:02:23.2352599Z  * [new tag]           win16/20210309.0        -> win16/20210309.0
2021-12-03T08:02:23.2353161Z  * [new tag]           win16/20210329.1        -> win16/20210329.1
2021-12-03T08:02:23.2353723Z  * [new tag]           win16/20210404.2        -> win16/20210404.2
2021-12-03T08:02:23.2354282Z  * [new tag]           win16/20210411.1        -> win16/20210411.1
2021-12-03T08:02:23.2354849Z  * [new tag]           win16/20210419.1        -> win16/20210419.1
2021-12-03T08:02:23.2355409Z  * [new tag]           win16/20210425.1        -> win16/20210425.1
2021-12-03T08:02:23.2355975Z  * [new tag]           win16/20210509.1        -> win16/20210509.1
2021-12-03T08:02:23.2356523Z  * [new tag]           win16/20210516.0        -> win16/20210516.0
2021-12-03T08:02:23.2357085Z  * [new tag]           win16/20210525.0        -> win16/20210525.0
2021-12-03T08:02:23.2357653Z  * [new tag]           win16/20210531.1        -> win16/20210531.1
2021-12-03T08:02:23.2358208Z  * [new tag]           win16/20210609.1        -> win16/20210609.1
2021-12-03T08:02:23.2358771Z  * [new tag]           win16/20210614.1        -> win16/20210614.1
2021-12-03T08:02:23.2359323Z  * [new tag]           win16/20210620.1        -> win16/20210620.1
2021-12-03T08:02:23.2359889Z  * [new tag]           win16/20210628.1        -> win16/20210628.1
2021-12-03T08:02:23.2360447Z  * [new tag]           win16/20210711.1        -> win16/20210711.1
2021-12-03T08:02:23.2361003Z  * [new tag]           win16/20210719.0        -> win16/20210719.0
2021-12-03T08:02:23.2361563Z  * [new tag]           win16/20210725.1        -> win16/20210725.1
2021-12-03T08:02:23.2362109Z  * [new tag]           win16/20210802.1        -> win16/20210802.1
2021-12-03T08:02:23.2362800Z  * [new tag]           win16/20210810.1        -> win16/20210810.1
2021-12-03T08:02:23.2363359Z  * [new tag]           win16/20210815.1        -> win16/20210815.1
2021-12-03T08:02:23.2363922Z  * [new tag]           win16/20210901.3        -> win16/20210901.3
2021-12-03T08:02:23.2364486Z  * [new tag]           win16/20210907.1        -> win16/20210907.1
2021-12-03T08:02:23.2365034Z  * [new tag]           win16/20210914.2        -> win16/20210914.2
2021-12-03T08:02:23.2365593Z  * [new tag]           win16/20210919.1        -> win16/20210919.1
2021-12-03T08:02:23.2366142Z  * [new tag]           win16/20210927.1        -> win16/20210927.1
2021-12-03T08:02:23.2366705Z  * [new tag]           win16/20211003.1        -> win16/20211003.1
2021-12-03T08:02:23.2367350Z  * [new tag]           win16/20211011.0        -> win16/20211011.0
2021-12-03T08:02:23.2367903Z  * [new tag]           win16/20211018.0        -> win16/20211018.0
2021-12-03T08:02:23.2368465Z  * [new tag]           win16/20211102.4        -> win16/20211102.4
2021-12-03T08:02:23.2369025Z  * [new tag]           win16/20211109.0        -> win16/20211109.0
2021-12-03T08:02:23.2369590Z  * [new tag]           win16/20211115.1        -> win16/20211115.1
2021-12-03T08:02:23.2370157Z  * [new tag]           win16/20211122.1        -> win16/20211122.1
2021-12-03T08:02:23.2370711Z  * [new tag]           win16/20211229.2        -> win16/20211229.2
2021-12-03T08:02:23.2371264Z  * [new tag]           win19/20200102.1        -> win19/20200102.1
2021-12-03T08:02:23.2371817Z  * [new tag]           win19/20200113.1        -> win19/20200113.1
2021-12-03T08:02:23.2372370Z  * [new tag]           win19/20200116.1        -> win19/20200116.1
2021-12-03T08:02:23.2372938Z  * [new tag]           win19/20200203.0        -> win19/20200203.0
2021-12-03T08:02:23.2373494Z  * [new tag]           win19/20200212.1        -> win19/20200212.1
2021-12-03T08:02:23.2374052Z  * [new tag]           win19/20200225.0        -> win19/20200225.0
2021-12-03T08:02:23.2374602Z  * [new tag]           win19/20200301.1        -> win19/20200301.1
2021-12-03T08:02:23.2375165Z  * [new tag]           win19/20200308.0        -> win19/20200308.0
2021-12-03T08:02:23.2375728Z  * [new tag]           win19/20200319.1        -> win19/20200319.1
2021-12-03T08:02:23.2376278Z  * [new tag]           win19/20200330.1        -> win19/20200330.1
2021-12-03T08:02:23.2376831Z  * [new tag]           win19/20200331.1        -> win19/20200331.1
2021-12-03T08:02:23.2377374Z  * [new tag]           win19/20200407.1        -> win19/20200407.1
2021-12-03T08:02:23.2377923Z  * [new tag]           win19/20200416.1        -> win19/20200416.1
2021-12-03T08:02:23.2378481Z  * [new tag]           win19/20200426.1        -> win19/20200426.1
2021-12-03T08:02:23.2379029Z  * [new tag]           win19/20200430.2        -> win19/20200430.2
2021-12-03T08:02:23.2379588Z  * [new tag]           win19/20200511.1        -> win19/20200511.1
2021-12-03T08:02:23.2380130Z  * [new tag]           win19/20200517.1        -> win19/20200517.1
2021-12-03T08:02:23.2380684Z  * [new tag]           win19/20200524.1        -> win19/20200524.1
2021-12-03T08:02:23.2381246Z  * [new tag]           win19/20200531.1        -> win19/20200531.1
2021-12-03T08:02:23.2381795Z  * [new tag]           win19/20200608.1        -> win19/20200608.1
2021-12-03T08:02:23.2382341Z  * [new tag]           win19/20200621.1        -> win19/20200621.1
2021-12-03T08:02:23.2382892Z  * [new tag]           win19/20200630.0        -> win19/20200630.0
2021-12-03T08:02:23.2383442Z  * [new tag]           win19/20200706.1        -> win19/20200706.1
2021-12-03T08:02:23.2383995Z  * [new tag]           win19/20200714.1        -> win19/20200714.1
2021-12-03T08:02:23.2384540Z  * [new tag]           win19/20200720.1        -> win19/20200720.1
2021-12-03T08:02:23.2385097Z  * [new tag]           win19/20200726.1        -> win19/20200726.1
2021-12-03T08:02:23.2385634Z  * [new tag]           win19/20200802.1        -> win19/20200802.1
2021-12-03T08:02:23.2386191Z  * [new tag]           win19/20200811.0        -> win19/20200811.0
2021-12-03T08:02:23.2386937Z  * [new tag]           win19/20200820.1        -> win19/20200820.1
2021-12-03T08:02:23.2387514Z  * [new tag]           win19/20200827.1        -> win19/20200827.1
2021-12-03T08:02:23.2388081Z  * [new tag]           win19/20200920.1        -> win19/20200920.1
2021-12-03T08:02:23.2388645Z  * [new tag]           win19/20201004.1        -> win19/20201004.1
2021-12-03T08:02:23.2389203Z  * [new tag]           win19/20201011.1        -> win19/20201011.1
2021-12-03T08:02:23.2389763Z  * [new tag]           win19/20201021.0        -> win19/20201021.0
2021-12-03T08:02:23.2390314Z  * [new tag]           win19/20201108.1        -> win19/20201108.1
2021-12-03T08:02:23.2390873Z  * [new tag]           win19/20201116.1        -> win19/20201116.1
2021-12-03T08:02:23.2391510Z  * [new tag]           win19/20201202.1        -> win19/20201202.1
2021-12-03T08:02:23.2392066Z  * [new tag]           win19/20201210.0        -> win19/20201210.0
2021-12-03T08:02:23.2392620Z  * [new tag]           win19/20210110.1        -> win19/20210110.1
2021-12-03T08:02:23.2393172Z  * [new tag]           win19/20210118.1        -> win19/20210118.1
2021-12-03T08:02:23.2393735Z  * [new tag]           win19/20210121.0        -> win19/20210121.0
2021-12-03T08:02:23.2394286Z  * [new tag]           win19/20210202.1        -> win19/20210202.1
2021-12-03T08:02:23.2394844Z  * [new tag]           win19/20210211.1        -> win19/20210211.1
2021-12-03T08:02:23.2395408Z  * [new tag]           win19/20210219.1        -> win19/20210219.1
2021-12-03T08:02:23.2395949Z  * [new tag]           win19/20210309.0        -> win19/20210309.0
2021-12-03T08:02:23.2396519Z  * [new tag]           win19/20210316.1        -> win19/20210316.1
2021-12-03T08:02:23.2397074Z  * [new tag]           win19/20210330.2        -> win19/20210330.2
2021-12-03T08:02:23.2397634Z  * [new tag]           win19/20210404.2        -> win19/20210404.2
2021-12-03T08:02:23.2398192Z  * [new tag]           win19/20210411.1        -> win19/20210411.1
2021-12-03T08:02:23.2398743Z  * [new tag]           win19/20210419.1        -> win19/20210419.1
2021-12-03T08:02:23.2399297Z  * [new tag]           win19/20210425.1        -> win19/20210425.1
2021-12-03T08:02:23.2399839Z  * [new tag]           win19/20210509.1        -> win19/20210509.1
2021-12-03T08:02:23.2400405Z  * [new tag]           win19/20210516.0        -> win19/20210516.0
2021-12-03T08:02:23.2400960Z  * [new tag]           win19/20210525.0        -> win19/20210525.0
2021-12-03T08:02:23.2401500Z  * [new tag]           win19/20210531.1        -> win19/20210531.1
2021-12-03T08:02:23.2402055Z  * [new tag]           win19/20210608.0        -> win19/20210608.0
2021-12-03T08:02:23.2402596Z  * [new tag]           win19/20210616.0        -> win19/20210616.0
2021-12-03T08:02:23.2403151Z  * [new tag]           win19/20210620.1        -> win19/20210620.1
2021-12-03T08:02:23.2403701Z  * [new tag]           win19/20210628.1        -> win19/20210628.1
2021-12-03T08:02:23.2404241Z  * [new tag]           win19/20210711.1        -> win19/20210711.1
2021-12-03T08:02:23.2404800Z  * [new tag]           win19/20210719.0        -> win19/20210719.0
2021-12-03T08:02:23.2405343Z  * [new tag]           win19/20210725.1        -> win19/20210725.1
2021-12-03T08:02:23.2405892Z  * [new tag]           win19/20210803.1        -> win19/20210803.1
2021-12-03T08:02:23.2406447Z  * [new tag]           win19/20210810.1        -> win19/20210810.1
2021-12-03T08:02:23.2406989Z  * [new tag]           win19/20210815.1        -> win19/20210815.1
2021-12-03T08:02:23.2407544Z  * [new tag]           win19/20210903.7        -> win19/20210903.7
2021-12-03T08:02:23.2408088Z  * [new tag]           win19/20210907.4        -> win19/20210907.4
2021-12-03T08:02:23.2408639Z  * [new tag]           win19/20210914.2        -> win19/20210914.2
2021-12-03T08:02:23.2409191Z  * [new tag]           win19/20210920.1        -> win19/20210920.1
2021-12-03T08:02:23.2409736Z  * [new tag]           win19/20210928.2        -> win19/20210928.2
2021-12-03T08:02:23.2410287Z  * [new tag]           win19/20211003.2        -> win19/20211003.2
2021-12-03T08:02:23.2410896Z  * [new tag]           win19/20211011.0        -> win19/20211011.0
2021-12-03T08:02:23.2411460Z  * [new tag]           win19/20211018.0        -> win19/20211018.0
2021-12-03T08:02:23.2412021Z  * [new tag]           win19/20211102.4        -> win19/20211102.4
2021-12-03T08:02:23.2412566Z  * [new tag]           win19/20211110.1        -> win19/20211110.1
2021-12-03T08:02:23.2413125Z  * [new tag]           win19/20211122.1        -> win19/20211122.1
2021-12-03T08:02:23.2413677Z  * [new tag]           win19/20211229.2        -> win19/20211229.2
2021-12-03T08:02:23.2414232Z  * [new tag]           win22/20210819.7        -> win22/20210819.7
2021-12-03T08:02:23.2414791Z  * [new tag]           win22/20210901.3        -> win22/20210901.3
2021-12-03T08:02:23.2415403Z  * [new tag]           win22/20210907.1        -> win22/20210907.1
2021-12-03T08:02:23.2415960Z  * [new tag]           win22/20210914.2        -> win22/20210914.2
2021-12-03T08:02:23.2416516Z  * [new tag]           win22/20210920.1        -> win22/20210920.1
2021-12-03T08:02:23.2417084Z  * [new tag]           win22/20210927.1        -> win22/20210927.1
2021-12-03T08:02:23.2417646Z  * [new tag]           win22/20211003.1        -> win22/20211003.1
2021-12-03T08:02:23.2418202Z  * [new tag]           win22/20211011.0        -> win22/20211011.0
2021-12-03T08:02:23.2418770Z  * [new tag]           win22/20211018.0        -> win22/20211018.0
2021-12-03T08:02:23.2419323Z  * [new tag]           win22/20211102.4        -> win22/20211102.4
2021-12-03T08:02:23.2419883Z  * [new tag]           win22/20211109.2        -> win22/20211109.2
2021-12-03T08:02:23.2420453Z  * [new tag]           win22/20211115.1        -> win22/20211115.1
2021-12-03T08:02:23.2421008Z  * [new tag]           win22/20211122.0        -> win22/20211122.0
2021-12-03T08:02:23.2421566Z  * [new tag]           win22/20211130.3        -> win22/20211130.3
2021-12-03T08:02:23.2422346Z  * [new ref]           95f279b601ca18bb6a1d17b55a8485fe042273d8 -> pull/4645/merge
2021-12-03T08:02:23.2424422Z ##[endgroup]
2021-12-03T08:02:23.2425337Z ##[group]Determining the checkout info
2021-12-03T08:02:23.2426179Z ##[endgroup]
2021-12-03T08:02:23.2427211Z ##[group]Checking out the ref
2021-12-03T08:02:23.2428015Z [command]/usr/bin/git checkout --progress --force refs/remotes/pull/4645/merge
2021-12-03T08:02:23.2625163Z Note: switching to 'refs/remotes/pull/4645/merge'.
2021-12-03T08:02:23.2625556Z 
2021-12-03T08:02:23.2626249Z You are in 'detached HEAD' state. You can look around, make experimental
2021-12-03T08:02:23.2627132Z changes and commit them, and you can discard any commits you make in this
2021-12-03T08:02:23.2627811Z state without impacting any branches by switching back to a branch.
2021-12-03T08:02:23.2628223Z 
2021-12-03T08:02:23.2628670Z If you want to create a new branch to retain commits you create, you may
2021-12-03T08:02:23.2629455Z do so (now or later) by using -c with the switch command. Example:
2021-12-03T08:02:23.2629812Z 
2021-12-03T08:02:23.2630317Z   git switch -c <new-branch-name>
2021-12-03T08:02:23.2630619Z 
2021-12-03T08:02:23.2630956Z Or undo this operation with:
2021-12-03T08:02:23.2631217Z 
2021-12-03T08:02:23.2631620Z   git switch -
2021-12-03T08:02:23.2631841Z 
2021-12-03T08:02:23.2636267Z Turn off this advice by setting config variable advice.detachedHead to false
2021-12-03T08:02:23.2636746Z 
2021-12-03T08:02:23.2637584Z HEAD is now at 95f279b6 Merge cdbc539f52a0a8ac9e4fc37e3d9dd2e28e792f14 into d12aeab69ca9c80f2d9317ea06e6087c25e66d10
2021-12-03T08:02:23.2639061Z ##[endgroup]
2021-12-03T08:02:23.2717952Z [command]/usr/bin/git log -1 --format='%H'
2021-12-03T08:02:23.2743733Z '95f279b601ca18bb6a1d17b55a8485fe042273d8'
2021-12-03T08:02:23.2888811Z ##[group]Run github/super-linter/slim@v4
2021-12-03T08:02:23.2889243Z env:
2021-12-03T08:02:23.2889610Z   VALIDATE_ALL_CODEBASE: false
2021-12-03T08:02:23.2890842Z   GITHUB_TOKEN: ***
2021-12-03T08:02:23.2891208Z   VALIDATE_JSON: true
2021-12-03T08:02:23.2891588Z   VALIDATE_MARKDOWN: true
2021-12-03T08:02:23.2891974Z   DEFAULT_BRANCH: main
2021-12-03T08:02:23.2892327Z ##[endgroup]
2021-12-03T08:02:23.2928261Z ##[command]/usr/bin/docker run --name ghcriogithubsuperlinterslimv4_6056c6 --label 905b62 --workdir /github/workspace --rm -e VALIDATE_ALL_CODEBASE -e GITHUB_TOKEN -e VALIDATE_JSON -e VALIDATE_MARKDOWN -e DEFAULT_BRANCH -e HOME -e GITHUB_JOB -e GITHUB_REF -e GITHUB_SHA -e GITHUB_REPOSITORY -e GITHUB_REPOSITORY_OWNER -e GITHUB_RUN_ID -e GITHUB_RUN_NUMBER -e GITHUB_RETENTION_DAYS -e GITHUB_RUN_ATTEMPT -e GITHUB_ACTOR -e GITHUB_WORKFLOW -e GITHUB_HEAD_REF -e GITHUB_BASE_REF -e GITHUB_EVENT_NAME -e GITHUB_SERVER_URL -e GITHUB_API_URL -e GITHUB_GRAPHQL_URL -e GITHUB_REF_NAME -e GITHUB_REF_PROTECTED -e GITHUB_REF_TYPE -e GITHUB_WORKSPACE -e GITHUB_ACTION -e GITHUB_EVENT_PATH -e GITHUB_ACTION_REPOSITORY -e GITHUB_ACTION_REF -e GITHUB_PATH -e GITHUB_ENV -e RUNNER_OS -e RUNNER_ARCH -e RUNNER_NAME -e RUNNER_TOOL_CACHE -e RUNNER_TEMP -e RUNNER_WORKSPACE -e ACTIONS_RUNTIME_URL -e ACTIONS_RUNTIME_TOKEN -e ACTIONS_CACHE_URL -e GITHUB_ACTIONS=true -e CI=true -v "/var/run/docker.sock":"/var/run/docker.sock" -v "/home/runner/work/_temp/_github_home":"/github/home" -v "/home/runner/work/_temp/_github_workflow":"/github/workflow" -v "/home/runner/work/_temp/_runner_file_commands":"/github/file_commands" -v "/home/runner/work/virtual-environments/virtual-environments":"/github/workspace" ghcr.io/github/super-linter:slim-v4
2021-12-03T08:02:24.0549051Z --------------------------------------------------------------------------------
2021-12-03T08:02:24.0549516Z 
2021-12-03T08:02:24.0549837Z                               /@@#///////@@/(@//@%/(@.@(       @@
2021-12-03T08:02:24.0550213Z                           @@//////////////////////////////#*  @@@
2021-12-03T08:02:24.0550558Z                         @////@//(///////////@@@@@///@//@/@**//@@(
2021-12-03T08:02:24.0550918Z                       @///////@///////////////@@@@    (           @,
2021-12-03T08:02:24.0551275Z                      @/(&/@////////////////////                     @
2021-12-03T08:02:24.0551620Z                     @////////////////////////@@                      @
2021-12-03T08:02:24.0552008Z                   @%////////(//////////%/////&@            @@       *,@           ______________
2021-12-03T08:02:24.0552393Z              @@@@@/@/#/////(&//////////////////                       .@         /              \
2021-12-03T08:02:24.0553007Z         *@@@@@.    .%///(//@//////////////////&.   .@@,                 @%      / Don't mind me  \
2021-12-03T08:02:24.0553646Z       @@%           .&@&&/@.@//&/////(//////////    @@@@@@@@@         .. &@    / I'm just looking \
2021-12-03T08:02:24.0554123Z     @@%               @@@@@   @&/////////////////#   @/       V  @@/ ,@@@ @   <  for some trash... |
2021-12-03T08:02:24.0554574Z @@@%                   @@@@        .%@@@@//////#@ @   @@         @     .,.     \__________________/
2021-12-03T08:02:24.0554953Z                                           @@@/@(  (@@@@% @/\      %
2021-12-03T08:02:24.0555300Z                                            @@@@(    .     .@@/\   #
2021-12-03T08:02:24.0555659Z                                              @                  %@%
2021-12-03T08:02:24.0555889Z 
2021-12-03T08:02:24.0556470Z --------------------------------------------------------------------------------
2021-12-03T08:02:24.0589559Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   ---------------------------------------------[0m
2021-12-03T08:02:24.0618865Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   --- GitHub Actions Multi Language Linter ----[0m
2021-12-03T08:02:24.0647709Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m    - Image Creation Date:[][0m
2021-12-03T08:02:24.0677536Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m    - Image Revision:[563be7dc5568017515b9e700329e9c6d3862f2b7][0m
2021-12-03T08:02:24.0706363Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m    - Image Version:[563be7dc5568017515b9e700329e9c6d3862f2b7][0m
2021-12-03T08:02:24.0736000Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   ---------------------------------------------[0m
2021-12-03T08:02:24.0764669Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   ---------------------------------------------[0m
2021-12-03T08:02:24.0793729Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   The Super-Linter source code can be found at:[0m
2021-12-03T08:02:24.0822675Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m    - https://github.com/github/super-linter[0m
2021-12-03T08:02:24.0853215Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   ---------------------------------------------[0m
2021-12-03T08:02:24.0859249Z Removing Languages from LANGUAGE_ARRAY for slim image...
2021-12-03T08:02:24.0861247Z found item:[ARM], removing Language...
2021-12-03T08:02:24.0869916Z found item:[CSHARP], removing Language...
2021-12-03T08:02:24.0877454Z found item:[ENV], removing Language...
2021-12-03T08:02:24.0886833Z found item:[POWERSHELL], removing Language...
2021-12-03T08:02:24.0894068Z found item:[RUST_2015], removing Language...
2021-12-03T08:02:24.0900906Z found item:[RUST_2018], removing Language...
2021-12-03T08:02:24.0908442Z found item:[RUST_CLIPPY], removing Language...
2021-12-03T08:02:24.0910834Z Removing Linters from LINTER_NAMES_ARRAY for slim image...
2021-12-03T08:02:24.0915625Z found item:[ARM], removing linter...
2021-12-03T08:02:24.0922910Z found item:[CSHARP], removing linter...
2021-12-03T08:02:24.0927547Z found item:[ENV], removing linter...
2021-12-03T08:02:24.0944337Z found item:[POWERSHELL], removing linter...
2021-12-03T08:02:24.0952753Z found item:[RUST_2015], removing linter...
2021-12-03T08:02:24.0957997Z found item:[RUST_2018], removing linter...
2021-12-03T08:02:24.0960986Z found item:[RUST_CLIPPY], removing linter...
2021-12-03T08:02:24.1116189Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   --------------------------------------------[0m
2021-12-03T08:02:24.1145176Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   Gathering GitHub information...[0m
2021-12-03T08:02:24.1176709Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   Successfully found:[0;37m[GITHUB_SHA][0;34m, value:[0;37m[95f279b601ca18bb6a1d17b55a8485fe042273d8][0m
2021-12-03T08:02:24.1206449Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   Successfully found:[0;37m[GITHUB_WORKSPACE][0;34m, value:[0;37m[/github/workspace][0m
2021-12-03T08:02:24.1237463Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   Successfully found:[0;37m[GITHUB_EVENT_PATH][0;34m, value:[0;37m[/github/workflow/event.json][0;34m[0m
2021-12-03T08:02:24.1884964Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   Successfully found:[0;37m[GITHUB_ORG][0;34m, value:[0;37m[actions][0m
2021-12-03T08:02:24.2220979Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   Successfully found:[0;37m[GITHUB_REPO][0;34m, value:[0;37m[virtual-environments][0m
2021-12-03T08:02:24.2249565Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   Successfully found:[0;37m[GITHUB_TOKEN][0m
2021-12-03T08:02:24.2280244Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   Successfully found:[0;37m[GITHUB_REPOSITORY][0;34m, value:[0;37m[actions/virtual-environments][0m
2021-12-03T08:02:24.2315517Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   Successfully found:[0;37m[GITHUB_RUN_ID][0;34m, value:[0;37m[1534303266][0m
2021-12-03T08:02:24.2346534Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   --------------------------------------------[0m
2021-12-03T08:02:24.2374960Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   Gathering user validation information...[0m
2021-12-03T08:02:24.2405043Z [0m2021-12-03 08:02:24 [0;34m[INFO][0m   - Only validating [new], or [edited] files in code base...[0m
2021-12-03T08:02:28.2153306Z You are not currently on a branch.
2021-12-03T08:02:28.2153880Z Please specify which branch you want to merge with.
2021-12-03T08:02:28.2154907Z See git-pull(1) for details.
2021-12-03T08:02:28.2155409Z 
2021-12-03T08:02:28.2155758Z     git pull <remote> <branch>
2021-12-03T08:02:28.2156025Z 
2021-12-03T08:02:28.3526178Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   ---------------------------------[0m
2021-12-03T08:02:28.3556691Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   ------ File list to check: ------[0m
2021-12-03T08:02:28.3589853Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   ---------------------------------[0m
2021-12-03T08:02:28.6420954Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   ----------------------------------------------[0m
2021-12-03T08:02:28.6449731Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   Successfully gathered list of files...[0m
2021-12-03T08:02:28.9172527Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   [0m
2021-12-03T08:02:28.9203693Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   ----------------------------------------------[0m
2021-12-03T08:02:28.9233606Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   ----------------------------------------------[0m
2021-12-03T08:02:28.9293638Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   Linting [JSON] files...[0m
2021-12-03T08:02:28.9327360Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   ----------------------------------------------[0m
2021-12-03T08:02:28.9359579Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   ----------------------------------------------[0m
2021-12-03T08:02:28.9544851Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   ---------------------------[0m
2021-12-03T08:02:28.9577562Z [0m2021-12-03 08:02:28 [0;34m[INFO][0m   File:[/github/workspace/images/win/toolsets/toolset-2016.json][0m
2021-12-03T08:02:30.4279664Z [0m2021-12-03 08:02:30 [0;34m[INFO][0m    - File:[0;37m[toolset-2016.json][0;34m was linted with [0;37m[eslint][0;34m successfully[0m
2021-12-03T08:02:30.4500622Z [0m2021-12-03 08:02:30 [0;34m[INFO][0m   ---------------------------[0m
2021-12-03T08:02:30.4536292Z [0m2021-12-03 08:02:30 [0;34m[INFO][0m   File:[/github/workspace/images/win/toolsets/toolset-2019.json][0m
2021-12-03T08:02:31.5012230Z [0m2021-12-03 08:02:31 [0;34m[INFO][0m    - File:[0;37m[toolset-2019.json][0;34m was linted with [0;37m[eslint][0;34m successfully[0m
2021-12-03T08:02:31.5230824Z [0m2021-12-03 08:02:31 [0;34m[INFO][0m   ---------------------------[0m
2021-12-03T08:02:31.5260581Z [0m2021-12-03 08:02:31 [0;34m[INFO][0m   File:[/github/workspace/images/win/toolsets/toolset-2022.json][0m
2021-12-03T08:02:32.5604617Z [0m2021-12-03 08:02:32 [0;34m[INFO][0m    - File:[0;37m[toolset-2022.json][0;34m was linted with [0;37m[eslint][0;34m successfully[0m
2021-12-03T08:02:32.9501279Z [0m2021-12-03 08:02:32 [0;34m[INFO][0m   ----------------------------------------------[0m
2021-12-03T08:02:32.9534722Z [0m2021-12-03 08:02:32 [0;34m[INFO][0m   ----------------------------------------------[0m
2021-12-03T08:02:32.9567986Z [0m2021-12-03 08:02:32 [0;34m[INFO][0m   The script has completed[0m
2021-12-03T08:02:32.9601809Z [0m2021-12-03 08:02:32 [0;34m[INFO][0m   ----------------------------------------------[0m
2021-12-03T08:02:32.9635994Z [0m2021-12-03 08:02:32 [0;34m[INFO][0m   ----------------------------------------------[0m
2021-12-03T08:02:33.2220368Z [0m2021-12-03 08:02:33 [0;34m[INFO][0m   ERROR! Failed to call GitHub Status API![0m
2021-12-03T08:02:33.2250919Z [0m2021-12-03 08:02:33 [0;34m[INFO][0m   ERROR:[][0m
2021-12-03T08:02:33.2315785Z [0m2021-12-03 08:02:33 [0;32m[NOTICE][0m   All file(s) linted successfully with no errors detected[0m
2021-12-03T08:02:33.2347790Z [0m2021-12-03 08:02:33 [0;34m[INFO][0m   ----------------------------------------------[0m
2021-12-03T08:02:33.3622273Z ##[group]Run ./images.CI/shebang-linter.ps1
2021-12-03T08:02:33.3622950Z [36;1m./images.CI/shebang-linter.ps1[0m
2021-12-03T08:02:33.3665332Z shell: /usr/bin/pwsh -command ". '{0}'"
2021-12-03T08:02:33.3665736Z ##[endgroup]
2021-12-03T08:02:34.1075521Z [+] './images/linux/scripts/helpers/etc-environment.sh'
2021-12-03T08:02:34.1093164Z [+] './images/linux/scripts/helpers/install.sh'
2021-12-03T08:02:34.1106077Z [+] './images/linux/scripts/helpers/invoke-tests.sh'
2021-12-03T08:02:34.1118578Z [+] './images/linux/scripts/helpers/os.sh'
2021-12-03T08:02:34.1132492Z [+] './images/linux/scripts/base/apt-mock-remove.sh'
2021-12-03T08:02:34.1144257Z [+] './images/linux/scripts/base/apt-mock.sh'
2021-12-03T08:02:34.1156324Z [+] './images/linux/scripts/base/apt.sh'
2021-12-03T08:02:34.1168252Z [+] './images/linux/scripts/base/limits.sh'
2021-12-03T08:02:34.1180129Z [+] './images/linux/scripts/base/reboot.sh'
2021-12-03T08:02:34.1192273Z [+] './images/linux/scripts/base/repos.sh'
2021-12-03T08:02:34.1208547Z [+] './images/linux/scripts/installers/aliyun-cli.sh'
2021-12-03T08:02:34.1220387Z [+] './images/linux/scripts/installers/android.sh'
2021-12-03T08:02:34.1232491Z [+] './images/linux/scripts/installers/apache.sh'
2021-12-03T08:02:34.1244354Z [+] './images/linux/scripts/installers/aws.sh'
2021-12-03T08:02:34.1256200Z [+] './images/linux/scripts/installers/azcopy.sh'
2021-12-03T08:02:34.1269181Z [+] './images/linux/scripts/installers/azure-cli.sh'
2021-12-03T08:02:34.1281132Z [+] './images/linux/scripts/installers/azure-devops-cli.sh'
2021-12-03T08:02:34.1292874Z [+] './images/linux/scripts/installers/basic.sh'
2021-12-03T08:02:34.1304572Z [+] './images/linux/scripts/installers/bazel.sh'
2021-12-03T08:02:34.1316775Z [+] './images/linux/scripts/installers/bicep.sh'
2021-12-03T08:02:34.1328347Z [+] './images/linux/scripts/installers/clang.sh'
2021-12-03T08:02:34.1340253Z [+] './images/linux/scripts/installers/cleanup.sh'
2021-12-03T08:02:34.1352631Z [+] './images/linux/scripts/installers/cmake.sh'
2021-12-03T08:02:34.1364597Z [+] './images/linux/scripts/installers/codeql-bundle.sh'
2021-12-03T08:02:34.1376944Z [+] './images/linux/scripts/installers/complete-snap-setup.sh'
2021-12-03T08:02:34.1389013Z [+] './images/linux/scripts/installers/configure-environment.sh'
2021-12-03T08:02:34.1400675Z [+] './images/linux/scripts/installers/containers.sh'
2021-12-03T08:02:34.1412665Z [+] './images/linux/scripts/installers/docker-compose.sh'
2021-12-03T08:02:34.1424493Z [+] './images/linux/scripts/installers/docker-moby.sh'
2021-12-03T08:02:34.1436883Z [+] './images/linux/scripts/installers/dotnetcore-sdk.sh'
2021-12-03T08:02:34.1448856Z [+] './images/linux/scripts/installers/dpkg-config.sh'
2021-12-03T08:02:34.1460589Z [+] './images/linux/scripts/installers/erlang.sh'
2021-12-03T08:02:34.1476342Z [+] './images/linux/scripts/installers/example.sh'
2021-12-03T08:02:34.1488338Z [+] './images/linux/scripts/installers/firefox.sh'
2021-12-03T08:02:34.1500151Z [+] './images/linux/scripts/installers/gcc.sh'
2021-12-03T08:02:34.1511281Z [+] './images/linux/scripts/installers/gfortran.sh'
2021-12-03T08:02:34.1523350Z [+] './images/linux/scripts/installers/git.sh'
2021-12-03T08:02:34.1536877Z [+] './images/linux/scripts/installers/github-cli.sh'
2021-12-03T08:02:34.1550143Z [+] './images/linux/scripts/installers/google-chrome.sh'
2021-12-03T08:02:34.1563553Z [+] './images/linux/scripts/installers/google-cloud-sdk.sh'
2021-12-03T08:02:34.1575969Z [+] './images/linux/scripts/installers/graalvm.sh'
2021-12-03T08:02:34.1588925Z [+] './images/linux/scripts/installers/haskell.sh'
2021-12-03T08:02:34.1601623Z [+] './images/linux/scripts/installers/heroku.sh'
2021-12-03T08:02:34.1615158Z [+] './images/linux/scripts/installers/hhvm.sh'
2021-12-03T08:02:34.1628351Z [+] './images/linux/scripts/installers/homebrew.sh'
2021-12-03T08:02:34.1640446Z [+] './images/linux/scripts/installers/java-tools.sh'
2021-12-03T08:02:34.1652672Z [+] './images/linux/scripts/installers/julia.sh'
2021-12-03T08:02:34.1665205Z [+] './images/linux/scripts/installers/kotlin.sh'
2021-12-03T08:02:34.1677397Z [+] './images/linux/scripts/installers/kubernetes-tools.sh'
2021-12-03T08:02:34.1689389Z [+] './images/linux/scripts/installers/leiningen.sh'
2021-12-03T08:02:34.1701361Z [+] './images/linux/scripts/installers/miniconda.sh'
2021-12-03T08:02:34.1713606Z [+] './images/linux/scripts/installers/mongodb.sh'
2021-12-03T08:02:34.1725717Z [+] './images/linux/scripts/installers/mono.sh'
2021-12-03T08:02:34.1738028Z [+] './images/linux/scripts/installers/mssql-cmd-tools.sh'
2021-12-03T08:02:34.1750244Z [+] './images/linux/scripts/installers/mysql.sh'
2021-12-03T08:02:34.1762135Z [+] './images/linux/scripts/installers/nginx.sh'
2021-12-03T08:02:34.1774032Z [+] './images/linux/scripts/installers/nodejs.sh'
2021-12-03T08:02:34.1786002Z [+] './images/linux/scripts/installers/nvm.sh'
2021-12-03T08:02:34.1798196Z [+] './images/linux/scripts/installers/oc.sh'
2021-12-03T08:02:34.1810298Z [+] './images/linux/scripts/installers/oras-cli.sh'
2021-12-03T08:02:34.1822259Z [+] './images/linux/scripts/installers/packer.sh'
2021-12-03T08:02:34.1834632Z [+] './images/linux/scripts/installers/phantomjs.sh'
2021-12-03T08:02:34.1847147Z [+] './images/linux/scripts/installers/php.sh'
2021-12-03T08:02:34.1859110Z [+] './images/linux/scripts/installers/pipx-packages.sh'
2021-12-03T08:02:34.1871531Z [+] './images/linux/scripts/installers/post-deployment.sh'
2021-12-03T08:02:34.1883587Z [+] './images/linux/scripts/installers/postgresql.sh'
2021-12-03T08:02:34.1895709Z [+] './images/linux/scripts/installers/powershellcore.sh'
2021-12-03T08:02:34.1907778Z [+] './images/linux/scripts/installers/preimagedata.sh'
2021-12-03T08:02:34.1920104Z [+] './images/linux/scripts/installers/pulumi.sh'
2021-12-03T08:02:34.2367321Z [+] './images/linux/scripts/installers/pypy.sh'
2021-12-03T08:02:34.2380592Z [+] './images/linux/scripts/installers/python.sh'
2021-12-03T08:02:34.2393601Z [+] './images/linux/scripts/installers/r.sh'
2021-12-03T08:02:34.2405976Z [+] './images/linux/scripts/installers/ruby.sh'
2021-12-03T08:02:34.2418152Z [+] './images/linux/scripts/installers/rust.sh'
2021-12-03T08:02:34.2430454Z [+] './images/linux/scripts/installers/sbt.sh'
2021-12-03T08:02:34.2442742Z [+] './images/linux/scripts/installers/selenium.sh'
2021-12-03T08:02:34.2454922Z [+] './images/linux/scripts/installers/sphinx.sh'
2021-12-03T08:02:34.2467149Z [+] './images/linux/scripts/installers/sqlpackage.sh'
2021-12-03T08:02:34.2479207Z [+] './images/linux/scripts/installers/swift.sh'
2021-12-03T08:02:34.2491545Z [+] './images/linux/scripts/installers/terraform.sh'
2021-12-03T08:02:34.2503892Z [+] './images/linux/scripts/installers/validate-disk-space.sh'
2021-12-03T08:02:34.2516291Z [+] './images/linux/scripts/installers/vcpkg.sh'
2021-12-03T08:02:34.2528504Z [+] './images/linux/scripts/installers/yq.sh'
2021-12-03T08:02:34.2584305Z [+] './images/macos/provision/utils/invoke-tests.sh'
2021-12-03T08:02:34.2595161Z [+] './images/macos/provision/utils/utils.sh'
2021-12-03T08:02:34.2606057Z [+] './images/macos/provision/utils/xamarin-utils.sh'
2021-12-03T08:02:34.2619766Z [+] './images/macos/provision/core/android-toolsets.sh'
2021-12-03T08:02:34.2630664Z [+] './images/macos/provision/core/apache.sh'
2021-12-03T08:02:34.2641438Z [+] './images/macos/provision/core/audiodevice.sh'
2021-12-03T08:02:34.2652230Z [+] './images/macos/provision/core/aws.sh'
2021-12-03T08:02:34.2662966Z [+] './images/macos/provision/core/azcopy.sh'
2021-12-03T08:02:34.2673819Z [+] './images/macos/provision/core/bicep.sh'
2021-12-03T08:02:34.2684804Z [+] './images/macos/provision/core/build-xcode-symlinks.sh'
2021-12-03T08:02:34.2695387Z [+] './images/macos/provision/core/chrome.sh'
2021-12-03T08:02:34.2706037Z [+] './images/macos/provision/core/cocoapods.sh'
2021-12-03T08:02:34.2716986Z [+] './images/macos/provision/core/commonutils.sh'
2021-12-03T08:02:34.2727592Z [+] './images/macos/provision/core/dotnet.sh'
2021-12-03T08:02:34.2738201Z [+] './images/macos/provision/core/edge.sh'
2021-12-03T08:02:34.2749131Z [+] './images/macos/provision/core/firefox.sh'
2021-12-03T08:02:34.2759920Z [+] './images/macos/provision/core/gcc.sh'
2021-12-03T08:02:34.2770467Z [+] './images/macos/provision/core/git.sh'
2021-12-03T08:02:34.2781017Z [+] './images/macos/provision/core/golang.sh'
2021-12-03T08:02:34.2791920Z [+] './images/macos/provision/core/haskell.sh'
2021-12-03T08:02:34.2802431Z [+] './images/macos/provision/core/homebrew.sh'
2021-12-03T08:02:34.2813034Z [+] './images/macos/provision/core/llvm.sh'
2021-12-03T08:02:34.2823763Z [+] './images/macos/provision/core/miniconda.sh'
2021-12-03T08:02:34.2834678Z [+] './images/macos/provision/core/mongodb.sh'
2021-12-03T08:02:34.2845141Z [+] './images/macos/provision/core/nginx.sh'
2021-12-03T08:02:34.2855836Z [+] './images/macos/provision/core/node.sh'
2021-12-03T08:02:34.2866435Z [+] './images/macos/provision/core/nvm.sh'
2021-12-03T08:02:34.2882183Z [+] './images/macos/provision/core/openjdk.sh'
2021-12-03T08:02:34.2892453Z [+] './images/macos/provision/core/openssl.sh'
2021-12-03T08:02:34.2951621Z [+] './images/macos/provision/core/php.sh'
2021-12-03T08:02:34.2966482Z [+] './images/macos/provision/core/pipx-packages.sh'
2021-12-03T08:02:34.2980924Z [+] './images/macos/provision/core/postgresql.sh'
2021-12-03T08:02:34.2989301Z [+] './images/macos/provision/core/powershell.sh'
2021-12-03T08:02:34.2999264Z [+] './images/macos/provision/core/pypy.sh'
2021-12-03T08:02:34.3009223Z [+] './images/macos/provision/core/python.sh'
2021-12-03T08:02:34.3019317Z [+] './images/macos/provision/core/reboot.sh'
2021-12-03T08:02:34.3029909Z [+] './images/macos/provision/core/ruby.sh'
2021-12-03T08:02:34.3039845Z [+] './images/macos/provision/core/rubygem.sh'
2021-12-03T08:02:34.3049593Z [+] './images/macos/provision/core/rust.sh'
2021-12-03T08:02:34.3064128Z [+] './images/macos/provision/core/safari.sh'
2021-12-03T08:02:34.3075610Z [+] './images/macos/provision/core/stack.sh'
2021-12-03T08:02:34.3085818Z [+] './images/macos/provision/core/swiftlint.sh'
2021-12-03T08:02:34.3096002Z [+] './images/macos/provision/core/vcpkg.sh'
2021-12-03T08:02:34.3107264Z [+] './images/macos/provision/core/vsmac.sh'
2021-12-03T08:02:34.3118302Z [+] './images/macos/provision/core/xamarin-android-ndk.sh'
2021-12-03T08:02:34.3128159Z [+] './images/macos/provision/core/xamarin.sh'
2021-12-03T08:02:34.3138072Z [+] './images/macos/provision/core/xcode-clt.sh'
2021-12-03T08:02:34.3148401Z [+] './images/macos/provision/core/xcode-postbuild.sh'
2021-12-03T08:02:34.3158438Z [+] './images/macos/provision/core/xcode-sims.sh'
2021-12-03T08:02:34.3170072Z [+] './images/macos/provision/bootstrap-provisioner/installNewProvisioner.sh'
2021-12-03T08:02:34.3181728Z [+] './images/macos/provision/configuration/add-network-interface-detection.sh'
2021-12-03T08:02:34.3191891Z [+] './images/macos/provision/configuration/autologin.sh'
2021-12-03T08:02:34.3201884Z [+] './images/macos/provision/configuration/configure-hostname.sh'
2021-12-03T08:02:34.3211926Z [+] './images/macos/provision/configuration/configure-machine.sh'
2021-12-03T08:02:34.3221946Z [+] './images/macos/provision/configuration/configure-ssh.sh'
2021-12-03T08:02:34.3232402Z [+] './images/macos/provision/configuration/configure-tccdb-macos11.sh'
2021-12-03T08:02:34.3242268Z [+] './images/macos/provision/configuration/disable-auto-updates.sh'
2021-12-03T08:02:34.3252053Z [+] './images/macos/provision/configuration/finalize-vm.sh'
2021-12-03T08:02:34.3261968Z [+] './images/macos/provision/configuration/max-files.sh'
2021-12-03T08:02:34.3272333Z [+] './images/macos/provision/configuration/ntpconf.sh'
2021-12-03T08:02:34.3282743Z [+] './images/macos/provision/configuration/preimagedata.sh'
2021-12-03T08:02:34.3292746Z [+] './images/macos/provision/configuration/screensaver-off.sh'
2021-12-03T08:02:34.3302525Z [+] './images/macos/provision/configuration/shell-change.sh'
2021-12-03T08:02:34.3314289Z [+] './images/macos/provision/assets/select-xamarin-sdk-v2.sh'
2021-12-03T08:02:34.3324177Z [+] './images/macos/provision/assets/select-xamarin-sdk.sh'
2021-12-03T08:02:34.4039789Z Post job cleanup.
2021-12-03T08:02:34.5277376Z [command]/usr/bin/git version
2021-12-03T08:02:34.5319999Z git version 2.34.1
2021-12-03T08:02:34.5352878Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2021-12-03T08:02:34.5384645Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2021-12-03T08:02:34.5589249Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2021-12-03T08:02:34.5606965Z http.https://github.com/.extraheader
2021-12-03T08:02:34.5650333Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2021-12-03T08:02:34.5682547Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2021-12-03T08:02:34.5942671Z Cleaning up orphan processes
