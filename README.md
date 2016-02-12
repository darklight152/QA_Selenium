# QA_Selenium
QA exercise using selenium

I would like to start off by saying that learning Selenium on the go like this was quite the challenge!  A lot of reading, trial and error and a ton of Googling was involved but it was definitely worth it as I now appreciate how powerful a tool it can be.  That said, numerous complications arose when attempting to program this little application.  Selenium often times slows down or even causes FireFox to crash, the application sometimes fails to find elements on the page which causes errors, if this occurs re-run the application.  I believe this happens because the page has not fully loaded yet and therefore it can't find certain elements.

A couple of notes, getting Selenium to run on my machine took a bit of figuring out.  One thing I needed to do was to tell my application where my FireFox browswer was installed on my computer.  Having the program find the location of FireFox will be different depending on the computer used.  The following code (line 20/21) will need to be removed or altered for the program to run I believe.

FirefoxProfile profile = new FirefoxProfile();
WebDriver driver = new FirefoxDriver(new FirefoxBinary(new File("E:/firefox/firefox.exe")), profile);


Working with Selenium has been a rewarding challenge and I'd like to refine my abilities at making simple, automated tests like this in the future.
