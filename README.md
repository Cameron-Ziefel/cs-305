# cs-305

1. Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
  
    Artemis Financial is a consulting company that develops individualized financial plans for their customers that include, savings, retirement, investments and insurance.  Aretemis Financial wants to use the most current software that includes a RESTfuyl web API.
    
2. What did you do very well when you found your client's software vulnerabilities? Whis it it important to code securely? What value does sofware security add toa  company's overall wellbeing?

    Im not sure i did anything especially well. After finding the vulnerabilities, At first understanding the report was rather difficult. It took some time and practice to understand what i was looking at. It is important to code securely because when you write code, it is important that you prioritize the sensitive data of the end users that would be using your program. SSN's, bank account numbers, and names are all information that could be potentially lost if special care is not taken towards security. The value of having a secure system adds to the companies wellbeing because it allows for trust between the users and the company itself, the user will not be as worried that they will lose sensitive information.
    
3. What part of the vulnerability assessmenbt was challenging or helpful to you?
    I personally found discovering the false positives to be somewhat difficult. At first, understanding what to look for when identifying false positives is difficult. It is sometimes hard to determine what could be considered a false positive.
    
4. How did you increase layers or security? In the future, what would you use to assess vulnerabilities and decide what mitigations techniques to use?

  I increased security in this project by using the SHA-256 hash algorithm. This algorithm takes a string and using a 256 bit key, it converts the string into a new string of a fixed length. The hash value is unrecognizable, and has never had a collision recorded. I think in the future, i think more study and practice will need to be had before i can give a safe answer on what i would do next. 

5. How did you make certain the code and software application were functional and secure?
    
    TO make sure that the application was function and secure, I ran the program like normal but i tested the hash algorithm in a browsser to ensure that it functioned properly. 
    
6. What resources, tools, or coding practices did you use that might be helpful in furture assignments or tasks?
  
  Like always, google is a great resource when trying to learn new coding concepts. But also, a website such as youtube also can prove to be useful. I think the knowledge of the vulnerability assessment tool is an imnportant skill to have that will be useful in the future
  
 7. Employers sometimes ask for examples of work that you have successfully completed to show your skill, knowlege, and experience. Wahat might you show future employers from thsi assignment?
 
    I think i would show the employers the user of the vulnerability assessment tool. Demonstrating how to use the assessment tool, along with konwing how to identify false positives would be a plus with employers.
