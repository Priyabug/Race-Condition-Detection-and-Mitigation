<h1>Race-Condition-Detection-and-Mitigation</h1>

<h2>Description</h2>
 A race condition arises when multiple processes simultaneously access and modify the same data, and the execution outcome depends on the sequence of these accesses. 
 If a privileged program contains a race-condition vulnerability, attackers can execute a parallel process to "race" against the privileged program, aiming to alter its behavior.
 Here we have exploited the vulnerability and gain the root privilege. In addition to the attacks, and we will also discuss about various protection schemes that can be used to counter the race-condition attacks.
 The lab covers the following topics:
    • Race condition vulnerability
    • Sticky symlink protection
    • Principle of least privilege


 <h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Ununtu 20.04 VM</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

Task 1: Choosing Our Target<br>
Task 2: Launching the Race Condition Attack<br>
         2.A: Simulating a Slow Machine<br>
         2.B: The Real Attack<br>
         2.C: An Improved Attack Method<br>
Task 3: Countermeasures<br>
         3.A: Applying the Principle of Least Privilege
         3.B: Using Ubuntu’s Built-in Scheme


<embed src a href="https://drive.google.com/file/d/1uCxoX4KH4VHQnJwIdMl1H1Zu7jlkE_vg/view" alt=""></a> </embed>

