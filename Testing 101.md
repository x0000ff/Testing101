autoscale: true  
slidenumbers: true  
theme: MercadoLibre

# [fit]Testing 101

<br/>

```swift
let author = "Konstantin Portnov"
let github = "github.com/x0000ff"
```

[^ ]

![inline 60%](./img/commons/mercadolibre.png)

![right](./labtocat.png)

[^ ]: Labtocat (c) https://octodex.github.com/labtocat

---

# First things first

1. Ask at any time
2. Yes, I will share the slides
3. Yes, I know that you know about tests

---

# If you didn't test how do you know it works?...

![right 100%](./img/it-just-works.jpg)

---

# Do you understand what needs to be done?

![right 100%](./img/are-you-sure.jpg)

---

![inline fit](./img/process.png)

---

![inline 100%](./img/Requirements.png)

---

![inline 100%](./img/this-is-fine.jpg)

---

# La Brea Tar Pits

![inline 100%](./img/La Brea Tar Pits.jpg)

---
# The Mythical Man-Month

![inline 100%](./img/Brooks - The Mythical Man-Month.jpg)

---

# 🧐 Why to test?

[.code-highlight: 1]

```
1. We don't like sh*tty code
```

![right 100%](./img/shit-code.jpg)
	
---

# 🧐 Why to test?

[.code-highlight: 2]

```
1. We don't like sh*tty code
2. To sleep well
```

![right 60%](./img/sleep-well.jpg)
	
---

# 🧐 Why to test?

[.code-highlight: 3-6]

```
1. We don't like sh*tty code
2. To sleep well
3. Discover requirements
```

<br/>

- Dividable by 3 -> "Fizz"
- Dividable by 5 -> "Buzz"
- by 3 and 5 -> "FizzBuzz"

![right](./img/fizz-buzz.jpg)

---

# 🧐 Why to test?

[.code-highlight: 4]

```
1. We don't like sh*tty code
2. To sleep well
3. Discover requirements
4. Documentation
```

![right 100%](./img/forget-code.png)

---

# 🧐 Why to test?

[.code-highlight: 5-6]

```
1. We don't like sh*tty code
2. To sleep well
3. Discover requirements
4. Documentation
5. Move fast or die
	- Who said Lotus?
```

![right fit](./img/eta.jpg)

---

# 😒 When to test?

[.code-highlight: 1]

```
1. You have regression bugs
```

![right fit](./img/kenny.jpg)

---

# 😒 When to test?

[.code-highlight: 2]

```
1. You have regression bugs
2. You are scared to change the code
```

![right fit](./img/hope-it-works.jpg)

---

# 😒 When to test?

[.code-highlight: 3]

```
1. You have regression bugs
2. You are scared to change the code
3. High cost of failure
```
---

# 😒 When to test?

[.code-highlight: 4-7]

```
1. You have regression bugs
2. You are scared to change the code
3. High cost of failure
4. Long Time To Market
	- Mobile Apps
	- Desktop Apps
	- Embedded
```

![right fit](./img/coffee.jpg)

---

# 🤓 How to test?

[.code-highlight: 1]

```
1. Unit testing
```

![right fit](./img/black-box-testing-big.png)

---

# 🤓 How to test?

[.code-highlight: 2]

```
1. Unit testing
2. UI / Screenshot testing	
```

![right fit](./img/cat-lion.jpg)

---

# 🤓 How to test?

[.code-highlight: 3]

```
1. Unit testing
2. UI / Screenshot testing	
3. Integration testing
```

![right fit](./img/joins.png)

---

# 🤓 How to test?

[.code-highlight: 4]

```
1. Unit testing
2. UI / Screenshot testing	
3. Integration testing
4. End to End testing
```

![right 50%](./img/my-face.jpg)

---

# 🤓 How to test?

[.code-highlight: 5]

```
1. Unit testing
2. UI / Screenshot testing	
3. Integration testing
4. End to End testing
5. Test Driven Development
```

![right fit 100%](./img/Beard-Baby.jpg)

---

# 🧘🏽‍♀️ Yes! 
# It hurts at the beginning!

---

# 👴🏻💰 Testing it's like investing

---

# 🧗🏻‍♂️ Tests force you 
# to create better code

---

# 💣 Comment
# something and a test
# should fail

---

# 💩 100% coverage can be 100% fake
### It doesn't make sense a test which just "executes" the line

---

# Simple Code 
# = 
# Simple Test 

---

# 🖖🏼 In [S.O.L.I.D.](https://en.wikipedia.org/wiki/SOLID) We Trust

---

# 🤖 Humans shouldn't test things	 which machines can test

---

# 🕵🏻‍♂️ The test doesn't find the bug
# 👨🏻‍💻 A **human** finds the bug

---

# 🙃 The 1st thing we need to do is change the way we think

---

# 😜 Ready for some practice?[^*]

![inline 100%](./img/uf-clp.gif)

[^*]: `https://mindicador.cl/api/uf/DD-MM-YYYY`

---

# 🔪 Divide et impera

1. Network operation
2. Process Network response
3. Convert 
	3.1. **UF** ↔ **CLP**
	3.2. **CLP** ↔ **UF**
4. Format amount
...

- Cache network communication
- Localization
- Notify user on errors:
	- Networking
	- Math ( divide by 0 etc.)
- UI / Layout

![right 100%](./img/uf-clp.gif)

---


# 🤔 Q & A

---

# **Me...**

![right 50%](./img/commons/me.jpeg)

- ![:inline:](./img/commons/me.jpeg) Konstantin Portnov 

- ![:inline:](./img/commons/favicon.ico) [http://about.me/x0000ff](http://about.me/x0000ff)

- ![:inline:](./img/commons/github.png) [https://github.com/x0000ff](https://github.com/x0000ff)

- ![:inline:](./img/commons/twitter.png) [https://twitter.com/x0000ff](https://twitter.com/x0000ff)

- ![:inline:](./img/commons/linkedin.png) [https://www.linkedin.com/in/KonstantinPortnov](https://www.linkedin.com/in/KonstantinPortnov)

---

# 🙂 You can find this talk here:
# `http://bit.ly/`
# `3dvFvFQ`[^**]
![right 100%](./img/qr.png)

[^**]: https://github.com/x0000ff/Testing101

---

# ☺️ Thanks a lot!

![70% right](./img/commons/thanks.jpg)

---

# EOF
# 🍻