<h1>Changing Passwords Within Active DIrectory</h1>


<h2>Description</h2>
In this project, we will illustrate how to change a user password directly within Active Directory. We'll employ the find function to locate the user, ensuring we're in the correct organizational unit where the username is situated. Upon finding the user, we will edit the account details to enforce password renewal and generate a temporary password for the user to log back in. Additionally, this action will automatically log out the user from any currently active sessions on the operating software.


<h2>Tools and Languages Utilized</h2>
<ul>
  <li>Microsoft Active Directory</li>
</ul>



<h2>Program walk-through</h2>
<ul>
<li>Resetting a password in Active Directory is a straightforward process. Upon accessing Active Directory, we can locate the user whose password requires resetting. One convenient method is by utilizing the <ins>find</ins> function within Active Directory. As demonstrated below, let's search for a user within the Sales OU.</li><br>

<p align="center">
<img src="https://github.com/Salrocks/activedirectorychangingpasswords/blob/main/1.png" height="80%" width="80%" alt="OU modification"/>
</p>
<br>
<br>

<li>After accessing the find function, we will enter the username we wish to locate. In this instance, I am searching for 'Robert'. Upon clicking 'Find now', we receive the search results.</li><br>

<p align="center">
<img src="https://github.com/Salrocks/activedirectorychangingpasswords/blob/main/2.png" height="80%" width="80%" alt="OU modification"/>
</p>
<br>
<br>

<li>After obtaining the results, double-clicking on the name will open a tab similar to the one below. Within this tab, various options are presented, but our primary focus is on the 'Account' section, so let's navigate there.</li><br>

<p align="center">
<img src="https://github.com/Salrocks/activedirectorychangingpasswords/blob/main/3.png" height="80%" width="80%" alt="OU modification"/>
</p>
<br>
<br>

<li>On the account page, our attention is drawn to the section labeled 'Account Options' in the middle. Here, we must ensure to select the option 'User must change password on next logon,' which will compel the user to create a new password upon their next login. Once this option is checked, proceed to click 'OK' at the bottom.</li><br>

<p align="center">
<img src="https://github.com/Salrocks/activedirectorychangingpasswords/blob/main/4.png" height="80%" width="80%" alt="OU modification"/>
</p>
<br>
<br>

<li>After clicking 'OK', you should return to the <ins>find</ins> tab. Now, right-clicking on the username will bring up a list of options. Here, we have the ability to disable the account, add it to a different group, reset the password, and more. Since our objective is to reset the password, we will select that option.</li><br>
<p align="center">
<img src="https://github.com/Salrocks/activedirectorychangingpasswords/blob/main/5.png" height="80%" width="80%" alt="OU modification"/>
</p>
<br>
<br>
<li>After opting to reset the password, we are presented with this tab. Here, we will generate a new temporary password, which we will then share with Robert. Once the new temporary password is created, we click 'OK' to proceed.</li><br>

<p align="center">
<img src="https://github.com/Salrocks/activedirectorychangingpasswords/blob/main/6.png" height="80%" width="80%" alt="OU modification"/>
</p>
<br>
<br>


<li>In the image below, it's evident that we have successfully reset the password for the user Robert. Remember, once Robert logs in with the temporary password we provide, he will be prompted to create a new password.</li><br>


<p align="center">
<img src="https://github.com/Salrocks/activedirectorychangingpasswords/blob/main/7.png" height="80%" width="80%" alt="OU modification"/>
</p>
<br>
<br>
</ul>
