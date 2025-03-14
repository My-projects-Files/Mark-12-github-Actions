# Mark-12-github-Actions
This is to practice the github action related tools. its is similar to jenkins but easy to use.

## Self hosted runner

github provides a predefined runner that can be used anytime for free, but this runners are public and not a best practice for privicy and security complaince.
in those case we can use self hosted runner and configure them to run the actions.
~~~
repo --> settings --> actions --> self hosted
~~~

Note: in caase of EC2, Be sure to allow http and https traffic in both inbound and outbound so github and instance can communicate.

in actions file we can select "ubuntu-latest" or the "(self-hosted name)" at run-on to specify if it need to be run as hosted runner or self hosted runner.

## Reference
find the reference documents in the github action offical page
~~~
https://docs.github.com/en/actions/use-cases-and-examples/building-and-testing/building-and-testing-python
~~~

