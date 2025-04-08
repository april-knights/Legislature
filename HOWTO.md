# How To - A Sample Legislation

This document provides a sample of how to actually create draft legislation. There are technical users in the April Knights who are very familiar with Github and can help you if you get stuck!

## Some Legislation

Suppose I wanted to create legislation like the currently proposed Unified Standards Act. I would go to the Legislation folder in this repo and click on "Add File" from the top right then "Create new file" like so:
![Alt text](/References/howto-1.png)

Because I can't edit the repo directly, it tells me that I need to fork it first (make my own copy) and edit that forked version. Then it will help me with suggesting the change get merged back into the repo. So, click on "Fork this repository":
![Alt text](/References/howto-2.png)


Now, I would set the name of my legislation to "Unified Stands Revisions Act.md" and start putting in content like so:
![Alt text](/References/howto-3.png)

Alternatively, I don't even need to document the actual changes to be made and just describe where I plan to make changes like so:
![Alt text](/References/howto-4.png)

Either way, I get my document formatting nicely in the "Preview" tab and then click on the top right green button, "Commit changes..."
![Alt text](/References/howto-5.png)

I don't need to add any extra info on this screen. Just click "Propose Changes"
![Alt text](/References/howto-6.png)

Congratz to me! I have a new version of the AK Governing docs in my version (called patch-1) that anyone can look at to see how it differs from the AK version. Github takes me to a branch comparison page that shows the difference with AK's version. I can share that link with anyone who wants to see my differences.
![Alt text](/References/howto-7.png)

Github then suggests that I "Create pull request", but that step isn't even necessary. At this point, I still need to go edit the other 2 files before I am ready to share it with anyone else, because I am Anachronist and I want to edit those other items. So I will click on the context menu for that file (the three dots) and select "View file" to go see it in my repo copy:
![Alt text](/References/howto-8.png)

Next I need to switch from that specific commit to my patch-1 branch so that I can get edit my other files:
![Alt text](/References/howto-9.png)

Now that I am on patch-1 branch, I can go to the Articles folder and go click on the "Edit" icon/pencil to begin making edits to the Battalion Standardization Act:
![Alt text](/References/howto-10.png)

Once I'm done making changes, I can even go to the Preview tab and select "Show Diff" if I want to see subtle highlights to indicate my changes. If I'm happy, I click on "Commit changes..."
![Alt text](/References/howto-11.png)

And because I want to package these changes along with the act that I already wrote in patch-1, I am going to make sure that it is selected that I commit directly to the patch-1 branch and then click on "Commit changes"
![Alt text](/References/howto-12.png)

I'd then go and repeat the same process to edit the Document Standardization Act and commit those changes also to patch-1. Once complete, back on my base repo page, I would see a hint to "Compare & pull request". I click it!
![Alt text](/References/howto-13.png)

And it takes me to the branch comparison page where I can see all 3 files and all differences between them:
![Alt text](/References/howto-14.png)

I may prefer to use the "Unified" diff view if that is easier for me to read:
![Alt text](/References/howto-15.png)

But everyone can now see all the differences between my repo and its patch-1 and the AK repo on my main branch. And I can share the link to people if I want them to review it.
You can view this sample legislation here [as a comparison](https://github.com/april-knights/Government/compare/main...Szeraax:Government:patch-1?diff=split&w=) or as a [pull request](https://github.com/april-knights/Government/pull/3/files). In the pull request, note that you can make comments and view the other tabs that are part of it.
