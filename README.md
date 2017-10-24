![DUB](https://img.shields.io/dub/l/vibe-d.svg?style=flat) [![Join the chat](https://img.shields.io/badge/gitter-join%20chat%20%E2%86%92-brightgreen.svg)](https://gitter.im/moz-lnmiit/Lobby)

# Pull-Request-and-Hacktoberfest
 A basic page to give hands on expirience on git-GitHub.

 ## The letters listed here is jumbled and is written backwards. Correct it and send Pull requests!!!
 thE+ fundamentalS firsT ll’you+ need to have a few things installed and .available foR ,starters ll’I assume you already have giT .installed iF you ,t’don grab a copy of the latest version for your operating .system iF re’you on ,linuX you can install it via your package manager .instead ,secondlY ll’you need to be at least partly comfortable with using the command .line noW not everyone ,is so if re’you ,not t’don .worry thiS will all be quite .straightforward nothinG too .complex ,thirdlY re’we going to create a simple repository consisting of a code file and a .README sO make sure you have a directory set aside where you can do .this ,theN with everything ,prepared s’let step through a standard set of actions ll’you commonly use on a daily .basis ,specificallY re’we going to use ,init ,clone ,add ,commit ,diff and .log therE are a number of ,other more advanced actions you can .perform buT in the ,beginning you t’won need .them initializinG a repositorY beforE you can work with ,giT you have to initialize a project ,repository setting it up so that giT will manage .it opeN up your ,terminal and in your project directory run the command git init . as shown in the screenshot .below A new hidden directory called git. will now be present in your project .directory thiS is where giT stores its database and configuration ,information so that it can track your .project cloninG a repositorY s’therE another way to access a ,repository which is .cloning similaR to checking out a repository in other ,systems running git clone will pull in a complete copy of the remote repository to your local .system noW you can work away on ,it making ,changes staging ,them committing ,them and pushing the changes .back addinG a neW filE m’I primarily a PHP ,developer so s’that what ll’I be using in the sample code for this .tutorial ,howeveR if you prefer ,pythoN ,rubY ,gO or another ,language feel free to substitute your language of .choice noW create a new ,file called ,php.index in your project ,directory and in ,it add the following :code php?< print hellO" ;"worlD afteR saving the ,file from the terminal run the command git .status thiS will show you the current status of your working .repository iT should look similar to the screenshot ,below with .index php listed as a ,new untracked .file noW s’let stage ,php.index because re’we not interested in md.README just for the .moment tO do ,that run git add .php.index noW run git status ,again and ll’you see php.index listed as a new file under changeS“ to be ”,committed and md.README left in the untrackeD“ ”files .area updatinG youR giT configuratioN noW re’you ready to commit .php.index buT before you ,do I want to show you how to configure the ,editor which giT will use when you write commit .messages thiS can be quite ,helpful especially if re’you not a regular line-command .user bY ,default giT uses the program specified in the environment variables VISUAL$ or ,EDITOR$ which on linuX systems is normally ,pico ,vi ,vim or .emacs iF these are new to ,you you might want to change it to an application re’you more familiar ,with perhaps ,notepaD ,texTediT or .gediT tO do ,that run the following command from your :terminal git config global-- .core editor your< s'app >name therE are a number of other configuration changes you can ,make such as your name and email ,address what the commit message looks like by ,default whether to use ,colors and so .on foR a complete ,list check out the git configuration section of the giT .book foR the remainder of this ,tutorial ll’I be using ,vim as s’it my editor of .choice buT t’don feel you have .to makinG the firsT commiT committinG in giT is a lot like committing in other version control ,systems such as .subversioN yoU start the ,process add a meaningful commit message to explain why the change was ,made and s’that ,it the s’file .changed sO run git .commit thiS will automatically open up your editor and display the commit template .below aS with the output of git ,status you see the state of your working ,repository which makes it easy to remember what re’you committing and what re’you .not A good commit message is composed of two :parts a short ,message less than 27 characters ,long which briefly states in( active )voice the change being ;made and a much ,longer optional ,description which is separated from the brief description by a .newline iN this ,case s’there no need to write anything too ,involved as re’we just adding the file to the .repository buT if the change you were making involved a complex ,algorithm perhaps in response to a bug filed against the ,code d’you want to give your fellow developers a good understanding of why you made the change that you .did sO add the following simple message addinG“ the core script file to the ”,repository save ,it and exit the .editor noW that the s’file ,committed run git status ,again and ll’you see that md.README is still listed as .untracked seeinG differenceS noW that ve’we got some files under version control and have looked at the basic ,commands s’let see how to review file .changes I t’didn complete the last commit for that .reason tO review changes in a ,file we use the command git .diffcommand giT ,diff similar to linuX diff and other diff ,programs compares two files and shows the changes the more recent file ,contains if .any s’leT have a look at the differences ve’we staged for .md.README tO do ,that run git diff .md.README seE something ?unexpected m’I guessing you were expecting to see the difference between the most recent version and the staged copy of the ,file not the .unstaged s’thaT a little gotcha that might catch you ,out at least at .first yoU need to bear in mind whether re’you ing’diff a staged or an unstaged .file bY ,default with no extra ,arguments git diff will diff the unstaged .changes iF you want to see staged ,changes then run git diff cached-- .md.README thaT command will display something similar to :this diff git-- .README/a
