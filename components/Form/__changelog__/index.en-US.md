## 2.66.0

2025-04-03

### 🐛 BugFix

- Fixed the "Form" component dependcies execution timing bug. (Only when the value of the field specified by dependencies changes, the validation of Form.Item itself is triggered)([#2869](https://github.com/arco-design/arco-design/pull/2869))

## 2.65.0

2024-11-29

### 🐛 BugFix

- Fixed the bug that `flat` syntax in `Form` component is not compatible with lower version browsers([#2881](https://github.com/arco-design/arco-design/pull/2881))

## 2.62.1

2024-05-17

### 🐛 BugFix

- Fix the bug that the verification status appears validating when rules are not set in `Form.Item`([#2676](https://github.com/arco-design/arco-design/pull/2676))

## 2.61.3

2024-04-12

### 🐛 BugFix

- Fix `Form` rtl view style issue([#2635](https://github.com/arco-design/arco-design/pull/2635))
- Fix the bug that `Form.useFormContext` component `isSubmitting` is incorrect.([#2631](https://github.com/arco-design/arco-design/pull/2631))
- Fixed an error issue when `Form` component rules is not set and validate method validateOnly is true([#2620](https://github.com/arco-design/arco-design/pull/2620))

## 2.61.0

2024-03-15

### 🐛 BugFix

- Fixed the bug of internal method call error caused by `Form.useFormContext` not being used under `Form` component.([#2590](https://github.com/arco-design/arco-design/pull/2590))

## 2.60.3

2024-03-08

### 🐛 BugFix

- Fixed the bug of internal method call error caused by `Form.useFormContext` not being used under `Form` component.([#2574](https://github.com/arco-design/arco-design/pull/2574))

## 2.59.0

2024-01-19

### 🐛 BugFix

- Fixed a bug that caused all form items to be reset when the `resetFields` method of the `Form` component passed in non-string/array type parameters.([#2505](https://github.com/arco-design/arco-design/pull/2505))

## 2.56.2

2023-12-01

### 💎 Enhancement

- Optimize performance when field value is a large data array in a Form([#2397](https://github.com/arco-design/arco-design/pull/2397))

## 2.56.0

2023-11-17

### 🆕 Feature

- The `Form` component supports setting `validateOnly` for silent verification without UI performance.([#2366](https://github.com/arco-design/arco-design/pull/2366))

## 2.54.3

2023-10-26

### 🐛 BugFix

- Fixed the UI problem of displaying the verification success style when the `Form` component is verified (this bug was introduced in `2.54.2`).([#2312](https://github.com/arco-design/arco-design/pull/2312) )

## 2.54.2

2023-10-20

### 🐛 BugFix

- Fixed the bug where the `Form` component's style was lost in the `validating` state.([#2299](https://github.com/arco-design/arco-design/pull/2299) )
- Fixed the issue where `Form.useFormContext` status update caused component lag.([#2299](https://github.com/arco-design/arco-design/pull/2299) )

## 2.52.2

2023-09-01

### 🐛 BugFix

- Fix the bug that `Form.Item` component's `disabled` property overrides the child node's `disabled` property.([#2204](https://github.com/arco-design/arco-design/pull/2204))

## 2.46.3

2023-04-07

### 🐛 BugFix

- Fixed a bug where 'form.list' 'onChange' of directly wrapped child components was incorrectly triggered when dynamically adding or subtracting Form items.([#1898](https://github.com/arco-design/arco-design/pull/1898))

## 2.46.2

2023-03-31

### 💎 Enhancement

- Optimize the problem that when `Form.useFormContext` is not used in `<Form>`, there will be a page error and cause a white screen.([#1884](https://github.com/arco-design/arco-design/pull/1884))

## 2.46.1

2023-03-24

### 🐛 BugFix

- Fix the bug that the `Form.List` component behaves abnormally when the user executes the `add/remove/move` method `memo`([#1868](https://github.com/arco-design/arco-design/pull/1868))

## 2.46.0

2023-03-17

### 🆕 Feature

- `Form.List` supports validation rules([#1790](https://github.com/arco-design/arco-design/pull/1790))

## 2.45.1

2023-03-01

### 🐛 BugFix

- Fix the bug that the `value` reference address of the `Form.Item` component injected into the custom form control changes when `rerender`.([#1815](https://github.com/arco-design/arco-design/pull/1815))

## 2.44.0

2023-01-13

### 🆕 Feature

- `Form` supports to get the verification information of the specified field through `useFormState`, verification status([#1723](https://github.com/arco-design/arco-design/pull/1723))

## 2.43.0

2022-12-23

### 🆕 Feature

- `Form.Item` supports setting tooltip via `tooltip` property.([#1665](https://github.com/arco-design/arco-design/pull/1665))

## 2.42.2

2022-12-09

### 💎 Enhancement

- Optimize the situation where the `Form.List` component is completely re-rendered when the form item data is updated through the Form API, causing the page to freeze.([#1638](https://github.com/arco-design/arco-design/pull/1638))

## 2.41.0

2022-10-28

### 🆕 Feature

- The `colon` property of the `Form` component supports passing a `ReactNode`.([#1455](https://github.com/arco-design/arco-design/pull/1455))

### 🐛 BugFix

- Fixed a bug where the `shouldUpdate` property of the `Form.Item` component did not take effect when resetting the form item.([#1462](https://github.com/arco-design/arco-design/pull/1462))

## 2.40.0

2022-09-16

### 💎 Enhancement

- Optimize the built-in validation information template of the `Form` component([#1398](https://github.com/arco-design/arco-design/pull/1398))

### 🆕 Feature

- `Form.Item` supports the `dependencies` property([#1397](https://github.com/arco-design/arco-design/pull/1397))

### 🐛 BugFix

- Fix the bug that the return value of `Form.useWatch` is not updated in time when `field` changes([#1400](https://github.com/arco-design/arco-design/pull/1400))

## 2.38.1

2022-08-05

### 🐛 BugFix

- Fix the bug that form value won't update when the parameter of `setFieldsValue` is empty array or empty object.([#1186](https://github.com/arco-design/arco-design/pull/1186))

## 2.37.0

2022-07-08

### 🆕 Feature

- `Form.useWatch` supports watching multiple field values.([#1034](https://github.com/arco-design/arco-design/pull/1034))

### 🐛 BugFix

- Fixed `Form.useWatch` when monitoring a form control with an initial value but not mounted, the return value has a change of `initial value => undefined`, causing the component to update.([#1034](https://github.com/arco-design/arco-design/pull/1034))
- Fixed bug where the `onChange` method of the `Form.Item` component injected into a custom form control would be redeclared every time it renders.([#1102](https://github.com/arco-design/arco-design/pull/1102))

## 2.36.1

2022-07-01

### 🐛 BugFix

- Fix the problem that the order of form items is adjusted under `Form.List`, and the verification status may be displayed in disorder([#1077](https://github.com/arco-design/arco-design/pull/1077))

## 2.36.0

2022-06-24

### 🐛 BugFix

- Fixed a bug where the validation state of other form items was lost when the `Form.List` component was removed from the form item.([#1046](https://github.com/arco-design/arco-design/pull/1046))
- Fixed a bug where the `form.clearFields()` method did not clear the validation state.([#1046](https://github.com/arco-design/arco-design/pull/1046))

## 2.35.0

2022-06-10

### 🐛 BugFix

- Fixed a bug where `Form.useWatch` returned a non-latest value when adding/deleting rows in `Form.List`.([#955](https://github.com/arco-design/arco-design/pull/955))

## 2.34.0

2022-05-27

### 🐛 BugFix

- Fix the bug that the `warning` state of the form control is not cleared when the `Form` component sets the `warning` to `null` through `setFields`.([#930](https://github.com/arco-design/arco-design/pull/930))

## 2.33.1

2022-05-20

### 🐛 BugFix

- Modifications to the return value of `getFieldValue` should not affect the original data inside the `Form`([#869](https://github.com/arco-design/arco-design/pull/869))

### 🆎 TypeScript

- Complete `children` property type in `FormItemProps`, compatible with React 18([#874](https://github.com/arco-design/arco-design/pull/874))

## 2.33.0

2022-05-13

### 🆕 Feature

- The `Form` component supports `Form.useWatch`.([#864](https://github.com/arco-design/arco-design/pull/864))
- The `Form` component supports `Form.useFormContext`.([#864](https://github.com/arco-design/arco-design/pull/864))

## 2.32.2

2022-04-29

### 🐛 BugFix

- Fix the bug that the `Form` component has controlled invalidation of form items in React 18 strict mode.([#823](https://github.com/arco-design/arco-design/pull/823))

## 2.32.0

2022-04-15

### 🆕 Feature

- The `Form` component supports setting the validation message template through the `validateMessages` property([#773](https://github.com/arco-design/arco-design/pull/773))

### 🐛 BugFix

- Fix the bug that `onChange` is not called when the form control wrapped by `Form.Item` is returned by the function type `children`.([#760](https://github.com/arco-design/arco-design/pull/760))

## 2.30.2

2022-03-18

### 🐛 BugFix

- Fix a bug where `Form.provider` causes console warning.([#646](https://github.com/arco-design/arco-design/pull/646))

## 2.30.0

2022-03-04

### 🆕 Feature

- The `Form` component supports multiple form data management through the `Form.Provider` component.([#607](https://github.com/arco-design/arco-design/pull/607))

## 2.29.2

2022-02-25

### 🐛 BugFix

- Fixed the bug that the `form` parameter passed to the `Form.useForm` method did not take effect.([#577](https://github.com/arco-design/arco-design/pull/577))

## 2.29.0

2022-02-11

### 🆕 Feature

- `Form.Item` supports hiding form items via the `hidden` property([#509](https://github.com/arco-design/arco-design/pull/509))
- Support for clearing field values via the `clearFields` method([#509](https://github.com/arco-design/arco-design/pull/509))

## 2.28.1

2022-01-14

### 🐛 BugFix

- Fixed the bug where the `scrollToFirstError` property of the `Form` component did not work on form items with `noStyle` set.([#444](https://github.com/arco-design/arco-design/pull/444))
- Fixed a style issue where the form item jittered when the validation failed when the `Form` component had a `mini` size.([#438](https://github.com/arco-design/arco-design/pull/438))

## 2.28.0

2022-01-07

### 🆕 Feature

- The `Form` component supports the global setting of the triggering timing of the verification rule through the `validateTrigger` property([#400](https://github.com/arco-design/arco-design/pull/400))

## 2.27.0

2021-12-17

### 💅 Style

- Fix the problem that there is no validated style when `InputTag` is used in `Form.Item` with `validateStatus`.([#330](https://github.com/arco-design/arco-design/pull/330))

## 2.26.1

2021-12-07

### 🐛 BugFix

- Fix the bug that the `warning` style of the `Form` component is shown when the teaching experience is passed.([#282](https://github.com/arco-design/arco-design/pull/282))

## 2.25.0

2021-11-19

### 🆕 Feature

- `Form` support to set the `validateTrigger` property in `rules` to specify that the rule will be executed when a specific event is triggered.([#190](https://github.com/arco-design/arco-design/pull/190))
- `Form` support setting the `validateLevel` property in `rules` to specify that only the `warning` status is displayed when the rule validation fails, and the form submission is not blocked.([#190](https://github.com/arco-design/arco-design/pull/190))
- The `Form` component `rule.message` supports the use of `ReactNode`.([#185](https://github.com/arco-design/arco-design/pull/185))

## 2.24.0

2021-11-05

### 🐛 BugFix

- Adjust the TS definition of the `Form` component as `FormHTMLAttributes`([#118](https://github.com/arco-design/arco-design/pull/118))
- Fix the `bug` that the `Form.List` component creates form items through the `add()` method, and the default value passed in does not take effect when the form item has an `initialValue`.([#118](https://github.com/arco-design/arco-design/pull/118))

## 2.23.0

2021-09-27

### 🆕 Feature

- Specify how to handle the value when the child node triggers the `onChange` event.
- The `Form` component supports conversion of the field values ​​passed to the control through the `formatter` property.

### 🐛 BugFix

- Fixed bug where 'add' method does not take effect when setting initial values for `Form. List`

## 2.22.0

2021-09-10

### 💎 Optimization

-  When the `add` method of `Form.List` receives the event object as a parameter, it will prompt in the console.

### 🆕 Feature

- `Form.List` supports setting the initial value through the `initialValue` property.

### 🐛 BugFix

- Fix the bug of rendering errors when `Form.Item` passes in children as an empty string.

## 2.21.1

2021-08-27

### 🐛 BugFix

-  Fix the bug that `onChange` can't be fired when to add or remove an item in `Form.List`.

## 2.21.0

2021-08-20

### 🆕 Feature

- The `Form` component supports the `onSubmitFailed` property, which is called when the validation fails when submitting the form.

### 🆎 TypeScript

-  Optimize `Form.setFieldsValue` ts definition

## 2.20.1

2021-08-06

### 🐛 Bugfix

- Fix the bug that the `Form` component does not receive the native `dom` property.
- Fix the bug that the `Form.Item` component does not receive the native `dom` property.

## 2.20.0

2021-07-30

### 🆎 TypeScript

- Optimize the TS definition of `scrollIntoViewOptions` of `scrollToFirstError` property of `Form` component.

## 2.19.0

2021-07-16

### 💎 Optimization

- Optimize the keyboard accessibility of the `Form` form, click the label label to focus on the form item.

### 🆕 Feature

- The `Form` component `scrollIntoFirstError` supports passing in `scrollIntoViewOptions`.

### 🐛 Bugfix

- Fix the problem that the `move` method of the `Form.List` component moves the form items in the wrong position.
- Fix the problem that `setFieldsValue` does not take effect when the `Form` component form linkage cooperates with nested fields and sets the initial value of the form item.

## 2.18.2

2021-07-09

### 🆎 TypeScript

- Fix the bug that the parameter definition of the `add` method of the `Form.List` component.



## 2.18.0

2021-07-02

### 🐛 Bugfix

- When `Form.List` is nested with `Form.List`, the order of `FormItem` is adjusted by `move` method, and the UI display is not updated according to `value`.



## 2.16.1

2021-06-04

### 🆎 TypeScript

- Fix the problem that the `Form` component type is deduced to `any`.


## 2.16.0

2021-05-28

### 🐛 Bugfix

- Fix the problem that the verification state of the verified control is reset when the `Form.List` component executes the `add` method.

### 🆎 TypeScript

- Export the `FormInstance` definition of the `Form` component.

## 2.15.3

2021-05-21

### 💎 Optimization

- `Form` prevents the `onSubmit` event from bubbling.



### 🐛 Bugfix

- Fixed a bug that reported errors in `Form` when `Select` set `labelInValue`.

## 2.14.0

2021-04-09

### 🆕 Feature

- Optimize the rendering logic of `Form.List` so that the entire Form.List will not be rendered when the child components change.



### 🐛 Bugfix

- Fix the bug that the priority of `initialValue` of `Form.Item` is lower than the priority of `initialValues` on `Form`.

## 2.13.2

2021-04-01

### 🐛 Bugfix

- Fixed the bug that the `onValuesChange` was not triggered when the `resetFieldsValue` method was called when the initial value of the `Form` component was not set.



## 2.12.0

2021-03-19

### 🐛 Bugfix

- Fix the problem that the priority of `initialValue` of the `Form` component is higher than the value set by `Form.setFieldsValue` before the creation of the control when the control is created, causing the control to always display the initial value.

## 2.11.0

2021-03-12

### 🐛 Bugfix

- Fixed a bug that caused console error when `Form.Item` was updated during uninstallation.

## 2.10.0 🏮

2021-02-26

### 🆕 Feature

- The `resetFields` method of `Form` supports passing in a string to reset a single field.

## 2.9.1

2021-02-20

### 🐛 Bugfix

- Fix the bug that the default class name of label is missing when the `labelCol` property of `className` is set in the `Form` component.

## 2.9.0 🔥

2021-02-05

### 🐛 Bugfix

- Fix the bug that the error message displayed in the upper layer of the `Form.Item` is not destroyed when the `Form.Item` component is destroyed.

## 2.7.0

2021-01-15

### 💅 Style

- Fix the problem that the `extra` prompt text of the `Form` component flashes when the verification information is hidden.
- When `Form` is placed in `vertical`, the label adds 4px bottom space.



