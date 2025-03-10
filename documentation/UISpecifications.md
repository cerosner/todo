# UI Specifications

## 01.00 Home Page
### 01.01 Input Section
- Text Input Bar
  01. Allows users to type a new list item.
  02. Placeholder text: "Enter a new item..."
  03. Prevents adding an empty item (disable button if input is empty).
- Add Button
  01. Clicking adds text in the input bar as a new list item.
  02. Button is disabled if the input field is empty.
### 01.02 List Items Section
- List Item Elements
  01. Each list item consists of:
  02. Text (Clickable to open update confirmation)
  03. Update Icon (🖊️)
  04. Trash Icon (🗑️)
### 01.03 Update Confirmation Dialog
- Trigger: Clicking on the list item text or update icon.
- Dialog Options:
  ✅ Confirm Update: Marks the list item as DONE (applies visual changes).
  ❌ Cancel: Closes the dialog without changes.
### 01.04 Delete Confirmation Dialog
Trigger: Clicking the trash icon.
Dialog Options:
  ✅ Confirm Delete: Removes the item from the list.
  ❌ Cancel: Closes the dialog without changes.