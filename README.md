# Learn Go and HTMX

Learn Go and HTMX by building a simple chatting application.

## 01 - First steps
```go
////////////////////////////////////////////
// Go Concepts:
// - Entrypoint
// - Imports
// - Variables
// - Functions
// - Structs

////////////////////////////////////////////
// Tasks:
// - [ ] 1. Create a function that prints a simple message.
// - [ ] 2. Create `Message` struct.
// - [ ] 3. Create `ToString` method.

// Define the entrypoint package.

// Set imports.

// 1. Define `PrintMessage` function.

// 2. Define `Message` struct.

// 3. Define `ToString` method.

// Define entrypoint function.
```

## 02 - Simple HTTP Server

```go
////////////////////////////////////////////
// Go Concepts:
// - "net/http" package
//   - Handlers
//   - Serving files
// - Anonymous functions
// - Casting

////////////////////////////////////////////
// Tasks:
// - [ ] 1. Create simplest possible HTTP server.
// - [ ] 2. Print "Hello world" to client at "/".
// - [ ] 3. Serve `index.html` file.

// 1. Define `RunSimplestHTTPServer` function.

// 2. Define `RunServerWithHandler` function.

// 3. Define `ServeHTMLFile` method.
```

## 03 - Communicating with the Client using HTMX
```go
////////////////////////////////////////////
// Go Concepts:
// - Getting form values with `http.Request.FormValue`
//
// HTMX Concepts:
// - GET/POST Methods
// - Inner/Outer Swapping
// - Starting to think of HTML as "components"

////////////////////////////////////////////
// Tasks:
// - [ ] 1. Display name (form) input and "Enter chat" button
// - [ ] 2. Print name sent from client on server
// - [ ] 3. Replace welcome message with client name using HTMX
// - [ ] 4. Return "chatroom page" from server

// 2. Define `PrintNameHandler` function.

// 3. Define `SendClientNameHandler` function.

// 4. Define `ReturnChatroomPage` function.
```

## 04 - Go Templates
```go
```
