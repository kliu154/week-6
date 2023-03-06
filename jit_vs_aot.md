Just-in-Time (JIT) compiles the application in the browser at runtime. JIT compilation is the default when you run the ng build (build only) or ng serve (build and serve locally) CLI commands.

Ahead-of-Time (AOT) compiles the application at build time on the server. For AOT compilation, include the --aot option with the ng build or ng serve command. Another ways is using --prod which by default production mode is configured in Angular.json with AOT is set to true.

!(https://miro.medium.com/v2/resize:fit:1400/format:webp/1*a15BveUQ7cFyV0P8CwLUCg.png)
