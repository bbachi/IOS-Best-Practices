# IOS-Best-Practices

These are the best practices for IOS programming.

1. It is good practice to add conformance for each protocol in tis own extention as it helps to keep your code clean and organized.

```
extension ViewController: UITableViewDataSource { 
    // extension implementation
}

extension ViewController: UITableViewDelegate { 
    // extension implementation
}

```
