# blog

- this is a simple project for showing the demonstration of TDD process

---

### Member

- 110710529 廖明志

- 110710506 吳博霖

* 110710501 張育騰

### Definition

- this blog should have basic blog function, including saving user's post and showing all posts

### Test Method

- TDD

### Cooperaiton Model

- `github + pull request`

### Dispatch

- 廖明志

  - `front end`

  * `integration`

- 吳博霖

  - `Django model building`

  - `view of user posting`

- 張育騰

  - `view of home page`

  - `view of specific post content`

### Code & Unit test

- 廖明志

  - `integration`

    ```
    Creating test database for alias 'default'...
    System check identified no issues (0 silenced).
    .
    ----------------------------------------------------------------------
    Ran 1 test in 0.043s

    OK
    Destroying test database for alias 'default'...

    ```

- 吳博霖

  - `Django model building`

    ```
    Creating test database for alias 'default'...
    System check identified no issues (0 silenced).
    .
    ----------------------------------------------------------------------
    Ran 1 test in 0.005s

    OK
    Destroying test database for alias 'default'...

    ```

  - `view of user posting`

    ```
    resCreating test database for alias 'default'...
    System check identified no issues (0 silenced).
    .
    ----------------------------------------------------------------------
    Ran 1 test in 0.033s

    OK
    Destroying test database for alias 'default'...
    ult
    ```

- 張育騰

  - `view of home page`

    ```
    Creating test database for alias 'default'...
    System check identified no issues (0 silenced).
    .
    ----------------------------------------------------------------------
    Ran 1 test in 0.003s

    OK
    Destroying test database for alias 'default'...

    ```

  - `view of specific post content`

    ```
    Creating test database for alias 'default'...
    System check identified no issues (0 silenced).
    .
    ----------------------------------------------------------------------
    Ran 1 test in 0.049s

    OK
    Destroying test database for alias 'default'...
    ```

### Integration & Test

- result

  ```
  Creating test database for alias 'default'...
  System check identified no issues (0 silenced).
  .....
  ----------------------------------------------------------------------
  Ran 5 tests in 0.041s

  OK
  Destroying test database for alias 'default'...

  ```

### Demo
![](src\demo.gif)

### Publish
