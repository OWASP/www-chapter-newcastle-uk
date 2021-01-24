---
title: CurrentEvent
layout: null
displaytext: Upcoming Event
tab: true
order: 1
tags: newcastle
altfooter: true

---

## Next Event

**23/02/2021** 1900 - 2030 Online

Our first event of 2021 and we're back with two great talks. Tickets are available on our meetup event [page](https://www.meetup.com/OWASP-Newcastle-Chapter/) 

### Talk 1

**Title**: Detect complex code patterns using semantic grep 

**Speaker**: [Colleen Dai](https://www.linkedin.com/in/colleen-dai-839376b4) 

**Bio**: Colleen Dai is a security software engineer at r2c, a startup working on building static analysis tools that focus on precision and being custom-fit to the consumer. At r2c, Colleen has worked on the language parsing along with AST matching. She is also writing rules to find security vulnerabilities in open source code. Colleen recently received her B.S. in Computer Science and M.S. in Statistics from Stanford. She regularly enjoys Brazilian Jiujitsu, drawing, and trying (and failing) not to eat everything in her fridge.

**Description**: We’ll discuss a program analysis tool we’re developing called Semgrep. It's a multilingual semantic tool for writing security and correctness queries on source code (for Python, Java, Go, C, and JS) with a simple “grep-like” interface. The original author, Yoann Padioleau, worked on Semgrep’s predecessor, Coccinelle, for Linux kernel refactoring, and later developed Semgrep while at Facebook. He’s now full time with us at r2c.

Semgrep is a free open-source program analysis toolkit that finds bugs using custom analysis we’ve written and OSS code checks. Semgrep is ideal for security researchers, product security engineers, and developers who want to find complex code patterns without extensive knowledge of ASTs or advanced program analysis concepts.

For example, find subprocess calls with shell=True in Python using the query:

`subprocess.open(..., shell=True)`

This will even find snippets like:

```import subprocess as s
s.open(f'rm {args}', shell=True)
```

Or find hardcoded credentials using the query:

`boto3.client(..., aws_secret_access_key=”...”, aws_access_key_id=”...” )`

Source code: [https://github.com/returntocorp/semgrep](https://github.com/returntocorp/semgrep)

Test in your browser: [https://semgrep.dev/](https://semgrep.dev/)

### Talk 2

**Title**: Wham, bam, thank you scam!

**Speaker**: [Adam Pickering](https://www.twitter.com/Adam_P81) 

**Description**: A glance at how GDPR fines risk breeding laziness in Cyber security Management