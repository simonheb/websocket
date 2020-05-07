# httpuv

<details>

* Version: 1.5.2
* Source code: https://github.com/cran/httpuv
* URL: https://github.com/rstudio/httpuv
* Date/Publication: 2019-09-11 05:40:02 UTC
* Number of recursive dependencies: 31

Run `revdep_details(,"httpuv")` for more info

</details>

## Newly broken

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      namespace 'later' 1.0.0 is already loaded, but >= 1.0.0.9004 is required
      Backtrace:
       1. websocket::WebSocket
       2. base::getExportedValue(pkg, name)
       3. base::asNamespace(ns)
       4. base::getNamespace(ns)
       5. base::loadNamespace(name)
       7. base::loadNamespace(i, c(lib.loc, .libPaths()), versionCheck = vI[[i]])
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      [ OK: 207 | SKIPPED: 8 | WARNINGS: 0 | FAILED: 1 ]
      1. Error: a close message with no payload is processed (@test-frame-completion.R#26) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

## In both

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

