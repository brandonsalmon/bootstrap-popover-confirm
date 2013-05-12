Bootstrap Popover Confirm
=========================

Dependencies:
- jQuery
- Twitter Bootstrap

## Getting Started
### 1. Include javascript however you wish.

### 2. Attach the html to an element.
data-popover-confirm: activates the script.

data-title: is the message shown to users.

jQuery Version
    <span
      class='btn btn-success'
      data-title='Confirm order and use selected payment method?'
      data-popover-confirm='Cardonfile.purchase()'>
      Confirm and Purchase
    </span>

Angular JS Directive
    <div 
      class='btn btn-danger' 
      ng-model='record' 
      ng-popover-confirm="scope.deleteRecord()" 
      data-title="Delete this form entry?">
      <i class='icon-remove'></i> Delete
    </div>

Todos:
- Convert to directive for angular js


We will be using an abritrary versioning system.

Current version: ARBVERS.6000
