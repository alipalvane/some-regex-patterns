
# Some important regex patterns

Regex patterns for projects



## Review Patterns

- Email Validation
```bash
  const regex = /\w+([\-\.\d]?\w)*@\w+([\-\.\d]?\w)*(\.\w{2,3})+/
```
- Telephone Number Validate
```bash
  const regex = /^0\d{2,3}\-\d{8}$/g;
```
- Phone Number Validate for Iranian simcards (Hamrah-aval, Irancell, Rightel, ..)
```bash
  const regex = /09(1[\d]|2[012]|3[\d]|9[0123])\-\d{3}\-\d{4}/g;
```  
- Decimal Numbers Validate
```bash
  const regex = /^[-+]?(\d*\.)?\d+$/;
```
- Date Validate
```bash
  const regex = /^\d{4}-(0?[1-9]|1[0-2])-(0?[1-9]|[12][0-9]|3[01])$/;
```  




