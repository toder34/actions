<!-- markdownlint-disable MD033 MD041 -->
<!-- Generated by .automation/build.py, please do not update manually -->

<div align="center">
  <a href="https://ktlint.github.io" target="blank" title="Visit linter Web Site">
    <img src="https://miro.medium.com/max/655/1*sLboL6JnC9yUodFsdSMB-w.png" alt="ktlint" height="150px" class="megalinter-banner">
  </a>
</div>

## ktlint documentation

- Version in Mega-Linter: **0.40.0**
- Visit [Official Web Site](https://ktlint.github.io){target=_blank}
- See [Index of problems detected by ktlint](https://ktlint.github.io/#rules){target=_blank}

[![ktlint - GitHub](https://gh-card.dev/repos/pinterest/ktlint.svg?fullname=)](https://github.com/pinterest/ktlint){target=_blank}

## Configuration in Mega-Linter

- Enable ktlint by adding `KOTLIN_KTLINT` in [ENABLE_LINTERS variable](https://nvuillam.github.io/mega-linter/configuration/#activation-and-deactivation)
- Disable ktlint by adding `KOTLIN_KTLINT` in [DISABLE_LINTERS variable](https://nvuillam.github.io/mega-linter/configuration/#activation-and-deactivation)

- Enable **auto-fixes** by adding `KOTLIN_KTLINT` in [APPLY_FIXES variable](https://nvuillam.github.io/mega-linter/configuration/#apply-fixes)

| Variable                           | Description                                                                                                                                                                                  | Default value      |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|
| KOTLIN_KTLINT_ARGUMENTS            | User custom arguments to add in linter CLI call<br/>Ex: `-s --foo "bar"`                                                                                                                     |                    |
| KOTLIN_KTLINT_FILTER_REGEX_INCLUDE | Custom regex including filter<br/>Ex: `(src|lib)`                                                                                                                                            | Include every file |
| KOTLIN_KTLINT_FILTER_REGEX_EXCLUDE | Custom regex excluding filter<br/>Ex: `(test|examples)`                                                                                                                                      | Exclude no file    |
| KOTLIN_KTLINT_FILE_EXTENSIONS      | Allowed file extensions. `"*"` matches any extension, `""` matches empty extension. Empty list excludes all files<br/>Ex: `[".py", ""]`                                                      | `[".kt", ".kts"]`  |
| KOTLIN_KTLINT_FILE_NAMES_REGEX     | File name regex filters. Regular expression list for filtering files by their base names using regex full match. Empty list includes all files<br/>Ex: `["Dockerfile(-.+)?", "Jenkinsfile"]` | Include every file |
| KOTLIN_KTLINT_DISABLE_ERRORS       | Run linter but consider errors as warnings                                                                                                                                                   | `false`            |

## IDE Integration

Use ktlint in your favorite IDE to catch errors before Mega-Linter !

| <!-- -->                                                                                                                                    | IDE                                          | Extension Name                                              | Install                                                                   |
|---------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------|-------------------------------------------------------------|---------------------------------------------------------------------------|
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/emacs.ico" alt="" height="32px" class="megalinter-icon"></a> | [Emacs](https://www.gnu.org/software/emacs/) | [flycheck-kotlin](https://github.com/whirm/flycheck-kotlin) | [Visit Web Site](https://github.com/whirm/flycheck-kotlin){target=_blank} |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/vim.ico" alt="" height="32px" class="megalinter-icon"></a>   | [vim](https://www.vim.org/)                  | [ale](https://github.com/w0rp/ale)                          | [Visit Web Site](https://github.com/w0rp/ale){target=_blank}              |

## Mega-Linter Flavours

This linter is available in the following flavours

| <!-- -->                                                                                                                                                  | Flavor                                                                         | Description                                           | Embedded linters | Info                                                                                                                                                                                               |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|-------------------------------------------------------|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/images/mega-linter-square.png" alt="" height="32px" class="megalinter-icon"></a> | [all](https://nvuillam.github.io/mega-linter/supported-linters/)               | Default Mega-Linter Flavor                            | 80               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter)                             |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/dart.ico" alt="" height="32px" class="megalinter-icon"></a>                | [dart](https://nvuillam.github.io/mega-linter/flavors/dart/)                   | Optimized for DART based projects                     | 36               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-dart/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-dart)                   |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/documentation.ico" alt="" height="32px" class="megalinter-icon"></a>       | [documentation](https://nvuillam.github.io/mega-linter/flavors/documentation/) | Mega-Linter for documentation projects                | 35               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-documentation/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-documentation) |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/dotnet.ico" alt="" height="32px" class="megalinter-icon"></a>              | [dotnet](https://nvuillam.github.io/mega-linter/flavors/dotnet/)               | Optimized for C, C++, C# or VB based projects         | 41               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-dotnet/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-dotnet)               |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/go.ico" alt="" height="32px" class="megalinter-icon"></a>                  | [go](https://nvuillam.github.io/mega-linter/flavors/go/)                       | Optimized for GO based projects                       | 36               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-go/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-go)                       |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/java.ico" alt="" height="32px" class="megalinter-icon"></a>                | [java](https://nvuillam.github.io/mega-linter/flavors/java/)                   | Optimized for JAVA based projects                     | 36               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-java/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-java)                   |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/javascript.ico" alt="" height="32px" class="megalinter-icon"></a>          | [javascript](https://nvuillam.github.io/mega-linter/flavors/javascript/)       | Optimized for JAVASCRIPT or TYPESCRIPT based projects | 44               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-javascript/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-javascript)       |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/php.ico" alt="" height="32px" class="megalinter-icon"></a>                 | [php](https://nvuillam.github.io/mega-linter/flavors/php/)                     | Optimized for PHP based projects                      | 39               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-php/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-php)                     |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/python.ico" alt="" height="32px" class="megalinter-icon"></a>              | [python](https://nvuillam.github.io/mega-linter/flavors/python/)               | Optimized for PYTHON based projects                   | 42               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-python/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-python)               |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/ruby.ico" alt="" height="32px" class="megalinter-icon"></a>                | [ruby](https://nvuillam.github.io/mega-linter/flavors/ruby/)                   | Optimized for RUBY based projects                     | 36               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-ruby/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-ruby)                   |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/rust.ico" alt="" height="32px" class="megalinter-icon"></a>                | [rust](https://nvuillam.github.io/mega-linter/flavors/rust/)                   | Optimized for RUST based projects                     | 36               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-rust/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-rust)                   |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/salesforce.ico" alt="" height="32px" class="megalinter-icon"></a>          | [salesforce](https://nvuillam.github.io/mega-linter/flavors/salesforce/)       | Optimized for Salesforce based projects               | 36               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-salesforce/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-salesforce)       |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/scala.ico" alt="" height="32px" class="megalinter-icon"></a>               | [scala](https://nvuillam.github.io/mega-linter/flavors/scala/)                 | Optimized for SCALA based projects                    | 36               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-scala/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-scala)                 |
| <img src="https://github.com/nvuillam/mega-linter/raw/master/docs/assets/icons/terraform.ico" alt="" height="32px" class="megalinter-icon"></a>           | [terraform](https://nvuillam.github.io/mega-linter/flavors/terraform/)         | Optimized for TERRAFORM based projects                | 38               | ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nvuillam/mega-linter-terraform/v4) ![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/mega-linter-terraform)         |

## Behind the scenes

### How are identified applicable files

- File extensions: `.kt`, `.kts`

<!-- markdownlint-disable -->
<!-- /* cSpell:disable */ -->

### Example calls

```shell
ktlint myfile.kt
```

```shell
ktlint --format myfile.kt
```


### Help content

```shell
An anti-bikeshedding Kotlin linter with built-in formatter
(https://github.com/pinterest/ktlint).

Usage:
  ktlint <flags> [patterns]
  java -jar ktlint <flags> [patterns]

Examples:
  # check the style of all Kotlin files inside the current dir (recursively)
  # (hidden folders will be skipped)
  ktlint

  # check only certain locations (prepend ! to negate the pattern,
  # Ktlint uses .gitignore pattern style syntax)
  ktlint "src/**/*.kt" "!src/**/*Test.kt"

  # auto-correct style violations
  ktlint -F "src/**/*.kt"

  # custom reporter
  ktlint --reporter=plain?group_by_file
  # multiple reporters can be specified like this
  ktlint --reporter=plain \
    --reporter=checkstyle,output=ktlint-checkstyle-report.xml
  # 3rd-party reporter
  ktlint --reporter=csv,artifact=com.github.user:repo:master-SNAPSHOT

Flags:
  -a, --android              Turn on Android Kotlin Style Guide compatibility
      --color                Make output colorful
      --color-name=<colorName>
                             Customize the output color
      --debug                Turn on debug output
      --disabled_rules=<disabledRules>
                             Comma-separated list of rules to globally disable. To
                               disable standard ktlint rule-set use
                               --disabled_rules=standard
  -F, --format               Fix any deviations from the code style
      --limit=<limit>        Maximum number of errors to show (default: show all)
      --relative             Print files relative to the working directory (e.g.
                               dir/file.kt instead of /home/user/project/dir/file.kt)
      --reporter=<reporters> A reporter to use (built-in: plain (default), plain?
                               group_by_file, json, checkstyle, html). To use a
                               third-party reporter specify a path to a JAR file on
                               the filesystem.
  -R, --ruleset=<rulesets>   A path to a JAR file containing additional ruleset(s)
      --stdin                Read file from stdin
  -v, --verbose              Show error codes
      --editorconfig=<editorConfigPath>
                             Path to .editorconfig
      --experimental         Enabled experimental rules (ktlint-ruleset-experimental)
      --baseline=<baseline>  Defines a baseline file to check against
  -h, --help                 Show this help message and exit.
  -V, --version              Print version information and exit.
Commands:
  installGitPreCommitHook, --install-git-pre-commit-hook  Install git hook to
                                                            automatically check
                                                            files for style
                                                            violations on commit
  installGitPrePushHook, --install-git-pre-push-hook      Install git hook to
                                                            automatically check
                                                            files for style
                                                            violations before
                                                            push
  printAST, --print-ast                                   Print AST (useful
                                                            when
                                                            writing/debugging
                                                            rules)
  applyToIDEA, --apply-to-idea                            Update Intellij IDEA
                                                            Kotlin codestyle
                                                            settings (global)
  applyToIDEAProject, --apply-to-idea-project             Update Intellij IDEA
                                                            project settings
  generateEditorConfig                                    EXPERIMENTAL!!!
                                                            Generate kotlin
                                                            style section for '.
                                                            editorconfig' file.
```

### Installation on mega-linter Docker image

- Dockerfile commands :
```dockerfile
RUN curl --retry 5 --retry-delay 5 -sSLO https://github.com/pinterest/ktlint/releases/latest/download/ktlint && \
    chmod a+x ktlint && \
    mv "ktlint" /usr/bin/

```


### Example success log

```shell
Results of ktlint linter (version 0.40.0)
See documentation on https://nvuillam.github.io/mega-linter/descriptors/kotlin_ktlint/
-----------------------------------------------

[SUCCESS] .automation/test/kotlin/kotlint_good_1.kt
    

```

### Example error log

```shell
Results of ktlint linter (version 0.40.0)
See documentation on https://nvuillam.github.io/mega-linter/descriptors/kotlin_ktlint/
-----------------------------------------------

[ERROR] .automation/test/kotlin/kotlin_bad_1.kt
    .automation/test/kotlin/kotlin_bad_1.kt:1:1: File must end with a newline (\n)
    .automation/test/kotlin/kotlin_bad_1.kt:2:20: Unnecessary semicolon
    .automation/test/kotlin/kotlin_bad_1.kt:3:16: Redundant curly braces
    .automation/test/kotlin/kotlin_bad_1.kt:3:27: Unnecessary semicolon
    .automation/test/kotlin/kotlin_bad_1.kt:5:15: Unnecessary semicolon

```