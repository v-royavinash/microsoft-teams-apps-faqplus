* **Knowledge base quality:** A good bot experience for your end-users is critically dependent upon the quality of your knowledge base. Please refer to these links on helpful on how to set up useful knowledge bases. 

    * https://learn.microsoft.com/en-us/azure/cognitive-services/language-service/question-answering/how-to/manage-knowledge-base
    

* **Multi-Turn Enablement:**
With the new updates to the FAQ Plus app template, the knowledge base can now support multi-turn conversations. To understand the basics of multi-turn conversations, navigate to the [Question Answering documentation](https://learn.microsoft.com/en-us/azure/cognitive-services/language-service/question-answering/overview#multi-turn-conversations) to understand about multi-turn conversations.


* **Managing user expectations:** 

    - The bot always keeps the end-user apprised of the status of their requests. For example, the bot will notify end-user about the status changes (e.g. from unassigned to assigned). You should also leverage the help tab text to define and set expectations for requestors. For example, if you goal is to answer all queries within 24 hours, mention that within the help tab.
    -  Members of the Experts team will be able to edit and delete only those QnA pairs that are added through the app. Existing QnA pairs or the ones directly added in the Question Answering service portal will not be editable.

* **Setting your expert team for success:** Similar to knowledge base quality, the success of this app in your organization also depends hugely on the experts team you have. You would want to make sure they can reap the full benefits of this app in helping end-users. Following are the items you should consider:

	* Involve them in the installation process, show them how the full app works - there are three big components - end-user bot; bot notifications in the general channel of the team; Messaging extension that enables experts to quickly shift through assigned/unassigned request.

	* Set up expectations with end-users and empower the specialists to deliver those expectations. For example, ensure that all queries do get resolved within 24 hours or the end-user is apprised of what's taking longer than usual. This will build confidence and you'd have returning end-users.

	* Leverage the 'Help Tab'. Use this tab to document process you'd like your end-users to follow. For example, giving them a lay of the land on what kind of questions they can ask and under what conditions they should escalate to asking an expert are good candidates for such content.

* **Configuring answers as rich cards instead of usual text based answers:** The knowledge base quality can be enhanced by configuring answers as rich cards to provide additional information such as title, image, supporting article link etc. Text based fields in the rich card support markdown to emphasize the message for end-users.

    ![Rich card field mapping](/Wiki/Images/FAQPlus_QnA_fieldmapping.png)
