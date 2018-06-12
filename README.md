# IOS-Best-Practices

These are the best practices for IOS programming.

1. It is good practice to add conformance for each protocol in its own extention as it helps to keep your code clean and organized.

```
extension ViewController: UITableViewDataSource { 
    // extension implementation
}

extension ViewController: UITableViewDelegate { 
    // extension implementation
}

```
  
  2. it's a good practice to use computed properties because you have detailed control over the exposed properties and it is very easy to chnage the underlying code. it ensures that you dont have to rewrite the existing code that access these properties and also it prevents you from writing somethig such as contact.contact.givenName.
  
  ```
  var givenName: String { 
     return contact.givenName 
   } 
   
   var familyName: String { 
      return contact.familyName 
   } 
  
  ```
