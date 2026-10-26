Answering your questions, honestly speaking, there are a few questions I really don't have an answer to. We have to work around it and find it. The business owner, MD-level owner for AIIC forum: I have to check with my leads and find it out. If you are also not able to find that from the documents and things, skip that.

Code storage: do you have access to a Git repository? I do have access to the repository, which I can use for personal testing (for example, logging in using my Google account). For that I don't have a GitHub repository created with my Blackrock credentials or any other sort of service account credentials or something but I can access Git repositories. For example if you have any Git repository or find documents related to creating a Git repository for the sort of test run, if possible, then our build is almost ready to take into the cloud. We can do that.

The cloud host is Aladdin Studio. I'm really not sure what the third question you were exactly asking was, whether I can access Aladdin Studio or not. If that was the question, yes I can access it. Regarding the cloud host, if I answered your question then just move on with the fourth question.

Jira means, as you said, for this particular cloud test, what I'm going to do is use my API credentials to do this but we can find the Jira admin and get that service account created as well. That is for real production. To show how it will actually be run in the cloud and the whole process, since everything has been running locally, if you see, the link has downloaded the PDF using the link. Then the process has started to extract it and the Excel output has been stored in that SharePoint folder. That too is local but it is kind of syncing with SharePoint. It triggers the Power Automate flow and then it runs the Power Automate script and gives the output in the Jira ticket.

This process has to be cut down. It has to directly access the Amazon S3 folder since it has been stored over there. I don't think we need to download and extract with the script. Also since it is a PDF, no modification would happen to the source. It is just used for extraction. It has to just extract it, strip the data from that particular stored PDF link in Amazon S3, and then the embedded Excel Power Automate script has to execute.

For that previously we checked whether we have the option to upload our script to the team SharePoint. Since our current organisation has not provided access, which can be easily gotten from the Microsoft 365 admin, that one thing has to be kept in mind. That is the only blocker right now in this cloud testing build as well.

For that as well we'll use the same sort of local setup, maybe plus a little bit of a cloud thing, and we'll make those configuration files and all the other necessary things easily editable. Say, for example, that means I don't have to come to you for each and every single step. Rather I will have a knowledge file documenting everything and it has to mention what has to be changed exactly and where. This has to be done and that's it, pretty much, about the cloud test build of this phase 1. Once this has been completed, all the approvals we've been looking for, taking it to AIC, and everything would be super busy. On top of that, since it is running locally, taking it to those AIC committees has been a really really big thing.

Right now our AI is not producing a really good result. It has been spitting out the worst result possible.
1. We'll fix that AI model.
2. I will test it out in a separate chat room and then I will come up to you with the results and all the essentials which you need to correct it.
3. We will proceed further.


I hope you understood all the necessary points. If you still have any doubt or need any clarification, do ask. If you have a better suggestion, please do tell. On top of that, if you need any additional sources or a knowledge file from my side, please do ask. 