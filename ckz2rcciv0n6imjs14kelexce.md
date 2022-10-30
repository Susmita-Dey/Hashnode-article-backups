# Return Statement in Programming Languages

In this article we'll learn about Return Statement and how it is being used in programming and it's process of execution and termination.

1. **Return Statement:-** It is used to return any value from a function/method when the method is being called in the main() in any programming language.

2. Return statements are mostly used in **recursion** programs.

3. **Example to demonstrate Return Statement in Java:-** 
Here, after the function call the method returns the sum of the two variables and doesn't execute the last one i.e., the print statement and it remains unreachable and throws an error as the method ends after the return statement.

```java
public class Sum {
	public static void main(String args[]){
		int a = 10;
		int b = 20;
		int ans = sum(a,b);
		System.out.println("Answer = " + ans);
	}
	
	public static int sum(int a, int b) {
		int sum = a + b;
		return sum; // Function ends it's execution and returns the value
		
		System.out.println("Unreachable statement"); // This will give an error.
	}
}
```
 
Thus after the return statement, if there's any more lines of code then those will not be executed and will give an error and the method will stop it's execution.

---

## Hope this helps you. Thank you for reading, and let's connect!
Thank you for reading my blog. Feel free to subscribe to my [YouTube Channel](https://www.youtube.com/channel/UCsuzc8lqAbgUYo4yzpjtfSw) and connect on [LinkedIn](https://www.linkedin.com/in/susmita-dey-15a15a210/) or [Twitter](https://twitter.com/its_SusmitaDey).
Also, feel free to [support](https://www.buymeacoffee.com/susmitadey) my work.😊