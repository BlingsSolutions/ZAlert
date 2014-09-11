ZAlert
======

show alert and action sheet easier way in swift


##alert
```
ZAlert.alert("alert title", message: "alert message")
.action("1st action", style: .Cancel, handler: { (action) -> () in
            println("1st")
        })
.action("2nd action", style: .Default, handler: { (action) -> () in
            println("2nd")
        })
.action("3rd action", style: .Destructive, handler: { (action) -> () in
            println("3rd")
        })
.present(self, animated: true, completion: { () -> Void in
            println("completion")
        })
```

##action sheet
```
ZAlert.actionSheet("alert title", message: "alert message")
.action("1st action", style: .Cancel, handler: { (action) -> () in
            println("1st")
        })
.action("2nd action", style: .Default, handler: { (action) -> () in
            println("2nd")
        })
.action("3rd action", style: .Destructive, handler: { (action) -> () in
            println("3rd")
        })
.present(self, animated: true, completion: { () -> Void in
            println("completion")
        })
```