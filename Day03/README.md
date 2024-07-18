# HTML Input Types and Attributes

This section provides a comprehensive list of HTML input types, their attributes, and examples.

## Input Types and Examples

| **Type**          | **Description**                                           | **Example**                                                  |
|-------------------|-----------------------------------------------------------|--------------------------------------------------------------|
| `text`            | Single-line text input                                    | `<input type="text" name="username">`                        |
| `password`        | Password input (masked)                                   | `<input type="password" name="password">`                    |
| `email`           | Email address input                                       | `<input type="email" name="email">`                          |
| `tel`             | Telephone number input                                    | `<input type="tel" name="phone">`                            |
| `url`             | URL input                                                 | `<input type="url" name="website">`                          |
| `number`          | Numeric input                                             | `<input type="number" name="quantity" min="1" max="10">`     |
| `range`           | Range input                                               | `<input type="range" name="volume" min="0" max="100">`       |
| `search`          | Search query input                                        | `<input type="search" name="query">`                         |
| `date`            | Date input                                                | `<input type="date" name="birthday">`                        |
| `month`           | Month and year input                                      | `<input type="month" name="expiration">`                     |
| `week`            | Week and year input                                       | `<input type="week" name="week">`                            |
| `time`            | Time input                                                | `<input type="time" name="alarm">`                           |
| `datetime-local`  | Local date and time input                                 | `<input type="datetime-local" name="appointment">`           |
| `checkbox`        | Checkbox input                                            | `<input type="checkbox" name="subscribe" value="newsletter">`|
| `radio`           | Radio button input                                        | `<input type="radio" name="gender" value="male">`            |
| `file`            | File selection input                                      | `<input type="file" name="resume">`                          |
| `submit`          | Submit button                                             | `<input type="submit" value="Submit">`                       |
| `reset`           | Reset button                                              | `<input type="reset" value="Reset">`                         |
| `button`          | General button                                            | `<input type="button" value="Click Me">`                     |
| `image`           | Graphical submit button                                   | `<input type="image" src="submit.png" alt="Submit">`         |
| `hidden`          | Hidden input                                              | `<input type="hidden" name="userID" value="12345">`          |

## Attributes and Examples

| **Attribute**     | **Description**                                           | **Example**                                                  |
|-------------------|-----------------------------------------------------------|--------------------------------------------------------------|
| `type`            | Specifies the type of input                               | `<input type="text">`                                        |
| `name`            | Specifies the name of the input                           | `<input type="text" name="username">`                        |
| `value`           | Specifies the initial value of the input                  | `<input type="text" name="username" value="JohnDoe">`        |
| `id`              | Specifies a unique identifier for the input               | `<input type="text" id="user-id">`                           |
| `class`           | Specifies one or more class names for the input           | `<input type="text" class="form-control">`                   |
| `placeholder`     | Specifies a short hint that describes the expected value  | `<input type="text" placeholder="Enter your username">`      |
| `required`        | Specifies that the input must be filled out               | `<input type="text" required>`                               |
| `readonly`        | Specifies that the input is read-only                     | `<input type="text" value="JohnDoe" readonly>`               |
| `disabled`        | Specifies that the input is disabled                      | `<input type="text" disabled>`                               |
| `maxlength`       | Specifies the maximum number of characters                | `<input type="text" maxlength="10">`                         |
| `minlength`       | Specifies the minimum number of characters                | `<input type="text" minlength="5">`                          |
| `size`            | Specifies the width of the input (in characters)          | `<input type="text" size="20">`                              |
| `pattern`         | Specifies a regular expression the input's value must match | `<input type="text" pattern="[A-Za-z]{3,}">`                 |
| `title`           | Specifies extra information about the input (tooltip)     | `<input type="text" title="Username should be 3-10 characters long">` |
| `autocomplete`    | Specifies whether the input should have autocomplete      | `<input type="text" autocomplete="on">`                      |
| `autofocus`       | Specifies that the input should automatically get focus   | `<input type="text" autofocus>`                              |
| `form`            | Specifies the form the input belongs to                   | `<input type="text" form="form1">`                           |
| `formaction`      | Specifies the URL for form submission                     | `<input type="submit" formaction="/submit-form">`            |
| `formenctype`     | Specifies how form data should be encoded                 | `<input type="submit" formenctype="multipart/form-data">`    |
| `formmethod`      | Specifies the HTTP method for form submission             | `<input type="submit" formmethod="post">`                    |
| `formnovalidate`  | Specifies that the input should not be validated          | `<input type="submit" formnovalidate>`                       |
| `formtarget`      | Specifies where to display the response after submitting  | `<input type="submit" formtarget="_blank">`                  |
| `alt`             | Specifies an alternate text for the input (type="image")  | `<input type="image" src="submit.png" alt="Submit">`         |
| `height`          | Specifies the height of the input (type="image")          | `<input type="image" src="submit.png" height="50">`          |
| `width`           | Specifies the width of the input (type="image")           | `<input type="image" src="submit.png" width="100">`          |
| `max`             | Specifies the maximum value for an input                  | `<input type="number" max="10">`                             |
| `min`             | Specifies the minimum value for an input                  | `<input type="number" min="1">`                              |
| `step`            | Specifies the legal number intervals for an input         | `<input type="number" step="1">`                             |
| `multiple`        | Specifies that the user is allowed to enter more than one value | `<input type="file" multiple>`                         |
