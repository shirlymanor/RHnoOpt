How to create a gif that shows Cloudinary optimization capabilities:
1. Ask customer which pages are important for them to measure (usually 1 homepage, 1 category page, 1 product listing page, 1 product detail page)
2. When we have those pages we copy all the images urls from our chrome extension. We add these urls to excel and through concatenate function you can generate code, [example](https://docs.google.com/spreadsheets/d/1tNNa3O7xSJn1KYbH_8kbQdT5r4KEwsirdFkCdLpNV84/edit?usp=sharing).
3. On github create basic html pages with this code. [Example of all my pages are here](https://github.com/shirlymanor/RHnoOpt/blob/main/noOpt.html).
4. When you have two pages - one with current assets one with Cloudinary urls (use MO or fetch to change those urls).
5. Run both pages through Web Page test. [Example of one test result](https://www.webpagetest.org/result/230106_AiDc78_8X8/). In the url of that test result you have a test code, for this example it is 230106_AiDc78_8X8.
6. When you have results of two tests (and their codes) you can add those codes to the url of test comparison, [example here](https://www.webpagetest.org/video/compare.php?tests=230106_AiDc4K_8XB%2C230106_AiDc78_8X8&thumbSize=200&ival=100&end=doc). Then you use any metrics, videos or whatever you find there and want to present to the customer.
