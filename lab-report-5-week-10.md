# Lab Report 5
---

I found the test with different results using the command: `diff MarkDownParser/results.txt markdown-parser/results.txt`

The command outputs all the differencers between results.txt of my markdown-parse and the given markdown-parse

## First difference found

[test 495](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/495.md)

![labreport5 ss1](https://user-images.githubusercontent.com/103283907/172286922-bf9bb9c8-894d-4a63-8999-034ddfddb2c4.png)

the first result is the given parser actual result and the second one is my actual result

The test in the file was

![labreport5 ss2](https://user-images.githubusercontent.com/103283907/172294707-2b85b9ea-9ae5-47a4-b23c-02f4938fc6eb.png)

the excpected output  is 

![labreport5 ss3](https://user-images.githubusercontent.com/103283907/172299876-d1402cab-21ea-4438-b332-f56fa0b5e101.png)

Both of my implementation and the given one were incorrect in this test. What I did wrong in my implementation is that it does not have a test case that properly handles not having a closing parethese. This is solvable by checking if the string contains a ).

![labreport5 ss4](https://user-images.githubusercontent.com/103283907/172313450-3f4b2f7f-7a33-4816-b9b2-d9fd4ea2da1b.png)


## Second difference found

[test 487](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/487.md)

![labreport5 ss5](https://user-images.githubusercontent.com/103283907/172313962-2e130a35-70db-4523-926e-6442f82bcae7.png)

the first result is the given parser actual result and the second one is my actual result

the test in the file was

![labreport5 ss6](https://user-images.githubusercontent.com/103283907/172315337-8d76f9c0-be55-460b-a7b3-b00734467a79.png)

the expected output is

![labreport5 ss7](https://user-images.githubusercontent.com/103283907/172317013-591fbc14-ce61-4980-9459-c330f6463852.png)

Both my implementation and the given parser were wrong in this test. What I did wrong in my implementation is that I did not account for a scenario where the link has a space in between. The way to fix this would be to have an if statment that picks up the whitespace and returns the string as it origanlly was.

![labreport5 ss8](https://user-images.githubusercontent.com/103283907/172319151-81481815-2c83-4126-bb48-5ef638a19e48.png)
