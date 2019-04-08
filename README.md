# viper template for Generamba
my own viper gen files

## How to use
You need some BaseClasses
1. DIResolver
2. BaseWireFrame
3. BaseInteractor
4. BasePresenter
5. BaseViewController: UIViewController

### DIResolver
```swift
class DIResolver {

    init() { }

}
```

### BaseWireFrame
```swift
class BaseWireFrame {

    let resolver: DIResolver

    init(resolver: DIResolver) {
        self.resolver = resolver
    }
}
```

### BaseInteractor
```swift
class BaseInteractor { }
```

### BasePresenter
```swift
class BasePresenter { }
```

### BaseViewController
```swift
class BaseViewController: UIViewController {

    override func viewDidLoad() {
        super.viewDidLoad()

    }
}
```