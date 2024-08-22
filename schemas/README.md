### **Summary of Key Upgrades**  
Date: 08/22/2024 
Original version located: `v3.0/smartapi_schema.json`

1. **Schema Version**
   - **Upgraded** from JSON Schema Draft-04 to Draft 2020-12 for better compatibility with modern standards.

2. **Definitions Location**
   - **Changed** from `#/definitions/...` to `#/$defs/...` to align with the latest JSON Schema conventions.

3. **Contact Roles**
   - **Added** a new role `"document creator"` to better document contributors.

4. **Server Maturity Levels**
   - **Added** `"testing"` as a new maturity level for better server environment categorization.

5. **Paths Object Flexibility**
   - **Removed** the requirement for the `summary` field, providing more flexibility in operation documentation.

6. **Response Value Type Validation**
   - **Enhanced** validation logic to allow flexibility with `path`/`x-path` and `valueType`/`x-valueType`.

7. **Improved Flexibility**
   - **Introduced** more flexible validation using `allOf` and `anyOf` constructs, allowing for adaptable data structures.
