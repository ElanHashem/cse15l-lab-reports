# **Lab Report 4**
---

My Markdownparse repo link: [Mine](https://github.com/ElanHashem/MarkDownParser.git)

Other group Markdownparse repo link: [theirs](https://github.com/ohuynh21/markdown-parser)

## Expected output for the snippits based off VS code preview 
Snippit 1

![labreport4 ss1](https://user-images.githubusercontent.com/103283907/171095821-6d1a1834-19e6-4b23-83bc-a637007e3d33.png)

Snippit 2

![labreport4 ss2](https://user-images.githubusercontent.com/103283907/171121311-a242925c-9ea4-439e-b56a-7029f78ac94b.png)

Snippit 3

![labreport4 ss4](https://user-images.githubusercontent.com/103283907/171139421-cb0c7a4e-358c-475a-b4f3-d8782db3cac1.png)

## code for testing MarkdownParse

![labreport4 ss5](https://user-images.githubusercontent.com/103283907/171142041-67abe83f-7f5c-4b4b-81c6-af0efa3f53f7.png)


## Junit testing output for my MarkdownParse

![labreport4 ss3](https://user-images.githubusercontent.com/103283907/171138965-015bb124-ace9-47b8-b0d9-09ced2cfb719.png)

All 3 tests failed

## Answering the questions

**Snippit 1**: I do think that there is a code change less than 10 lines to deal with the back ticks. I would have to add an if statment that searches through the string to find the next back tick the same way I would [] and inline code it.

**Snippit 2**: I do think there is a code change less than 10 lines to deal with nested links, brackets, and escaped brackets. For nested links and inner brackets have a boolean isSecondFront that gets set to true when the there is a second opening bracket that gets checked when a closed bracket is found and switched back to false. Escaped brackets can be dealt with an if statement that if the index before was a \ the bracket does not count.

**Snippit 3**: I do not think that there is a change less than 10 lines to fix newlines in brackets and parentheses. The process I would take to fix that is using if statements for brackets and parenthesis extend beyond the line to limit the white space in between words. I would also have to change how getLinks searches for a new link to start.
