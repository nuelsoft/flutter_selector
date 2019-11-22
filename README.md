# flutter_selector
Flutter widget for that Multi-Option idea

# Usage
- Clone the repository. To clone run <code>git clone https://github.com/nuelsoft/flutter_selector.git</code>
- Add the folder to your flutter project lib folder.
- Import it by adding this to your code, where necessary. <code>import 'flutter_selector/custom_selector.dart';</code>

# Example

<pre>
import 'flutter_selector/custom_selector.dart';
...

List<String> items = ["Onion", "Tomatoe", "Carrot", "Milk"];
String title = "Grocery List"
int selectedIndex = 0;

void onItemSelected(index){
  setState((){
    selectedIndex = i;
  });
}
...

Selector(
    items: items,
    selectedIndex: selectedIndex,
    title: title,
    onSelect: onItemSelected)

...
</pre>

# Have Fun
