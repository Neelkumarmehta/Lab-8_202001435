Lab-8_202001435
# Lab-8 IT314

Name:- Mehta Neelkumar Hirenkumar

Student Id:- 202001435

Course:- IT314

## **LAB - 8:** Unit Testing with JUnit

**Code:**

![image](https://user-images.githubusercontent.com/107932618/233590428-84b528dc-1251-473f-8233-6a7085ebdbac.png)


### **Lab Exercise:**

**1. Create a new Eclipse project, and within the project create a package.**

![image](https://user-images.githubusercontent.com/107932618/233590542-cbc79774-c7de-4c34-9a91-8a4a5b17ac44.png)


![image](https://user-images.githubusercontent.com/107932618/233590824-9b53ced4-71c0-49d9-9e0f-d1067b5b574b.png)


**2. Create a class for a Boa.**

![image](https://user-images.githubusercontent.com/107932618/233591895-5f607845-0c49-4809-8a4c-6ad4a37ae9ad.png)


**3. Follow the instructions in the JUnit tutorial in the section “Creating a JUnit Test Case in Eclipse”. You’ll be creating a test case for the class Boa. When you’re asked to select test method stubs, select both isHealthy() and fitsInCage(int).**

**Test Case Code:**

![image](https://user-images.githubusercontent.com/107932618/233592007-8f512b41-74aa-43eb-9aa1-6f5daf76d55b.png)


**4. Now it’s time to write some unit tests. Notice that the BoaTest class that JUnit created for you contains stubs for several methods. The first stub (for the method setUp()) is annotated with @Before. The @Before annotation denotes that the method setUp() will be run prior to the execution of each test method. setUp() is typically used to initialize data needed by each test. Modify the setUp() method so that it creates a couple of Boa objects, as follows:**

![image](https://user-images.githubusercontent.com/107932618/233592189-071cab9b-0cb1-4f1b-8a9f-9f36f68992c4.png)

**Test Case Code:**

![image](https://user-images.githubusercontent.com/107932618/233592345-216b2308-5f2c-4024-9d26-3df9ca2b4076.png)


**5. JUnit also provided stubs for two test methods, each annotated with @Test. Work on the testIsHealthy() method first. The purpose of this method is to check that the isHealthy() method in the Boa class behaves the way it’s supposed to. In the JUnit tutorial, read the section on “Writing Tests”. Modify the testIsHealthy() method so that it checks the results of activating the isHealthy() method on the two Boa objects you created in setup(). Likewise, modify the testFitsInCage() method to test the results of that method. Make sure your test is robust; it should check the results when the cage length is less than the length of the boa, when the cage length is equal to the length of the boa, and when the cage length is greater than the length of the boa. Should you write tests for both jen and ken?**

**Ans:** Yes, We should write tests for both Ken and Jen.

**6. Now you can run your tests. Read the section “Running Your Test Case” in the tutorial. Did you get a green bar in the JUnit pane? If you got a red bar, use the output in the JUnit pane to determine which test(s) failed. Fix your tests, and try running the test case again. It’s important to note that a red bar doesn’t necessarily mean that the test case is written incorrectly; it could be that the method that’s being tested isn’t correct. In fact, that’s what unit testing is supposed to do – help us find errors in our code. When a test fails, you need to determine if the error is in the test case itself or in the code it’s testing.**

**Test Case Code:-**

![image](https://user-images.githubusercontent.com/107932618/233592431-62080860-ede2-4e58-b28c-841f4342eee7.png)


**7. Add a new method to the Boa class, with this purpose and signature: // produces the length of the Boa in inches public int lengthInInches(){ // you need to write the body of this method } Add a new test case to the BoaTest class that tests the lengthInInches() method. Make sure you annotate the new test method with @Test. Run your tests.**

**Function added in the Boa Class:**

![image](https://user-images.githubusercontent.com/107932618/233592570-50d7f1a8-c2f9-4973-a59c-92dc19e6885e.png)

**Test Case Code:**

![image](https://user-images.githubusercontent.com/107932618/233592775-e1d1f46f-d06b-4bc9-9580-c09479c79f8e.png)
