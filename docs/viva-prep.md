What does go.mod contain and what does go mod tidy do?
go.mod contains the module's name and the versions(go version: 1.26) of all direct dependencies (libraries we imported). go mod tidy cleans up the file by removing any unused entries and adding missing ones.

What's the difference between go run, go build, and go install?
go run compiles and runs the code immediately. go build only compiles and creates an executable file that you can run later. go install compiles and moves the executable to a system directory so you can run it from anywhere.

Why pick Fiber over Go's net/http standard library?
Fiber gives you convenient helpers for routing, JSON, middleware, etc., so you write less code. The standard library can do everything but requires more manual work.

What does c fiber.Ctx give you access to?
It's the request/response context. You can read incoming request data (URL, headers, body) and control the response (send text, JSON, set status code).
