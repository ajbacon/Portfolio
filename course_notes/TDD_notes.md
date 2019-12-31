# Test & Behaviour Driven Development Notes


## rspec


## Mocks and Doubles


## Capybara 


### Setup of Capybara

* Install Firefox: ```brew cask install firefox```
* List ```capybara``` and ```selenium-webdriver``` in a Gemfile (and ensure ```bundle``` is run)
* Install Firefox GeckoDriver: ```brew install geckodriver```

By default, Capybara uses the ```:rack_test``` driver, which is fast but limited: it does not support JavaScript, nor is it able to access HTTP resources outside of your Rack application, such as remote APIs and OAuth services. To get around these limitations, a different default driver can be used, for example selenium.

* add ```Capybara.default_driver = :selenium``` and ```Capybara.server = :webrick``` to the spec_helper file.


### Useful Capybara Links
[Capybara Cheat Sheet](https://devhints.io/capybara)  
[Another Capybara Cheat Sheet](https://thoughtbot.com/upcase/test-driven-rails-resources/capybara.pdf)  



## Useful links


