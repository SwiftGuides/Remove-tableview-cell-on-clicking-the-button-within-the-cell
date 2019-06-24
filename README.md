# Remove-tableview-cell-on-clicking-the-button-within-the-cell
You can remove cell or perform any action using the button which is inside the cell 


## Source Links 

To perform any action on Button Click :- https://stackoverflow.com/a/45242735/10422074

To remove the cell from the tableview listing :- 

```swift
          self.arrayEventlist.remove(at: self.selectedIndexPath)
          self.tableEventList.deleteRows(at: [IndexPath(item: self.selectedIndexPath, section: 0)], with: .left) //or you can just use "self.tableEventList.reloadData()" instead of this line without animation

```
