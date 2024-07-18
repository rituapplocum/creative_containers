
# Creative Container
Let's you customise your existing container

## Installation

1. Add the latest version of package to your pybspec.yaml file
```yaml
dependencies:
  new_creative_containers: ^0.0.2
```
2. Import the package and use it in your flutter app.
```dart
import 'package:new_creative_containers/new_creative_containers.dart';
```


## Example
There are a number of properties that you can modify:

- height
- width
- title
- subtitle
- gradient (color1 and color2)

<hr>

<table>
<tr>
<td>

```dart
class GradientScreen extends StatelessWidget {  
  const GradientScreen({Key? key}) : super(key: key);

  @override  
  Widget build(BuildContext context) {  
    return Scaffold(  
      body: Center(  
        child: const CreativeContainer(  
        title: 'Hello World',  
        color1: Colors.lightGreenAccent,  
        color2: Colors.lightBlue,  
        subtitle: 'This is a new package',  
        ),  
      ),  
    );  
  }  
}
```


</td>
<td>
<img  src="https://user-images.githubusercontent.com/53579386/126896556-911d4778-04cd-49bf-b32a-01a6eb3b0155.jpeg"  alt="">
</td>
</tr>
</table>

## Next Goals

- [x] Add onTap for functions.
  Now, you can specify the onTap and specify a function.

- [x] Change font and color style for text.
  Change color by specifying `textcolor` and `subtitlecolor` properties.

- [ ] Add more containers to the package.
