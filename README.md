 Its Just Practice

 * remove the values from formGroup and declare them as variabes in the component
 * use those variables inside the formGroup
 * use formControl inside template
---
**NOTE**

using formCotrol instead of formControlName will help if we want to validate only one field after a backend goal has been done 

---

* Create custom createPasswordStrength validator file in validators folder ...
* use AbstractControl, ValidationErrors, ValidatorFn
* test cases like hasUpperCase, hasLowerCase, hasNumeric , passwordValid
* return statement is little tricky

<ins>#25-Form Builder</ins>

* To reduce the verbose code we will introduce formBuilder Service
* use formcontrolName in template
