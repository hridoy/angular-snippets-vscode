
# Angular Snippets

**Now Updated for 4.3.5 release**

This extension for Visual Studio Code adds snippets for Angular Framework. More Snippets will be coming soon just release.


## Contributors
[![Hridoy](https://avatars.githubusercontent.com/hridoy?s=100)<br /><sub>Hridoy</sub>](http://github.com/hridoy)<br />
See the [CHANGELOG](https://github.com/hridoy/backbone-js-snippets-vscode/master/CHANGELOG.md) for the latest changes

Features Snippets
=================
![Angular Core](https://github.com/hridoy/angular-snippets-vscode/raw/master/img/angular-ts.png)&nbsp;![Angular Bug](https://github.com/hridoy/angular-snippets-vscode/raw/master/img/angular-bug.png)&nbsp;![Angular rxjs](https://github.com/hridoy/angular-snippets-vscode/raw/master/img/angular-rxjs.png)&nbsp;&nbsp;![Angular Material](https://github.com/hridoy/angular-snippets-vscode/raw/master/img/material.png)&nbsp;<br />&nbsp;<sub>**Angular Core**</sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<sub>**Angular Bug**</sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<sub>**Angular rxjs**</sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<sub>**Angular Material**</sub> <br />

![Angular Native](https://github.com/hridoy/angular-snippets-vscode/raw/master/img/angular-native.png)&nbsp;![Angular Meteor](https://github.com/hridoy/angular-snippets-vscode/raw/master/img/angular-meteor.png)&nbsp;&nbsp;&nbsp;&nbsp;![Angular Bootstrap](https://github.com/hridoy/angular-snippets-vscode/raw/master/img/bootstrap.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Angular Flex](https://github.com/hridoy/angular-snippets-vscode/raw/master/img/flex.png)&nbsp;<br />&nbsp;<sub>**Angular Native**</sub>&nbsp;&nbsp;&nbsp;<sub>**Angular Meteor**</sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<sub>**Angular Bootstrap**</sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<sub>**Angular Flex**</sub>


# Usage

### Angular Core

 1. **ng-** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  `default snippet style`
 2. **ng-c**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `stand for ng-component`
 3. **ng-d** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`stand for ng-directive`
 4. **ng-m**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`stand for ng-module`  
 5. **ng-s** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`stand for ng-service`
 6. **ng-r** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`stand for ng-route`
 7. **ng-p** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`stand for ng-pipe`

| **Prefix** | **Description** |
|---|---|
| **ng-** | |
| `ng-afterContentChecked` | Lifecycle hook: Called after every check of the component's or directive's content |
| `ng-afterContentInit` | Lifecycle hook: Called after ngOnInit when the component's or directive's content has been initialized |
| `ng-afterViewChecked` | Lifecycle hook: Called after every check of the component's view. Applies to components only |
| `ng-afterViewInit` | Lifecycle hook: Called after ngAfterContentInit when the component's view has been initialized |
| `ng-binding-oneway` | Property: [property]=\"expression\" |
| `ng-binding-twoway` | Two-way data binding with the NgModel |
| `ng-bootstraping` | Bootstraping example |
| `ng-button` | A button element with a click event |
| `ng-button-submit` | A submit button element with a click event |
| `ng-class` | CSS class |
| `ng-click` | Click event |
| ng-conf | The World's Original Angular Conference |
| ng-controller | Use component instead. |
| ng-doCheck | Lifecycle hook: Called every time that the input properties of a component or a directive are checked |
| ng-event | Event: (event) = \"onEvent()\" |
| ng-filter | For performance reasons, no comparable pipe exists in Angular 2. Do all your filtering in the component. If you need the same filtering code in several templates, consider building a custom pipe. |
| ng-for | For-loop directive |
| ng-for-index | For-loop directive with index |
| ng-for-li | For-loop directive with li element |
| ng-for-trackBy | For-loop directive with trackBy |
| ng-hide | Usage: Bind to the hidden property. |
| ng-href | Usage: Bind to the href property. |
| ng-http-get | Http observable get request |
| ng-http-get-post | Http observable get & post request |
| ng-httpClient-get | HttpClient observable get request |
| ng-if | If directive: *ngIf=\"expression\" |
| ng-if-else | v4: If else directive: *ngIf=\"expression; else\" |
| ng-if-then-else | v4: If then else directive: *ngIf=\"expression; then; else\" |
| ng-import | import module or component from path; |
| ng-input | Class Input Property |
| ng-interpolation | Interpolation: {{ interpolation }} |
| ng-ngOnChanges | Lifecycle hook: Called before any other lifecycle hook |
| ng-onDestroy | Lifecycle hook: Called before the instance is destroyed |
| ng-onInit | Lifecycle hook: Called after the constructor |
| ng-orderBy | For performance reasons, no comparable pipe exists in Angular 2. Instead, use component code to order or sort results. If you need the same ordering or sorting code in several templates, consider building a custom pipe. |
| ng-output | Class Output Event |
| ng-property | Property: [property]=\"expression\" |
| ng-repeat | Use ngFor instead. |


| **Prefix** | **Description** |
|---|---|
| **ng-c** | |
| `ng-component` | Component with template and style urls |
| `ng-component-inline` | Component with inline Template and Styles |

| **Prefix** | **Description** |
|---|---|
| **ng-d** | |
| `ng-directive` | Directive template |
| `ng-directive-attribute` | Attribute directive |
| `ng-directive-css` | CSS directive |


| **Prefix** | **Description** |
|---|---|
| **ng-m** | |
| `ng-module` | Feature Module |
| `ng-module-root` | App root module |

| **Prefix** | **Description** |
|---|---|
| **ng-s** | |
| `ng-s` | Basic service |
| `ng-s-appmodule` | Routes to include in root module |


| **Prefix** | **Description** |
|---|---|
| **ng-r** | |
| `ng-r` | Router template |
| `ng-r-appmodule` | Routes to include in root module |
| `ng-r-attribute` | Router link |
| `ng-r-featuremodule` | Routes to include in a feature module 
| `ng-r-link` | Router link |
| `ng-r-linkActive` | Router active link |
| `ng-r-outlet` | Router outlet element |
| `ng-r-outlet-name` | Router outlet element with name |
| `ng-r-guard-canactivate` | CanActivate Guard Route |
| `ng-r-guard-canactivatechild` | CanActivateChild Route |
| `ng-r-guard-candeactivate` | CanDeactivate Guard Route |
| `ng-r-guard-canload` | CanLoad Guard Route |
| `ng-r-guard-resolve` | Resolve Guard Route |

| ** ** | ** ** |
|---|---|
| **ng-p** | |
| `ng-pipe` | Pipe template |
| `ng-pipe-async` | Async pipe - Usage: observable_or_promise_expression &#x7c; async |
| `ng-pipe-currency` | Currency pipe - Usage: money &#x7c; currency:'EUR' |
| `ng-pipe-date` | Date pipe - Default format: 09/15/1971 |
| `ng-pipe-date-custom` | Date pipe - Format: \"MM/dd/yy\" = 09/15/71 |
| `ng-pipe-date-full` | Full date pipe - Format: Wednesday, September 15, 1971 |
| `ng-pipe-date-short` | Short date pipe - Format: 09/15/1971 |
| `ng-pipe-decimal` | Decimal pipe - Usage: number_expression &#x7c; decimal[:digitInfo] |
| `ng-pipe-example` | Angular pipe example |
| `ng-pipe-json` | Json pipe - Usage: object &#x7c; json |
| `ng-pipe-lowercase` | Lowercase pipe |
| `ng-pipe-percent` | Percent pipe - Usage: number_expression &#x7c; percent[:digitInfo] |
| `ng-pipe-slice` | Slice pipe - Usage: array_or_string_expression &#x7c; slice:start[:end] |
| `ng-pipe-titlecase` | v4: Titlecase pipe |
| `ng-pipe-uppercase` | Uppercase pipe |



### Angular rxjs
| **Prefix** | **Description** |
|---|---|
| **ng-rxjs** | |
| `ng-rx-action` | ngRx Single action |
| `ng-rx-actions` | ngRx Actions class |
| `ng-rx-module` | ngRx Root Module |
| `ng-rx-reducer` | ngRx Reducer |
|`ng-rx-util ` | ngRx Util|

### Angular Bug
| **Prefix** | **Description** |
|---|---|
| **ng-test** | |
|`ng-test-component-async` | ng-test-directive |
|`ng-test-component-synchronous` | Test component|
|`ng-test-directive ` | Test Directive|
|`ng-test-service ` | Test service|
|`ng-test-pipe ` | Test pipe|
| `ng-debug` | pre obj pipe json |
| `ng-debug-async` | pre obj pipe async pipe json |



### Angular Material

| **ng-md Prefix** | **Description** |
|---|---|
| **Autocomplete** | |
|`md-autocomplete:full` | all autocomplete options|
|`md-autocomplete:tpl` | all autocomplete options with custom template|
| **AutoFocus** | |
|`md-autofocus` | inline autofocus option|
| **Button** | |
|`md-button:standard` | standard button no options|
|`md-button:full` | standard button with all options|
|`md-button:icon` | standard button with icon and option mini and fab|
| **Bottom Sheet** | |
|`md-bottom-sheet:standard` | standard bottom sheet |
|`md-bottom-sheet:list` | bottom sheet list template |
|`md-bottom-sheet:grid` | bottom sheet grid template |
| **Card** | |
|`md-card:standard` | standard card|
|`md-card:Full` | full options card|
| **Checkbox** | |
|`md-checkbox:full` | checkbox full options|
|`md-checkbox:simple` | checkbox minimal options|
| **Chip** | |
|`md-chip:single` |  single md-chip item|
|`md-chip-remove` |  button to remove chip|
| **Datepicker** | |
|`md-dialog:full` |  date picker with full options|
|`md-datepicker:simple` |  datepicker with minimal options |
| **Dialog** | |
|`Dialog:full` |  datepicker with full options |
| **Divider** | |
|`md-divider` |  simple divider|
| **Fab Speed Dial** | |
|`md-fab-speed-dial` |  fab speed dial|
| **Fab Toolbar** | |
|`md-fab-toolbar` |  fab toolbar|
| **Grid** | |
|`md-grid-list-tile:single` |  single grid list tile|
|`md-grid-list-tile:footer` |  single grid list tile with footer|
|`md-grid-list:standard` |  grid list with options|
| **Menu** | |
|`md-menu:full` |  full options and template for menu|
|`md-menu:simple` |  simple template for menu|
| **Layout** | |
|`md-layout` |  the md-content tag with layout options|
| **Ink Ripple** | |
|`md-ink-ripple` | md-ink-ripple options|
| **Inputs** | |
|`md-input-container:single` | single md container. Wrapper for other input elements|
|`md-input:single` | standard input with options|
|`md-select` | select item with options|
|`ng-messages:wrapper` | the wrapper for ng messages|
|`ng-message:single` | single ng-message element|
| **List** | |
|`md-list:single` | single list item |
|`md-list:standard` | standard list |
| **Progess** | |
|`md-progress-circle` | circular progress loader|
|`md-progress-linear` | md-progress-linear|
| **Radio Button** | |
|`md-radio-button:standard` |standard radio button|
|`md-radio-button:full` | radio button full options|
|`md-radio-group` | radio button group|
| **Slider** | |
|`md-slider:standard` | slider|
| **Swtich** | |
|`md-switch:full` | switch full options|
| **Subheader** | |
|`md-subheader` | subheader|
| **Swipe** | |
|`md-swipe` | swipe options|
| **Tabs** | |
|`md-tab:label` | tab label|
|`md-tab:body` | tab body|
|`md-tab-item:full` | full tabs options|
|`md-tab:simple` | simple tab template|
|`md-tab:full` | full tab template|
| **ToolTip** | |
|`md-tooltip` | tooltip full options|
| **Virtual Repeat** | |
|`md-virtual-repeat` | virtual repeat for lists|
| **Whiteframe** | |
|`md-whiteframe` | md-whiteframe options|


### Angular Flex
| **Prefix** | **Description** |
|---|---|
| **ng-f** | |
| `ng-fx-col` | Flex Layout Column |
| `ng-fx-col-reverse` | Flex Layout Reverse Column |
| `ng-fx-import` | Flex Layout Import |
| `ng-fx-item` | Flex Layout Item |
| `ng-fx-item-align` | Flex Layout Item with fxFlexAlign |
| `ng-fx-item-fill` | Flex Layout Item with fxFlexFill |
| `ng-fx-item-offset` | Flex Layout Item with fxFlexOffset |
| `ng-fx-item-order` | Flex Layout Item with fxFlexOrder |
| `ng-fx-layout` | Flex Layout Property |
| `ng-fx-layout-align` | Flex Layout Align Property |
| `ng-fx-layout-gap` | Flex Layout Gap Property |
| `ng-fx-row` | Flex Layout Row |
| `ng-fx-row`-reverse | Flex Layout Reverse Row |


Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

## Installation


1. Install Visual Studio Code 1.10.0 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Choose the extension
6. Reload Visual Studio Code