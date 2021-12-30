# TRXToSlackExe
Parse results from a dotnet test .trx result file and post it to Slack using SlackBotMessages: https://github.com/prjseal/SlackBotMessages

This is useful if using something like "dotnet test -l:trx" to run tests in a pipeline from Azure, and you want to post the test results to Slack.
https://imgur.com/EqMqYAa

Application must be able to read the field "webhookUrl" from any json file.

Run "trxtoslack.exe {anyNamedTestResults.trx} {anyNamedConfig.json}"
