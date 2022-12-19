# Reading: `<Login />` and `<Auth />`

## Reading

### [What is Role Based Access Control (RBAC)?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

1. What is Role Based Access Control (RBAC)?

Role-Based or Attribute-Based Access Control is better model for authorization management? Learn best practice hybrid RBAC / ABAC / PBAC approaches. Download Free Whitepaper Here! ServiceNow. Microsoft. Services: Password Management, Role Mining.

2. Share some an example of RBAC including all possible CRUD operations and correlating roles.

- Admin: GET, POST, PUT, DELETE
- Editor: GET, PUT
- Author: GET, POST
- User: GET

3. What are the Benefits of RBAC?

- Improving operational efficiency
- Enhancing compliance
- Giving administrators increased visibility
- Reducing cost
- Decreasing risk of breaches and data leakage

Compare and Contrast the following two Libraries and the following questions. Yes, they are similarly named.

### [react-cookie library](https://www.npmjs.com/package/react-cookie)

### [react-cookies component](https://www.npmjs.com/package/react-cookies)

1. Describe some `react-cookie` features.

   - Set the user cookies
   - Access and modify cookies using React hooks.
   - Let you optionally specify a list of cookie names your component depend on or that should trigger a re-render. If unspecified, it will render on every cookie change.

2. Describe some `react-cookies` features.

   - Load the cookie value
   - Load all available cookies
   - Find all the cookies with a name that match the regex.
   - Set a cookie.

3. Which library would you prefer would you prefer? Why?

   I think I will use react-cookie because I like the documentation more.
