Dns Configuration

**Domain Not Resolving Issue - Troubleshooting & Solution**

**Issue**
---------

When accessing the website, the following error occurs:

*   _"This site can’t be reached. Check if there is a typo in the domain. DNS\_PROBE\_FINISHED\_NXDOMAIN"_
    

**Cause**
---------

*   The domain is not properly pointed to the hosting provider's DNS.
    
*   DNS records are either missing or incorrectly configured.
    
*   DNS propagation delay after updates.
    

* * *

**Solution**
------------

### **1\. Check DNS Configuration**

*   Log in to your domain registrar’s panel.
    
*   Navigate to **Manage DNS Settings**.
    
*   Verify if the domain is pointing to the correct name servers.
    

### **2\. Update Nameservers**

*   Remove any existing nameservers.
    
*   Add the correct nameservers provided by your hosting provider. Example:
    
    launch1.spaceship.net
    
    launch2.spaceship.net
    
*   Save changes.
    

### **3\. Add Domain to Hosting**

*   Log in to your hosting provider’s control panel.
    
*   Go to **Hosting Manager**.
    
*   Click **Add Domain** and enter your domain name.
    
*   Select the domain from the dropdown and proceed with the setup.
    

### **4\. Flush DNS Cache (Local System)**

*   Open **Command Prompt** (Windows) and run:
    
    ipconfig /flushdns
    
*   For macOS, run in **Terminal**:
    
    sudo killall -HUP mDNSResponder
    

### **5\. Check DNS Propagation**

*   DNS updates can take **24-48 hours** to propagate.
    
*   Check DNS status using online tools:
    
    *   https://www.whatsmydns.net/
        
    *   https://dnschecker.org/
        

### **6\. Test Website Accessibility**

*   Use a web proxy to bypass ISP cache:
    
    *   https://www.proxysite.com/
        
*   Try opening the website in an **incognito window** or **different network**.
    

### **7\. Contact Support if Issue Persists**

*   If the issue is not resolved after 48 hours, contact your hosting provider with:
    
    *   Screenshot of your DNS settings.
        
    *   Confirmation of name server updates.
        

* * *

**Future Best Practices**
-------------------------

1.  **Keep a record of DNS settings** before making changes.
    
2.  **Use hosting provider’s recommended nameservers** for smooth integration.
    
3.  **Test DNS changes using propagation checkers** before reporting issues.
    
4.  **Allow up to 48 hours for propagation** before assuming an issue.
    
5.  **Clear browser & system cache** to avoid outdated results.
    

For more details, refer to:

*   DNS Propagation Explained: https://www.namecheap.com/support/knowledgebase/article.aspx/9622/10/dns-propagation-explained/
    
*   DNS Troubleshooting: https://support.google.com/domains/answer/3290350?hl=en
    


#### Direct Access Failure
![DNS Error](Screenshot%202025-02-13%20110010.jpg)

#### Access via Proxy
![Proxy Access](Screenshot%202025-02-13%20115931.jpg)


### Network Routing Check
Analyzing network routing can help identify issues. See the routing path diagram below:

![Network Routing](Screenshot%202025-02-13%20120003.jpg)

    
