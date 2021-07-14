# summary of git 
Git is a distributed version control system (DVCS) that saves data in a snapshot-based file system. Git creates a snapshot of the file and keeps a reference to that every time you commit a changed version of your project. Git only stores a reference to the already-stored identical version of the file if it hasn't changed. Because the majority of the necessary information may be found in local resources, Git mostly relies on local activities. Because a project's history is stored on the local disk, it eliminates the need to fetch information from the server, allowing you to work on a project even while you're not connected to the internet or using a VPN. Git makes it extremely difficult for a snapshot of your file that is committed to being lost.
## why do you need it?
When something goes wrong, version control keeps track of every change in your code and allows you to go back in time. When numerous people are working on the same project, it's also very useful to keep concurrent work from interfering. One person may be working on the sidebar navigation while another is changing the header at the same time.
Multiple people's work is made easier by version control systems, which allow them to use different branches as part of a single "file tree" and merge their updated code to a single source.
![file](https://res.cloudinary.com/practicaldev/image/fetch/s--Gw9iaCrK--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/j3bj8cy3equfos30g535.png)

### Remote Repositories
* Pushing:

git push origin master
* Git commit

git commit -m “commit message”

* git add

If you want to stage all the files that you have worked on: git add .
