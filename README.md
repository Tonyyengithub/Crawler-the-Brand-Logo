# Crawler-the-Brand-Logo
To do: Saving the manpower to scratch the Logo-photo automative
First version only for those brand with English name.

<img src = "https://github.com/Tonyyengithub/Crawler-the-Brand-Logo/blob/master/0908_155139/2020-09-09%20%E4%B8%8B%E5%8D%882.42.25.png" width = "600">

1. Require the chromedriver and pandas, numpy, Selenium, os, time packages.
2. The 'try.csv' should contain all the target brand you want to crawler.
3. This demo utilizng the website: seeklogo.com

```
string = datetime.now().strftime("%m%d_%H%M%S") 
os.makedirs(string)
```
The above code help us create a folder, aim to save the input photo, with the name of current time

```
driver.find_element_by_xpath("//*[@id=\"searchBarInput\"]")
```
We can also use by_class, by_name, by ID, however, the Xpath is the most direct one.

```
Logo_str = str(i)
Logo_name = Logo_str + '.png'
```
Using the string type can let us save the time in modifying the file name. YOu can also save the photo in '.jpg' format.

```
imgg = img.screenshot_as_png
```
Screenshot the selected part

And the result will shown as below

<img src = "https://github.com/Tonyyengithub/Crawler-the-Brand-Logo/blob/master/0908_155139/%E6%88%AA%E5%9C%96%202020-09-08%20%E4%B8%8B%E5%8D%884.22.01.png" width = "500">

