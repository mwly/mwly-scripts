# mwly-scripts

Welcome to my scripts repository.

I want to use it to share some scripts that ease my workflow.

To use just add the folder to $PATH.

## scripts

### markservl

#### Requirements

npx markserv

#### Function

Opens a fileserver at the current dir on localhost:8080 and visits that address in your browser.

### markservx

#### Requirements

npx markserv

#### Function

Opens a fileserver at the current dir on localhost:8080 and visits that address in your browser, just as markservl does.
Additionaly the server will be exposed to 0.0.0.0 and visible to other devices allowed by your firewall ( will be all if not configured otherwise).
Please be careful and think about who could find you on the network you are exposing on.

### pandoc2pdf

#### Requirements

pandoc
which requires Texlive

#### Function

converts the markdown file specified in the first argument to pdf.

#### Usage

pandoc2pdf test

converts test.md to test.pdf




