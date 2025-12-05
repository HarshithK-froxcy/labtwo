first go to slack or you can go to this link if you dont find any apps https://my.slack.com/services/new/jenkins-ci
and the go to manage jenkins in that go to credentials 
in Stores scoped to Jenkins click on global and then 
there select secret text and add secrete from the jenkins cli from app and give any id and des
after create a new project and then select the windows execute batch command and there add jenkins -version
and after that in post build steps select slack notifications and mark all and down there will be advanced click on thaat 
give the workspace name and select the credential and then at last there will be Channel / member id give the channel name and save it and run
