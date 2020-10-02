# listview_demo

A Flutter project.

## Navigate and pass data to the detail screen

With a DetailScreen in place, you’re ready to perform the Navigation. In this example, navigate to the DetailScreen when a user taps a todo in the list. Pass the todo to the DetailScreen.

To capture the user’s tap in the TodosScreen, write an onTap() callback for the ListTile widget. Within the onTap() callback, use the Navigator.push() method.
