Day 1:

What worked: 
- Go Fiber app ran on localhost:8080 and returned the expected responses.
- Successfully pushed to GitHub after fixing SSH key permissions.
- The Go module system automatically handled all dependencies.

What broke:

    Git push failed with "Permission denied (publickey)" because my SSH key was only on GitLab. I fixed it by adding the same public key to my GitHub account, then push worked.

What surprised you:

    When I ran go get github.com/gofiber/fiber/v3, Go automatically downloaded all the framework’s dependencies. I didn’t have to install them one by one.


