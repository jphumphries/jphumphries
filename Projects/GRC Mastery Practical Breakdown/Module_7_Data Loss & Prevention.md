# [Mod 7] Data Loss & Prevention

An emergency executive meeting at Oscorp was held after reports of serious side effects of Oscorp's new medication hit the press.



Norman Osborn and Harry Osborn are extremely concerned. They suspect an employee has leaked the information to the press.



Oscorp use Microsoft Office 365 and The Microsoft Azure cloud. Internally, they use Microsoft SharePoint.



**Problem: Oscorp wants you to design a comprehensive "Insider Threat" program to monitor and stop employees from stealing and leaking sensitive data outside the organization.**

---

## My Thoughts & Recommendations

What methods are needed to keep data from internal research from reaching the outside world?

**First:**

- There are too few eyes on who has access to what data and when. We need to employ 
  - We have to make sure that any employees, disgruntled or otherwise, can't take data willingly or accidently carry data out with them or send it to outside locations. Locking down these vulnerabilities will reduce the lanes with which any internal threat actor can damage the company's brand.
- No outside data drives need to be allowed to connect to internal systems to prevent unauthorized movement of data.
 
**I recommend that:**

- Oscorp first classify sensitive and confidential data, based on the developed classification policy, using a program like MSFT Azure AIP. 
- Data needs to be encrypted for movement within the company.
  - To further monitor data movement a DLP system should be deployed to catch any sensitive data being moved from the servers to employee owned tech or emailed to outside email accounts.
- To monitor these states Oscorp will need to expand the SOC team to monitor employee threats and help optimize the DLP system so the most critical alerts will be received and analyzed.
- Employees that are separated from the company immediately lose access to any internal system that they were using for their role.
