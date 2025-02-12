If the scrollbar in your **WordPress website** is moving due to **content overflow**, here’s how you can **fix it**:

### **1\. Check CSS for Overflow Issues**

Add this CSS to your theme’s **Additional CSS** section (under Appearance > Customize > Additional CSS):

```css
html, body {
    overflow-x: hidden;
}
```

This prevents horizontal scrolling.

### **2\. Set Max Width for Containers**

If content is overflowing, set a **max-width** for containers:

```css
.container {
    max-width: 100%;
    overflow: hidden;
}
```

### **3\. Inspect Elements in Developer Tools**

*   Right-click on the page and select **Inspect** (or press `F12`).
*   Look for any sections that exceed the screen width.
*   Adjust width or remove extra margins.

### **4\. Disable Unnecessary Plugins**

Some plugins (like sliders, page builders) may cause overflow issues. Try disabling them one by one and check.

### **5\. Check Theme Settings**

*   If using **Elementor or WPBakery**, adjust section width in settings.
*   Set **"Stretch Section"** to **off** in Elementor.

### **6\. Check Custom JavaScript**

If you added custom JavaScript, ensure it’s not modifying the body width.
