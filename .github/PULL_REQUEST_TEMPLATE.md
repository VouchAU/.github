## Code review blocking items
Tick to disapprove and request changes with comment suggestions

- [ ] `Readability`
    <details>
     <summary>Rules</summary>
  
     - Confusing variable/function/typescript/file/folder naming
     - Not following our coding standard and convention
     - Not easy to understand the logic
  
    </details>

- [ ] `Single Purpose Principle`
    <details>
     <summary>Rules</summary>
  
     - Function/class/component is too big and having too many responsibilities.
  
    </details>

- [ ] `Reliability`
    <details>
     <summary>Rules</summary>
  
     - Missing error/exception handling
     - Missing clean up resources
     - Corner cases are not covered
  
    </details>
    
- [ ] `Performance`
    <details>
     <summary>Rules</summary>
  
     - Not lazy loaded
     - Not utilize cache
     - Unnecessary `debounce`, `delay`, `setTimeout` and any hardcoded time-based wait
  
    </details>
 
- [ ] `Reusability`
    <details>
     <summary>Rules</summary>
  
     - Against DRY (Do not Repeat Yourself) principle
     - Common utility functions or components are not flexible to be reused
  
    </details>
  
- [ ] `Maintainability`
    <details>
     <summary>Rules</summary>
  
     - Used type casting `as` or `any` to workaround mismatching type
     - Unnecessary module dependency
     - Reused different purpose of functions/components
     - Redundant code or duplicated code.
  
    </details>
  
- [ ] `Testability`
    <details>
     <summary>Rules</summary>
  
     - Missing `data-testid` attribute
     - Missing essential unit test
     - DOM structure is too complicate for e2e test
  
    </details>
  
- [ ] `Configurability`
    <details>
     <summary>Rules</summary>
  
     - Not keeping configurable values in place but inline hardcoded
  
    </details>
  
- [ ] `Security`
    <details>
     <summary>Rules</summary>
  
     - Violate SQL injections or XSS
     - No input data validation
     - Unauthorized actions
  
    </details>
