# 🎥 Video 5 – Structure of a C Program

---

## 🧱 Standard Sections of a C Program

1. 📝 **Documentation Section**  
   - Used for adding comments.  
   - Includes author info, date, description, etc.  
   - Syntax:  
     - `//` for single-line comments  
     - `/* ... */` for multi-line comments

2. 🔗 **Link Section**  
   - Includes necessary header files using `#include`.  
   - Example: `#include <stdio.h>` enables use of `printf()`, `scanf()`, etc.

3. 🔠 **Definition Section**  
   - Defines symbolic constants using `#define`.  
   - Example: `#define PI 3.14`

4. 🌐 **Global Declaration Section**  
   - Declare global variables or function prototypes.  
   - These can be accessed from anywhere in the program.  
   - Example:  
     ```c
     float r;  
     void sum();
     ```

5. 🎯 **Main Function Section**  
   - Program execution starts from `main()`.  
   - Contains core logic of the program.

6. 🔧 **Sub-program Section**  
   - Contains user-defined functions.  
   - Helps make the code modular and reusable.

---

## ✅ Example: Full C Program

```c
// Program to calculate area of a circle
// Author: Prashant

#include <stdio.h>
#define PI 3.14

float r, area;

int main() {
    printf("Enter radius: ");
    scanf("%f", &r);

    area = PI * r * r;

    printf("Area of circle: %.2f\n", area);

    return 0;
}
