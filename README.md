It sends message on linkedin using selenium-pro library

### Installation
```sh
pip install selenium_pro
```

### Code
```sh
from selenium_pro.webdriver.common.keys import Keys
from selenium_pro import webdriver
driver = webdriver.Start()
# to open the url in browser
driver.get('https://www.linkedin.com/in/leilagharani/')
# to click on the element(Message) found
driver.find_element_by_pro('lYGE64dmZqmPvbI').click()
# to click on the element found
driver.find_element_by_pro('xKndQk6s3DBdPBr').click()
# to type content in input field
driver.find_element_by_pro('CysLa3urzcyNbaG').send_keys('hope you are having a geat day')
# to click on the element(Send) found
driver.find_element_by_pro('2DzFOflq4I5UzlA').click()
# to click on the element found
driver.find_element_by_pro('n5WYaoXHASPucwq').click()
```

### Contact Us
* [Telegram](https://t.me/datakund)
* [Website](https://datakund.com)
