# COMP311_Sample
### Practice repository for GitHub workflow assignment

I wish I could be handing this in more complete, unfortunately I had a run of bad luck and have had to made do submitting what I have as I cannot afford to spend more time on this assignment, as much as I might wish to
- I lost track of the order I should be completing the changes to the repository almost immediately. With GitHub tracking every change I couldn't go back and make corrections without further adding to the misteps. Instead of scrapping everything and starting over (or using more advanced GitHub reseting operations, which seemed inadvisable) I opted to keep continue adding  commits, pull requests, review/comments and merges, and hope that even out of order I have demonstrated sufficiant understanding
- I made my simple application using java, but forgot I'd need to make it using a build tool like Maven/Gradle to create the release in GitHub. I was able to build my own jar file, but I do not know how to make the release in GitHub without the Maven/etc. integration and I do not have the time to start over
- One reason I don't have time is because I spent a lot of it trying to grasp using the local git hooks - I was able to implement a simple Pre-Commit hook - but could not find sufficient documentation to explain using the pre-commit-msg / commit-msg hook I would need to enforce commit message conventions. Without being able to modify the commit messages, I can only offer this screen grab to demonstrate the small success I had:
  ![alt text for screen readers](/githook_screenshot.jpg "Image of Pre-Commit git hook displaying in terminal")
- Finally, because I wasn't able to build the release file, I could not apply the GitHub action required to build new releases. I suspect there is a way to make a new release version without building the accompanying file, but every example I could find included it, and I dont know YAML well enough to figure it out. I have added the release manually with appropriate notes, and you can see my inoperable attempts at writing the workflow files.
- I hope my efforts to demonstrate effort where I was not able to complete the instructions in-full can get me some partial marks

### Thank you
