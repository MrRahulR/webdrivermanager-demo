# WebDriverManager Demo

To download the code in local clone this repository 

``` git clone https://github.com/MrRahulR/webdrivermanager-demo.git```

You can also star ⭐ the repository for the future reference.

To update code or refactor code or adding new feature, please create
a separate branch and raise a PR against ```main``` branch. The PR
will be approved after reviewed. 

#### What is WebDriverManager?
WebdriverManager is an automated browser management for Selenium WebDriver 
design by @bonigarcia -
https://github.com/bonigarcia/webdrivermanager
WebDriver Manager actually gets your browser version and
download the compatible browser binary by itself to make 
you run your code without interruption.

#### Why is WebDriverManager is required?
As an automation engineer, I believe you have always set 
the path for the browser binary. You will know that in 
order to use some browsers such as Chrome, Firefox, 
Opera, PhantomJS, Microsoft Edge, or Internet Explorer, 
first, you need to download a binary file that allows 
WebDriver to handle browsers. In addition, the absolute 
path to this binary must be set as JVM properties, as 
follows:

```
System.setProperty("webdriver.chrome.driver", "path/to/chromedriver.exe");
System.setProperty("webdriver.gecko.driver", "path/to/geckodriver.exe");
System.setProperty("webdriver.ie.driver", "path/to/IEDriverServer.exe");
```


I believe it’s a bit annoying every time you need to set
the binary path. Not just limited to this one, you also
need to change the binaries frequently as browser version
changes or sometimes Selenium version changes.