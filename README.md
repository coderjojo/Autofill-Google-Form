# Autofill Google Form

Simple Python code with Selenium to automate form filling for [https://forms.gle/Zu1AYzvvEFwGgNSg8](https://forms.gle/Zu1AYzvvEFwGgNSg8) form

> code is not properly implemented but it works ; )

### Installation and Usage

Install all requirements and download Firefox webdriver for selenuim  (you can use any webdriver you want, just make necessary changes in code)

[https://github.com/mozilla/geckodriver/releases/tag/v0.28.0](https://github.com/mozilla/geckodriver/releases/tag/v0.28.0)

```bash
pip3 install -r requirement.tx
```

Do changes in code suitable for your form like change logic of if else statements according to the input you want.

Remember to use the same class name for textbox, checkbox, submit buttons etc given in the code and change the ordering of the events to make it work properly (refer above google form example and use inspect element if you are stuck at some point)

Change the value of the variable test according to your sample needs and run the code

```bash
python3 main.py
```
