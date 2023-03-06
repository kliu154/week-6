Just-in-Time (JIT) compiles the application in the browser at runtime. JIT compilation is the default when you run the ng build (build only) or ng serve (build and serve locally) CLI commands.

Ahead-of-Time (AOT) compiles the application at build time on the server. For AOT compilation, include the --aot option with the ng build or ng serve command. Another ways is using --prod which by default production mode is configured in Angular.json with AOT is set to true.

![image](https://user-images.githubusercontent.com/123418101/223253022-e7022299-85fc-4323-8389-7a16262d7167.png)
