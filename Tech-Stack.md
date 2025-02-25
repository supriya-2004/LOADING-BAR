# 🚀 Technologies Used:  

### 🟢 HTML (Structure)  
- **`<div class="counter">`** → Displays the percentage counter  
- **`<hr class="loading-bar-front">`** → The animated progress bar  

### 🔵 CSS (Styling & Animation)  
- **`.loading-bar-front { transition: width 0.2s ease-in-out; }`**  
  - Creates a smooth progress bar animation  
- **`.counter { text-shadow: 2px 2px 5px rgba(129, 11, 44, 0.8); }`**  
  - Enhances counter visibility with a shadow effect  

### 🟠 JavaScript (Functionality)  
- **`setTimeout(updateNum, 20);`**  
  - Updates progress every **20ms** for a smooth animation  
- **`barEl.style.width = idx + "%";`**  
  - Dynamically adjusts the progress bar width based on the percentage  
